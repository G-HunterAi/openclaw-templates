# Longevity Protocol Generator

**Generate personalized health optimization protocols based on latest longevity research. Automate client assessments, protocol creation, and progress tracking.**

## What This Does

Automate evidence-based longevity protocol generation for health coaches, wellness practitioners, and biohackers. This OpenClaw agent:

- **Client Assessments:** Comprehensive intake forms (health history, goals, biomarkers)
- **Protocol Generation:** Personalized recommendations (nutrition, supplements, exercise, sleep, stress)
- **Research Integration:** Latest longevity studies and biomarker optimization
- **Progress Tracking:** Monitor client improvements over time
- **Client Communication:** Automated check-ins, educational content, protocol adjustments
- **Compliance Tools:** Habit tracking, supplement reminders, milestone celebrations

---

## Who This Is For

✅ **Health coaches** who create custom protocols for clients  
✅ **Longevity clinics** who need scalable client onboarding  
✅ **Wellness practitioners** who optimize health span  
✅ **Biohackers** who track personal optimization  
✅ **Nutritionists** who design personalized plans  

---

## What You Get

### 📋 Client Assessment System
- **Comprehensive intake:** Health history, current status, goals
- **Biomarker analysis:** Blood work interpretation, optimal ranges
- **Lifestyle audit:** Sleep, nutrition, exercise, stress, social connection
- **Risk stratification:** Identify high-priority interventions
- **Goal setting:** SMART goals for healthspan optimization

### 🧬 Protocol Generation
- **Nutrition protocols:** Macros, meal timing, fasting strategies
- **Supplement stacks:** Evidence-based supplementation with dosing
- **Exercise prescriptions:** Zone 2 cardio, strength training, mobility
- **Sleep optimization:** Sleep hygiene, circadian rhythm alignment
- **Stress management:** HRV training, meditation, breathwork
- **Hormone optimization:** Testosterone, estrogen, thyroid, cortisol
- **Metabolic health:** Glucose regulation, insulin sensitivity, mitochondrial function

### 📊 Biomarker Optimization
- **Blood panels:** Optimal ranges for longevity (not just "normal")
- **CGM data:** Continuous glucose monitoring analysis
- **HRV tracking:** Heart rate variability trends
- **Sleep data:** Deep sleep, REM, sleep efficiency
- **Body composition:** Lean mass, fat mass, visceral fat
- **Functional testing:** VO2 max, grip strength, balance

### 📚 Educational Content
- **Client handouts:** Protocol explanations, research summaries
- **Video scripts:** Educational content for client portal
- **Email sequences:** Onboarding, compliance, milestone emails
- **FAQ library:** Common questions about protocols

### 📈 Progress Tracking
- **Check-in templates:** Weekly/monthly assessments
- **Before/after analysis:** Biomarker improvements over time
- **Compliance tracking:** Supplement adherence, habit consistency
- **Protocol adjustments:** Dynamic optimization based on results

---

## Quick Start (5 Minutes)

### 1. Install in OpenClaw

```bash
# Install from ClawHub
openclaw skills install longevity-protocol-generator

# Or download this template manually
git clone https://github.com/G-HunterAi/openclaw-templates.git
cd openclaw-templates/templates/longevity-protocol-generator
```

### 2. Configure Your Practice

Edit `config.json`:

```json
{
  "practice_info": {
    "name": "Your Longevity Clinic",
    "practitioner_name": "Dr. Smith",
    "specialties": ["metabolic health", "hormone optimization"],
    "target_clients": "High-performing executives 35-55"
  },
  "protocol_focus": [
    "metabolic_health",
    "hormone_optimization",
    "sleep_quality",
    "cognitive_performance"
  ]
}
```

### 3. Generate Protocols

**Option A: New Client Intake (Recommended)**
```
Hey OpenClaw, create a comprehensive intake assessment for a new longevity client. Include health history, biomarkers, lifestyle audit, and goal setting.
```

**Option B: Generate Protocol from Intake**
```
Based on this client intake [paste data], generate a 90-day longevity protocol focusing on metabolic health and sleep optimization.
```

**Option C: Analyze Biomarkers**
```
Analyze these blood work results [paste lab values]. Identify suboptimal markers and recommend interventions to reach longevity-optimal ranges.
```

---

