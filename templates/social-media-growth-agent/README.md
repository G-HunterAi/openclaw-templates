# Social Media Growth Agent

**Automate your social media growth across Instagram, TikTok, Twitter/X, and LinkedIn. Strategic content, engagement tactics, and follower growth—all on autopilot.**

## What This Does

Automate social media growth for creators, brands, and agencies. This OpenClaw agent:

- **Content Strategy:** Generate 30-day content calendars optimized for each platform
- **Engagement Automation:** Strategic commenting, liking, DM responses
- **Follower Growth:** Target ideal audience, automated follow/unfollow strategies
- **Analytics Tracking:** Monitor growth metrics, identify what's working
- **Hashtag Research:** Find trending, relevant hashtags for maximum reach
- **Competitor Analysis:** Track competitors, identify content gaps
- **Posting Optimization:** Best times to post, content format recommendations

---

## Who This Is For

✅ **Content creators** who want consistent growth  
✅ **Personal brands** who need strategic visibility  
✅ **Social media managers** handling multiple accounts  
✅ **Agencies** who manage client social media  
✅ **Businesses** who want organic social growth  

---

## What You Get

### 📅 Content Calendar Generation
- **30-day calendars:** Platform-specific content plans
- **Content pillars:** Educational, entertaining, promotional mix
- **Post copy:** Captions, hooks, CTAs pre-written
- **Hashtag sets:** 30 relevant hashtags per post
- **Best times:** Optimal posting schedule based on audience

### 📈 Growth Strategies
- **Target audience research:** Identify ideal followers by niche
- **Competitor analysis:** Who to learn from, what's working
- **Engagement tactics:** Strategic commenting, DM campaigns
- **Collaboration opportunities:** Find accounts for shoutouts/collabs
- **Viral content trends:** Ride trending topics early

### 🤖 Automation Rules
- **Auto-engagement:** Like/comment on target accounts
- **DM sequences:** Welcome new followers, nurture leads
- **Response templates:** Quick replies to common questions
- **Follow/unfollow:** Strategic audience building
- **Story interactions:** Poll responses, question replies

### 📊 Analytics & Reporting
- **Growth tracking:** Followers, engagement rate, reach
- **Content performance:** Top posts, worst performers
- **Audience insights:** Demographics, peak activity times
- **Competitor benchmarks:** How you compare to competitors
- **ROI tracking:** Conversions from social traffic

### 🎯 Platform-Specific Strategies

**Instagram:**
- Reels strategy for discovery
- Story engagement tactics
- Carousel post templates
- Bio optimization
- Link-in-bio strategy

**TikTok:**
- Viral sound/trend tracking
- Hook formulas for first 3 seconds
- FYP optimization tactics
- Duet/stitch opportunities
- Creator fund eligibility

**Twitter/X:**
- Thread templates for engagement
- Reply-guy strategy (done tastefully)
- Tweet scheduling for timezone coverage
- Space hosting strategies
- Quote-tweet opportunities

**LinkedIn:**
- Thought leadership content
- Engagement pod strategies
- Comment-first approach
- Profile optimization
- Newsletter integration

---

## Quick Start (5 Minutes)

### 1. Install in OpenClaw

```bash
# Install from ClawHub
openclaw skills install social-media-growth-agent

# Or download this template manually
git clone https://github.com/G-HunterAi/openclaw-templates.git
cd openclaw-templates/templates/social-media-growth-agent
```

### 2. Configure Your Accounts

Edit `config.json`:

```json
{
  "accounts": [
    {
      "platform": "instagram",
      "handle": "@yourhandle",
      "niche": "fitness",
      "goals": ["grow_to_10k", "increase_engagement"]
    }
  ],
  "target_audience": {
    "interests": ["fitness", "wellness", "nutrition"],
    "demographics": "women 25-45",
    "competitor_accounts": ["@competitor1", "@competitor2"]
  }
}
```

### 3. Generate Content

**Option A: 30-Day Content Calendar**
```
Hey OpenClaw, generate a 30-day Instagram content calendar for my fitness account. Focus on workout tips, nutrition advice, and transformation content.
```

**Option B: Daily Content Ideas**
```
Give me 5 Instagram Reel ideas for today that are likely to go viral in the fitness niche.
```

