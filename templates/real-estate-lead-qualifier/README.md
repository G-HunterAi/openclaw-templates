# Real Estate Lead Qualifier - OpenClaw Agent Template

**Version:** 1.0  
**Price:** $97  
**Setup Time:** 5-10 minutes  
**Skill Level:** Beginner-friendly

---

## What This Does

Automatically screens real estate leads from MLS, Zillow, or other sources, qualifies them via SMS/email, schedules showings, and updates your CRM—all without manual intervention.

**Perfect for:**
- Real estate agents handling 10+ leads/day
- Brokers managing team lead distribution
- Investors screening rental inquiries
- Anyone tired of manually qualifying leads

---

## What You Get

- ✅ Pre-configured OpenClaw agent
- ✅ Lead qualification workflow (phone, email, budget, timeline)
- ✅ Automated SMS/email responses
- ✅ Showing scheduler (integrates with your calendar)
- ✅ CRM auto-update (HubSpot, Salesforce, Zillow CRM)
- ✅ Daily lead summary reports
- ✅ 5-minute video walkthrough
- ✅ Example workflows + test scenarios

---

## How It Works

### Step 1: Lead Capture
- Monitors MLS feed, Zillow, Realtor.com, or web forms
- Extracts: Name, phone, email, property interest, budget, timeline

### Step 2: Initial Contact
- Sends personalized SMS or email within 5 minutes
- "Hi [Name], thanks for your interest in [Property]. I'm [Your Name]'s AI assistant. Quick question: Are you pre-approved for financing?"

### Step 3: Qualification
- Asks 5 key questions:
  1. Pre-approved? (Yes/No/Need help)
  2. Budget range? ($200K-300K, $300K-400K, etc.)
  3. Timeline? (This week, this month, 2-3 months, just browsing)
  4. Working with other agents? (Yes/No)
  5. Best time for showing? (Morning, afternoon, evening, weekend)

### Step 4: Scoring & Routing
- Scores lead (Hot, Warm, Cold)
- Hot leads → Immediate notification + your calendar
- Warm leads → Follow-up sequence
- Cold leads → Nurture campaign

### Step 5: Showing Scheduler
- Hot leads get calendar link automatically
- Books showing in your Google/Outlook calendar
- Sends confirmation + reminder texts

### Step 6: CRM Update
- Updates lead status automatically
- Adds notes from conversation
- Tags by score (Hot/Warm/Cold)
- Triggers workflows in your CRM

---

## Setup Instructions

### Prerequisites

1. **OpenClaw installed** (get it at openclaw.ai)
2. **API keys:**
   - Twilio (for SMS) - free trial available
   - SendGrid (for email) - free up to 100/day
   - Your CRM API key (HubSpot, Salesforce, etc.)
3. **Lead source** (MLS feed, Zillow, web form)

### Installation (5 minutes)

**Step 1: Download template**
```bash
# Extract ZIP file to your OpenClaw workspace
cd /path/to/openclaw/workspace
unzip real-estate-lead-qualifier.zip
```

**Step 2: Run setup script**
```bash
cd real-estate-lead-qualifier
./setup.sh
```

This will:
- Copy template files to your workspace
- Install required ClawHub skills
- Prompt for your API keys
- Create test lead for validation

**Step 3: Configure**

Edit `USER.md` with your details:
```yaml
name: "Your Name"
brokerage: "Your Brokerage"
license: "CA DRE #12345678"
phone: "+1-555-123-4567"
email: "you@realestate.com"
```

Edit `TOOLS.md` with your integrations:
```yaml
crm: "hubspot"  # or "salesforce", "zillow-crm", "follow-up-boss"
calendar: "google"  # or "outlook", "apple"
sms_provider: "twilio"
email_provider: "sendgrid"
```

**Step 4: Test**

```bash
# Run test scenario
./test-lead.sh
```

This simulates a lead and walks you through the qualification flow.

**Step 5: Go Live**

```bash
# Start agent
openclaw start
```

Your agent is now monitoring for leads!