## Configuration Files

### `config.json` - Your Practice Settings
```json
{
  "practice_info": {
    "name": "Optimal Health Lab",
    "practitioner_name": "Dr. Sarah Johnson",
    "credentials": "MD, Functional Medicine",
    "specialties": [
      "Metabolic health",
      "Hormone optimization",
      "Longevity medicine"
    ],
    "target_clients": "Executives and entrepreneurs 35-60 seeking healthspan optimization"
  },
  "protocol_pillars": [
    "Metabolic health (glucose, insulin, mitochondria)",
    "Hormone optimization (testosterone, thyroid, cortisol)",
    "Sleep quality (deep sleep, REM, circadian rhythm)",
    "Cardiovascular health (VO2 max, blood pressure, lipids)",
    "Cognitive performance (brain health, focus, memory)",
    "Body composition (lean mass, visceral fat)"
  ],
  "biomarker_panels": {
    "essential": [
      "Fasting glucose",
      "HbA1c",
      "Lipid panel (LDL-C, HDL-C, Triglycerides, ApoB)",
      "Thyroid (TSH, Free T3, Free T4)",
      "Vitamin D",
      "hsCRP (inflammation)"
    ],
    "advanced": [
      "Insulin",
      "HOMA-IR",
      "Testosterone (total, free)",
      "Estradiol",
      "DHEA-S",
      "Cortisol (AM/PM)",
      "IGF-1",
      "Homocysteine",
      "Liver enzymes (ALT, AST, GGT)"
    ]
  },
  "intervention_priorities": [
    "Nutrition",
    "Exercise",
    "Sleep",
    "Stress management",
    "Supplements",
    "Medications (if needed)"
  ]
}
```

### `protocol_templates.json` - Evidence-Based Interventions
Pre-built protocol modules:
- Metabolic health (glucose optimization, insulin sensitivity)
- Hormone optimization (testosterone, thyroid, estrogen)
- Sleep protocols (circadian rhythm, sleep hygiene, supplements)
- Exercise prescriptions (Zone 2, HIIT, strength, mobility)
- Supplement stacks (foundational, performance, longevity)
- Fasting strategies (time-restricted eating, prolonged fasting)

### `biomarker_ranges.json` - Optimal Targets
Longevity-optimal ranges (not just "normal"):
- Fasting glucose: 70-85 mg/dL (not <100)
- HbA1c: <5.3% (not <5.7%)
- Triglycerides: <70 mg/dL (not <150)
- HDL-C: >60 mg/dL
- ApoB: <80 mg/dL (not <130)
- Vitamin D: 50-80 ng/mL (not >30)

---

## Example Outputs

### 📋 Client Intake Assessment
```
LONGEVITY CLIENT INTAKE

CLIENT PROFILE:
Name: John Smith
Age: 45
Sex: Male
Goals: Lose 20 lbs, improve energy, optimize metabolic health

HEALTH HISTORY:
- Pre-diabetes (HbA1c 5.9%)
- Elevated blood pressure (135/85)
- Poor sleep (5-6 hours/night)
- Sedentary lifestyle (desk job)
- High stress (executive role)

CURRENT BIOMARKERS:
✅ GOOD:
- HDL-C: 55 mg/dL (acceptable)
- Vitamin D: 45 ng/mL (adequate)

⚠️ SUBOPTIMAL:
- Fasting glucose: 105 mg/dL (target: <85)
- HbA1c: 5.9% (target: <5.3%)
- Triglycerides: 180 mg/dL (target: <70)
- hsCRP: 3.2 mg/L (elevated inflammation)
- Testosterone: 350 ng/dL (low for age)

❌ CONCERNING:
- HOMA-IR: 3.5 (insulin resistant, target: <1.5)
- Visceral fat: 35% (obese range)

LIFESTYLE AUDIT:
- Sleep: 5-6 hours (target: 7-9)
- Exercise: Sedentary (target: 150+ min/week)
- Nutrition: High carb, low protein, irregular meals
- Stress: High (no management strategies)
- Alcohol: 2-3 drinks/night (excess)

PRIORITY INTERVENTIONS:
1. Metabolic health (insulin sensitivity, glucose regulation)
2. Sleep optimization (circadian rhythm, sleep hygiene)
3. Hormone optimization (testosterone)
4. Body composition (lose fat, gain muscle)
5. Cardiovascular health (blood pressure, lipids)

RISK STRATIFICATION: HIGH
- Pre-diabetes → Type 2 diabetes risk
- Metabolic syndrome (4/5 criteria met)
- Cardiovascular disease risk (elevated BP, lipids, inflammation)

RECOMMENDED PROTOCOL: 90-Day Metabolic Reset
Focus: Reverse insulin resistance, optimize sleep, restore hormones
```