**Option C: Engagement Strategy**
```
Create a 7-day engagement strategy to grow my Instagram by 500 followers. Include target accounts, commenting tactics, and DM sequences.
```

---

## Configuration Files

### `config.json` - Your Social Media Setup
```json
{
  "accounts": [
    {
      "platform": "instagram",
      "handle": "@fitcoach_sarah",
      "niche": "fitness_coaching",
      "follower_count": 5000,
      "goals": [
        "grow_to_10k",
        "increase_engagement_rate_to_5_percent",
        "drive_traffic_to_website"
      ],
      "posting_frequency": {
        "feed_posts": "3x/week",
        "reels": "5x/week",
        "stories": "daily"
      }
    }
  ],
  "target_audience": {
    "niche": "Busy professionals who want to get fit",
    "demographics": "Women 30-50, working professionals",
    "interests": [
      "home workouts",
      "meal prep",
      "work-life balance",
      "healthy habits"
    ],
    "pain_points": [
      "No time for gym",
      "Don't know where to start",
      "Need accountability"
    ],
    "competitor_accounts": [
      "@kayla_itsines",
      "@blogilates",
      "@sweat"
    ]
  },
  "content_pillars": [
    {
      "name": "Workout Tips",
      "percentage": 40,
      "types": ["Reels", "Carousels"]
    },
    {
      "name": "Nutrition Advice",
      "percentage": 30,
      "types": ["Carousels", "Stories"]
    },
    {
      "name": "Transformation Stories",
      "percentage": 20,
      "types": ["Reels", "Feed posts"]
    },
    {
      "name": "Promotional",
      "percentage": 10,
      "types": ["Stories", "Feed posts"]
    }
  ]
}
```

### `growth_strategies.json` - Proven Tactics
Pre-built growth strategies:
- Follow/unfollow campaigns
- Engagement pod setups
- DM outreach sequences
- Collaboration frameworks
- Viral content formulas
- Hashtag research methods

### `content_templates.json` - Post Formats
Ready-to-use templates for:
- Instagram Reels (hooks, scripts, CTAs)
- TikTok videos (viral formulas)
- Twitter threads (engagement frameworks)
- LinkedIn posts (thought leadership)
- Carousel posts (swipe-worthy formats)

---

## Example Outputs

### 📅 30-Day Instagram Content Calendar
```
INSTAGRAM CONTENT CALENDAR - MARCH 2026
Account: @fitcoach_sarah | Niche: Fitness Coaching

WEEK 1: Foundation Week (Focus: Value + Trust Building)

MONDAY (Mar 3) - REEL
Title: "3 Exercises Busy Moms NEED"
Hook: "If you only do 3 exercises this week..."
Content: Squats, push-ups, planks (demo with modifications)
CTA: "Save this for your next workout!"
Hashtags: #fitmom #busymomworkout #homeworkout #momfitness [+26 more]
Post Time: 7:00 AM PST
Expected Reach: 5,000-8,000

WEDNESDAY (Mar 5) - CAROUSEL (10 slides)
Title: "10 Meal Prep Hacks for Busy Professionals"
Slide 1: "Meal prep doesn't have to take hours..."
Slides 2-10: Quick hacks (batch cooking, mason jar salads, etc.)
CTA: "Which hack are you trying first?"
Hashtags: #mealprep #healthyeating #mealplanning [+27 more]
Post Time: 12:00 PM PST
Expected Engagement: 400-600 likes, 50-80 comments

FRIDAY (Mar 7) - REEL
Title: "15-Minute Living Room HIIT"
Hook: "No equipment? No problem."
Content: Follow-along HIIT circuit
CTA: "Try it and let me know how you did!"
Hashtags: #hiitworkout #quickworkout #homeworkout [+27 more]
Post Time: 6:00 PM PST
Expected Reach: 8,000-12,000

SATURDAY (Mar 8) - STORY SERIES
Theme: "Weekend Workout Challenge"
Story 1: Poll - "Are you working out today?"
Story 2: 3 quick workout options
Story 3: Link to free workout guide (link sticker)
Story 4: "Tag me in your workout!"

SUNDAY (Mar 9) - FEED POST
Title: Client Transformation Spotlight
Content: Before/after (with permission) + client story
CTA: "Comment 'READY' if you want results like this"
Hashtags: #transformation #fitnessjourney #results [+27 more]
Post Time: 10:00 AM PST
Expected Engagement: 500-800 likes, 100+ comments

---

WEEK 2: Engagement Week (Focus: Community Building)

MONDAY (Mar 10) - REEL
Title: "POV: Your Excuses vs. Reality"
Hook: Trending audio + relatable fitness excuses
Content: Funny/relatable content (excuses we all make)
CTA: "Which excuse do you use most? 👇"
Hashtags: #fitnesshumor #relatable #fitnessmotivation [+27 more]
Post Time: 7:00 AM PST
Expected Reach: 10,000-15,000 (trending audio boost)

[...25 more days with similar detail...]

---

MONTHLY GROWTH TARGETS:
- Follower goal: +1,000 (5,000 → 6,000)
- Engagement rate: 4.5% average
- Story views: 1,500+ per story
- Reel views: 5,000+ average
- Profile visits: 8,000+
- Link clicks: 300+
```