---

## Configuration

### Qualification Questions (Customize)

Edit `config/questions.json`:

```json
{
  "questions": [
    {
      "id": "preapproval",
      "text": "Are you pre-approved for financing?",
      "type": "multiple_choice",
      "options": ["Yes", "No", "Need help"],
      "weight": 30
    },
    {
      "id": "budget",
      "text": "What's your budget range?",
      "type": "multiple_choice",
      "options": ["Under $200K", "$200K-300K", "$300K-400K", "$400K-500K", "$500K+"],
      "weight": 25
    }
    // ... customize your questions
  ]
}
```

### Lead Scoring (Customize)

Edit `config/scoring.json`:

```json
{
  "hot_threshold": 70,  // Score >= 70 = Hot lead
  "warm_threshold": 40,  // Score 40-69 = Warm lead
  "weights": {
    "preapproval": 30,
    "budget": 25,
    "timeline": 20,
    "exclusive": 15,
    "availability": 10
  }
}
```

### Response Templates (Customize)

Edit `config/templates.json`:

```json
{
  "initial_sms": "Hi {{name}}, thanks for your interest in {{property}}. I'm {{agent_name}}'s AI assistant. Quick question: {{first_question}}",
  "hot_lead_alert": "🔥 HOT LEAD: {{name}} ({{score}}/100)\n- Budget: {{budget}}\n- Timeline: {{timeline}}\n- Pre-approved: {{preapproval}}\n- Book showing: {{calendar_link}}",
  // ... customize all templates
}
```

---

## Integrations

### Supported CRMs

- ✅ **HubSpot** - Full integration (contacts, deals, tasks)
- ✅ **Salesforce** - Full integration (leads, opportunities, activities)
- ✅ **Zillow CRM** - Basic integration (lead import, status update)
- ✅ **Follow Up Boss** - Full integration
- ✅ **KVCore** - Basic integration
- ⏳ **Custom** - Webhook/API configuration available

### Supported Lead Sources

- ✅ **MLS feeds** (via RETS/RESO)
- ✅ **Zillow Premier Agent**
- ✅ **Realtor.com Connections Plus**
- ✅ **Web forms** (your website, landing pages)
- ✅ **Email** (monitor inbox for lead emails)
- ✅ **Webhooks** (integrate with any system)

### Supported Calendars

- ✅ **Google Calendar**
- ✅ **Outlook Calendar**
- ✅ **Apple Calendar** (via iCloud)
- ✅ **Calendly** (for custom booking flows)

---

## Examples & Use Cases

### Example 1: Zillow Lead

**Incoming:**
```
Name: Sarah Johnson
Phone: 555-234-5678
Property: 123 Main St, $425K
Source: Zillow Premier Agent
```

**Agent Actions:**
1. Sends SMS within 3 minutes
2. Qualifies via 5 questions (takes 2-3 minutes via text)
3. Scores: 85/100 (Hot lead - pre-approved, budget matches, ready this week)
4. Sends you alert: "🔥 HOT LEAD: Sarah Johnson (85/100)"
5. Books showing in your calendar for Thursday 3pm
6. Updates HubSpot: Contact created, Deal opened, Task assigned
7. Sends Sarah confirmation: "Great! Your showing is Thursday at 3pm with [Your Name]"

**Time saved:** 15-20 minutes per lead

### Example 2: Cold Lead Nurture

**Incoming:**
```
Name: Mike Chen
Property: 789 Oak Ave, $550K
Budget: "Just browsing"
Timeline: "6-12 months"
```

**Agent Actions:**
1. Scores: 25/100 (Cold lead)
2. Adds to nurture campaign (no immediate alert)
3. Sends weekly market updates about similar properties
4. Monitors engagement (opens, clicks)
5. Re-scores when engagement increases
6. Escalates to Warm when timeline moves to "2-3 months"

**Conversion:** 15-20% of cold leads convert within 6 months

### Example 3: Team Distribution

**Incoming:**
Multiple leads simultaneously from various sources