### 🧬 90-Day Longevity Protocol
```
90-DAY METABOLIC RESET PROTOCOL
Client: John Smith | Start Date: Feb 14, 2026

PHASE 1: FOUNDATION (Days 1-30)
Goal: Stabilize glucose, improve sleep, establish habits

NUTRITION:
- Time-restricted eating: 16:8 (eating window 12pm-8pm)
- Macros: 40% protein, 30% carbs, 30% fat
- Target: 180g protein, 135g carbs, 60g fat (1,800 cal)
- Eliminate: Refined carbs, seed oils, alcohol
- Prioritize: Lean protein, non-starchy vegetables, healthy fats
- Meal timing: Protein-forward breakfast (12pm), light dinner (6pm)

SUPPLEMENTS (Foundational):
- Magnesium glycinate: 400mg before bed (sleep + insulin)
- Vitamin D3 + K2: 5,000 IU daily (maintain 50-80 ng/mL)
- Omega-3 (EPA/DHA): 2-3g daily (inflammation, cardiovascular)
- Berberine: 500mg 2x/day (glucose regulation)
- Creatine: 5g daily (muscle, cognitive function)

EXERCISE:
- Zone 2 cardio: 3x/week, 30 min (build aerobic base)
- Resistance training: 2x/week, full body (build muscle)
- Daily walks: 10,000 steps (NEAT, glucose disposal)

SLEEP PROTOCOL:
- Target: 7.5-8 hours (11pm-7am)
- Wind-down routine: 9:30pm (no screens, dim lights)
- Morning sunlight: 10 min within 30 min of waking (circadian reset)
- Bedroom: Cool (65-68°F), dark (blackout curtains), quiet
- Supplements: Magnesium glycinate 400mg, glycine 3g, apigenin 50mg

STRESS MANAGEMENT:
- HRV training: 10 min/day (breathwork, biofeedback)
- Meditation: 10 min/day (morning or evening)
- Cold exposure: 2x/week (3 min cold shower)

TRACKING:
- Continuous glucose monitor (CGM): 24/7 for 30 days
- Daily check-ins: Weight, sleep quality, energy (1-10)
- Weekly photos: Front, side, back (body composition)

PHASE 1 TARGETS:
- Fasting glucose: <100 mg/dL
- Average glucose: <110 mg/dL
- Glucose variability: <30 mg/dL
- Sleep: 7+ hours consistently
- Weight: -5-8 lbs (mostly fat)

---

PHASE 2: OPTIMIZATION (Days 31-60)
Goal: Deepen insulin sensitivity, optimize hormones, increase performance

NUTRITION ADJUSTMENTS:
- Consider carb cycling: Low carb (5 days), moderate carb (2 days)
- Increase protein: 200g daily (preserve muscle during fat loss)
- Post-workout carbs: 50-100g (glucose disposal, muscle glycogen)

SUPPLEMENTS (Added):
- Tongkat Ali: 300mg daily (testosterone support)
- Vitamin K2 (MK-7): 200mcg (with D3, bone health)
- Alpha-lipoic acid: 600mg daily (glucose disposal, antioxidant)
- NAD+ precursor (NMN or NR): 250mg daily (cellular energy)

EXERCISE PROGRESSION:
- Zone 2 cardio: 4x/week, 45 min
- Resistance training: 3x/week, split routine
- Add HIIT: 1x/week, 20 min (metabolic conditioning)
- VO2 max test: Establish baseline

ADVANCED TRACKING:
- DEXA scan: Body composition (lean mass, fat mass, visceral fat)
- Blood work: Repeat metabolic panel, hormones, inflammation
- HRV trends: Weekly average (recovery, stress adaptation)

PHASE 2 TARGETS:
- Fasting glucose: <90 mg/dL
- HbA1c: <5.5%
- HOMA-IR: <2.0
- Testosterone: >500 ng/dL
- Weight: -10-15 lbs total
- VO2 max: Improve by 10%

---

PHASE 3: MASTERY (Days 61-90)
Goal: Lock in habits, optimize performance, prepare for maintenance

NUTRITION REFINEMENT:
- Protein: Maintain 200g
- Carbs: Individualized based on CGM data and performance
- Consider monthly 48-hour fast (autophagy, insulin sensitivity reset)

SUPPLEMENTS (Longevity):
- Resveratrol: 500mg daily (sirtuin activation)
- Spermidine: 1-2mg daily (autophagy)
- Quercetin: 500mg daily (senolytic, inflammation)
- CoQ10 (Ubiquinol): 200mg daily (mitochondrial function)

EXERCISE MASTERY:
- Zone 2: 4-5x/week, 60 min (cardiovascular fitness)
- Strength: 3-4x/week (build lean mass)
- HIIT: 1-2x/week (metabolic flexibility)
- Mobility: Daily (injury prevention, longevity)

FINAL ASSESSMENT:
- Comprehensive blood work (all biomarkers)
- DEXA scan (compare to baseline)
- VO2 max test (cardiovascular fitness)
- Metabolic flexibility test (fat oxidation vs. glucose)
- Client satisfaction survey

EXPECTED OUTCOMES (90 days):
- Fasting glucose: 70-85 mg/dL ✅
- HbA1c: <5.3% ✅
- HOMA-IR: <1.5 ✅
- Triglycerides: <100 mg/dL ✅
- Testosterone: >600 ng/dL ✅
- Weight loss: 15-25 lbs (mostly fat) ✅
- Lean mass: Maintained or increased ✅
- Sleep: 7.5-8 hours consistently ✅
- Energy: Sustained, no crashes ✅
- Mood: Improved, reduced anxiety ✅

MAINTENANCE PLAN:
- Continue foundational supplements
- Maintain exercise routine (4-5x/week)
- Flexible nutrition (80/20 rule)
- Quarterly blood work
- Annual DEXA scan
- Monthly check-ins with practitioner
```