### 🎯 7-Day Growth Sprint Strategy
```
7-DAY INSTAGRAM GROWTH SPRINT
Goal: +500 Followers in 7 Days

Strategy: Aggressive engagement + viral content + strategic networking

DAY 1: FOUNDATION
Morning (9-10 AM):
- Post carousel: "10 Things I Wish I Knew Before Starting My Fitness Journey"
- Use trending hashtags + niche hashtags
- Pin comment: "Which one surprised you most?"

Midday (12-1 PM):
- Engage with 50 accounts in target audience:
  - Find via competitor followers + fitness hashtags
  - Like 3-5 recent posts
  - Leave thoughtful comment on 1-2 posts
  - Follow accounts that align with your niche

Afternoon (3-4 PM):
- Post 3-5 stories:
  - Behind-the-scenes of your day
  - Poll: "Cardio or strength training?"
  - Question sticker: "What's your biggest fitness struggle?"

Evening (7-8 PM):
- Reply to ALL comments on your carousel post
- Engage with stories from your recent followers
- DM 10 new followers: "Hey [name]! Thanks for the follow. What brings you to my page?"

Target: 50-70 new followers Day 1

---

DAY 2: VIRAL PUSH
Morning (7-8 AM):
- Post Reel using trending audio:
  - Hook within 1 second
  - Educational + entertaining
  - Strong CTA in caption
- Share to stories immediately

Midday (12-1 PM):
- Engagement round 2:
  - 50 new target accounts
  - Focus on accounts with 1K-10K followers (more likely to engage back)
  - Use "engagement groups" if you have them

Afternoon (4-5 PM):
- Monitor Reel performance
- If doing well: boost visibility by sharing again to stories, asking friends to share
- Reply to every comment ASAP (algorithm boost)

Evening (8-9 PM):
- Go live for 15-20 minutes:
  - Topic: Quick Q&A or mini workout
  - Engage with viewers by name
  - Announce when you'll go live next

Target: 80-100 new followers Day 2 (viral Reel boost)

---

DAYS 3-7: [Similar detailed strategies...]

---

WEEK TOTALS:
Expected new followers: 500-700
Engagement rate increase: 1-2%
Story views increase: 30-50%
Profile visits: 3,000+

Success metrics:
✅ Post engagement rate >5%
✅ Reel views >10K on at least 2 Reels
✅ DM response rate >50%
✅ Follower retention >95% (minimal unfollows)
```

### 📊 Competitor Analysis Report
```
COMPETITOR ANALYSIS: Fitness Niche
Date: Feb 14, 2026

COMPETITOR #1: @kayla_itsines
Followers: 16.2M
Avg Engagement Rate: 2.3%
Posting Frequency: 5-7x/week

Content Strategy:
- 60% Workout videos (Reels)
- 25% Transformation posts
- 10% Community/motivational
- 5% Product/promotional

What's Working:
✅ Consistent Reels (3-5x/week)
✅ Strong community hashtag (#BBGCommunity)
✅ User-generated content features
✅ Clear workout demonstrations

What We Can Learn:
→ More Reels featuring client transformations
→ Create branded hashtag for community
→ Feature client content weekly
→ Clear, simple workout demos

Content Gaps (Our Opportunities):
→ Nutrition content (they focus mainly on workouts)
→ Mindset/habit content (we can own this)
→ Quick tips for busy professionals (their audience skews younger)

---

COMPETITOR #2: @blogilates
Followers: 2.9M
Avg Engagement Rate: 4.8%
Posting Frequency: 3-4x/week

Content Strategy:
- 50% Workout videos
- 30% Lifestyle/personality content
- 15% Product reviews/recommendations
- 5% Community challenges

What's Working:
✅ Strong personality (very authentic)
✅ Monthly challenges (creates recurring engagement)
✅ Mix of free + paid content
✅ Collaboration with other creators

What We Can Learn:
→ Show more personality (not just workouts)
→ Launch monthly challenges
→ Collaborate with complementary creators
→ Balance free value + paid offerings

---

OUR POSITIONING OPPORTUNITY:
"The fitness coach for busy professionals who need results WITHOUT hours at the gym"

Differentiation Strategy:
1. Time-efficient workouts (10-30 min)
2. Meal prep for people who hate cooking
3. Work-life balance focus
4. No-BS, science-backed advice
```