**Agent Actions:**
1. Scores all leads
2. Distributes based on rules:
   - Hot leads → Top performer or on-call agent
   - Warm leads → Round-robin distribution
   - Cold leads → Junior agent or ISA
3. Updates team dashboard
4. Sends daily summary to broker

**Result:** Fair distribution, faster response times, higher conversion

---

## Pricing & ROI

### Cost Breakdown

**One-time:**
- Template: $97

**Monthly (estimated):**
- Twilio SMS: $1-10/month (1¢ per SMS, 100-1000 leads)
- SendGrid Email: Free (or $15/month for 40K emails)
- OpenClaw: Free (self-hosted) or $20/month (cloud)
- **Total: $1-30/month**

### ROI Calculation

**Assumptions:**
- Average commission: $12,000
- Response time improvement: 15 minutes → 3 minutes
- Conversion increase: 2% (industry data: faster response = higher close rate)

**Scenario:**
- 100 leads/month
- 2% additional conversion = 2 extra deals/year
- 2 deals × $12,000 = **$24,000 additional revenue**

**ROI:** 24,700% ($24,000 return on $97 investment)

---

## Troubleshooting

### "SMS not sending"
- Check Twilio credentials in `TOOLS.md`
- Verify phone number is verified
- Check Twilio console for errors

### "CRM not updating"
- Check API key permissions (needs read/write)
- Test API key with: `./test-crm-connection.sh`
- Check CRM rate limits

### "Leads not being captured"
- Check lead source configuration in `HEARTBEAT.md`
- Verify webhook URL or email monitor settings
- Run: `./test-lead-capture.sh`

### "Agent not responding"
- Check OpenClaw status: `openclaw status`
- Check logs: `openclaw logs --tail 100`
- Restart agent: `openclaw restart`

---

## Advanced Customization

### Add Custom Fields

Edit `config/custom-fields.json`:

```json
{
  "fields": [
    {
      "name": "property_type",
      "question": "Are you looking for a single-family home, condo, or townhouse?",
      "type": "multiple_choice",
      "options": ["Single-family", "Condo", "Townhouse", "Multi-unit"]
    }
  ]
}
```

### Integrate with Your Website

Add to your contact form:

```html
<form action="https://your-openclaw-instance/webhook/lead-capture" method="POST">
  <input type="hidden" name="source" value="website">
  <input type="text" name="name" placeholder="Name" required>
  <input type="email" name="email" placeholder="Email" required>
  <input type="tel" name="phone" placeholder="Phone" required>
  <input type="text" name="property" placeholder="Property Address">
  <button type="submit">Submit</button>
</form>
```

### Build Custom Workflows

See `examples/custom-workflows.md` for examples:
- Buyer vs. seller qualification
- Luxury property handling
- Investor screening
- Rental inquiries

---

## Support

### Documentation
- Full docs: `/docs/`
- Video tutorials: `/videos/`
- Example configs: `/examples/`

### Community
- Discord: #real-estate-agents
- GitHub: Issues & discussions
- Email: support@openclaw-templates.com (placeholder)

### Updates
- Minor updates: Free (bug fixes, small features)
- Major updates: 50% discount for existing customers

---

## License

**Single-user license included**  
- Use on 1 OpenClaw instance
- Modify/customize freely
- Do NOT resell or redistribute template
- Commercial use allowed (for your business)

**Team license:** $197 (up to 5 agents)  
**Brokerage license:** $497 (unlimited agents)

---

## Version History

**v1.0 (Feb 15, 2026)**
- Initial release
- HubSpot, Salesforce, Zillow CRM support
- SMS + Email qualification
- Google Calendar integration
- 5-question default flow

**Roadmap (v1.1+)**
- Voice call integration (AI phone agent)
- Spanish language support
- Additional CRM integrations
- Video showing scheduler
- Automated follow-up campaigns

---

**Questions? Issues? Feature requests?**  
Open an issue on GitHub or email support.

**Ready to 10x your lead response time?**  
Get started in 5 minutes. 🚀