### 📊 Biomarker Analysis Report
```
BIOMARKER OPTIMIZATION REPORT
Client: John Smith | Date: Feb 13, 2026

METABOLIC HEALTH:
❌ Fasting Glucose: 105 mg/dL (Optimal: 70-85)
   → 20 mg/dL above optimal
   → Interventions: Time-restricted eating, berberine, zone 2 cardio

❌ HbA1c: 5.9% (Optimal: <5.3%)
   → Pre-diabetic range
   → Target: <5.3% in 90 days

❌ HOMA-IR: 3.5 (Optimal: <1.5)
   → Insulin resistant (2.3x optimal)
   → Interventions: Low-carb, resistance training, alpha-lipoic acid

❌ Triglycerides: 180 mg/dL (Optimal: <70)
   → 2.6x above optimal
   → Interventions: Omega-3, reduce carbs, fasting

⚠️ HDL-C: 55 mg/dL (Optimal: >60)
   → Borderline low
   → Interventions: Exercise, omega-3, niacin (if needed)

HORMONES:
❌ Testosterone: 350 ng/dL (Optimal for age: 500-800)
   → Low for 45-year-old male
   → Interventions: Tongkat ali, zinc, magnesium, sleep, stress reduction
   → Consider TRT if no improvement after 90 days

⚠️ Vitamin D: 45 ng/mL (Optimal: 50-80)
   → Adequate but not optimal
   → Intervention: Increase D3 to 5,000 IU daily

INFLAMMATION:
❌ hsCRP: 3.2 mg/L (Optimal: <1.0)
   → Elevated (cardiovascular risk)
   → Interventions: Omega-3, curcumin, reduce body fat

PRIORITY RANKING:
1. HOMA-IR (insulin resistance) - CRITICAL
2. Fasting glucose (pre-diabetes) - HIGH
3. Testosterone (hormonal health) - HIGH
4. Triglycerides (cardiovascular risk) - HIGH
5. hsCRP (inflammation) - MEDIUM

ESTIMATED IMPROVEMENT TIMELINE:
- 30 days: Glucose -10-15 mg/dL, improved sleep
- 60 days: HOMA-IR <2.5, testosterone >450
- 90 days: All biomarkers in optimal range

REPEAT TESTING:
- 30 days: Fasting glucose, weight, body composition
- 90 days: Comprehensive panel (all markers)
```