---

## Advanced Features

### 🤖 Engagement Automation
- **Smart commenting:** AI-generated comments that feel human
- **DM automation:** Welcome sequences, FAQ responses
- **Story engagement:** Auto-poll responses, question replies
- **Follow/unfollow:** Target ideal followers, unfollow non-engagers

### 📈 Analytics Dashboard
- **Growth tracking:** Daily follower changes, engagement trends
- **Content performance:** Top posts, optimal posting times
- **Audience insights:** Demographics, interests, behavior
- **Competitor tracking:** Monitor competitor growth and content

### 🎨 Content Creation Tools
- **Caption generator:** Multiple options per post
- **Hashtag research:** Trending + niche hashtags
- **Hook formulas:** First-3-second Reel hooks
- **CTA templates:** Drive actions (comment, share, click)

### 🤝 Collaboration Finder
- **Ideal collaborators:** Accounts in your niche for shoutouts/collabs
- **Engagement pods:** Find/create pods for mutual growth
- **Influencer outreach:** Templates for partnership requests

---

## Pricing & ROI

### 💰 What This Agent Replaces
- **Social media manager:** $1,000-3,000/month
- **Content calendar planning:** 10-15 hours/month
- **Engagement time:** 30+ hours/month
- **Analytics tracking:** 5 hours/month

**Total value:** $1,000-3,000/month  
**OpenClaw template cost:** $67-97 one-time

### 📈 Expected Results (90 Days)
- **Follower growth:** 1,000-5,000+ (depending on starting size, niche, consistency)
- **Engagement rate:** 2-3x improvement
- **Content output:** 10x more consistent
- **Time saved:** 40+ hours/month

---

## Support & Updates

- **Documentation:** Full video walkthrough included
- **Updates:** Free updates as platforms evolve
- **Support:** Email support@openclaw-templates.com
- **Community:** Join Discord for creator collaboration

---

## FAQ

**Q: Will this get my account banned?**  
A: All strategies are within platform TOS. We avoid spam tactics. Growth is organic and sustainable.

**Q: How much time do I need to invest?**  
A: 30-60 min/day for posting + engagement. Agent automates research, planning, and content creation.

**Q: Does this work for all niches?**  
A: Yes. Templates are customizable for any niche (fitness, business, lifestyle, tech, etc.).

**Q: Can I manage multiple accounts?**  
A: Absolutely. Configure multiple accounts in config.json.

**Q: What if I'm camera-shy (for video content)?**  
A: We include faceless content strategies for every platform.

**Q: How fast will I grow?**  
A: Realistic: 500-2,000 followers/month depending on niche, consistency, content quality.

---

## Next Steps

1. **Install the template** (5 minutes)
2. **Configure your accounts** (10 minutes)
3. **Generate your first 30-day calendar** (5 minutes)
4. **Start posting consistently** 
5. **Watch your growth accelerate** 📈

**Ready to grow your social media on autopilot?**

[Get the Social Media Growth Agent →](#)

---

## License & Usage

- ✅ Use for your own accounts (unlimited)
- ✅ Manage client accounts (agencies)
- ✅ Customize strategies for your niche
- ❌ Do not resell this template as-is
- ❌ Do not share your OpenClaw API keys

---

**Built by:** Hunter (OpenClaw Templates)  
**Version:** 1.0.0  
**Last Updated:** February 2026  
**Support:** [Discord](https://discord.gg/openclaw) | [Email](mailto:support@openclaw-templates.com)