---

## Advanced Features

### 🔬 Research Integration
- **Latest studies:** Auto-update protocols with new longevity research
- **Evidence hierarchy:** Prioritize RCTs, meta-analyses, mechanistic studies
- **Citation library:** Reference papers for each intervention
- **Mechanism explanations:** How/why each intervention works

### 📲 Client Portal Content
- **Educational videos:** Protocol explanations, supplement guides
- **Habit tracking:** Daily check-ins, supplement adherence
- **Progress dashboards:** Biomarker trends, before/after photos
- **Community forum:** Client Q&A, success stories

### 🤖 Automation
- **Onboarding sequences:** Welcome emails, intake forms, initial consultations
- **Check-in reminders:** Weekly progress updates, compliance tracking
- **Lab result interpretation:** Automated analysis when labs are uploaded
- **Protocol adjustments:** Dynamic optimization based on results

### 💰 Business Tools
- **Client CRM:** Track clients, protocols, progress, revenue
- **Scheduling:** Consultation booking, follow-ups
- **Invoicing:** Automated billing for services
- **Analytics:** Client outcomes, retention, LTV

---

## Pricing & ROI

### 💰 What This Agent Replaces
- **Protocol creation time:** 2-4 hours per client → 15 minutes
- **Follow-up assessments:** 1 hour per client → 10 minutes
- **Educational content creation:** $500-2,000 → Automated
- **Client onboarding:** Manual → Fully automated

**Time saved:** 10-15 hours per client  
**Cost:** $97 one-time vs. $1,000s in labor

### 📈 Revenue Potential
**Scenario: Longevity Coaching Practice**
- Clients: 20 active
- Avg. package: $3,000 (90-day protocol + coaching)
- Time saved per client: 12 hours
- Capacity increase: +10 clients/month (automation)

**Revenue impact:**
- Current: $60K/month (20 clients @ $3K)
- With automation: $90K/month (30 clients @ $3K)
- **Net gain: +$30K/month**

---

## Support & Updates

- **Documentation:** Full video walkthrough included
- **Updates:** Free protocol updates as research evolves
- **Support:** Email support@openclaw-templates.com
- **Community:** Join Discord for practitioner collaboration

---

## FAQ

**Q: Is this evidence-based or just biohacking hype?**  
A: Evidence-based. All protocols reference peer-reviewed research. We prioritize RCTs and meta-analyses.

**Q: Can I customize protocols for my clients?**  
A: 100%. Edit `config.json` and `protocol_templates.json` to match your practice style.

**Q: Does this replace medical advice?**  
A: No. This is for health coaches and wellness practitioners. Always defer to licensed physicians for medical conditions.

**Q: What if a client doesn't improve?**  
A: Protocol includes dynamic adjustments based on results. If no improvement, escalate to specialist or adjust interventions.

**Q: Can I use this for myself (personal optimization)?**  
A: Absolutely. Many biohackers use this for self-experimentation.

**Q: How often do protocols need updating?**  
A: We update templates quarterly as new longevity research emerges.

**Q: Does this work for all ages?**  
A: Protocols are customizable by age, sex, health status. Templates included for 25-35, 35-50, 50+.

---

## Next Steps

1. **Install the template** (5 minutes)
2. **Configure your practice** (10 minutes)
3. **Generate your first protocol** (15 minutes)
4. **Onboard a client** (automated)
5. **Track results** 📈

**Ready to 10x your client capacity?**

[Get the Longevity Protocol Generator →](#)

---

## License & Usage

- ✅ Use for your own practice (unlimited clients)
- ✅ Generate protocols for paying clients
- ✅ Customize templates for your methods
- ❌ Do not resell this template as-is
- ❌ Do not share your OpenClaw API keys

---

**Built by:** Hunter (OpenClaw Templates)  
**Version:** 1.0.0  
**Last Updated:** February 2026  
**Support:** [Discord](https://discord.gg/openclaw) | [Email](mailto:support@openclaw-templates.com)

**Synergy:** Integrates perfectly with **Lux Life Rx** for scalable longevity clinic operations.
