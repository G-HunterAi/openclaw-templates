# E-commerce Product Researcher

**Find winning products in minutes, not weeks. Automate product research for dropshipping, Amazon FBA, and e-commerce stores.**

## What This Does

Automate product research and validation for e-commerce sellers. This OpenClaw agent:

- **Product Discovery:** Scan trending products across marketplaces (Amazon, AliExpress, TikTok Shop, Etsy)
- **Competitor Analysis:** Analyze top sellers, pricing strategies, review patterns
- **Niche Validation:** Score product ideas by demand, competition, profitability
- **Supplier Research:** Find reliable suppliers with best pricing and shipping
- **Trend Monitoring:** Track emerging trends before they saturate
- **Import List Generation:** Export ready-to-import product lists for Shopify/WooCommerce

---

## Who This Is For

✅ **Dropshippers** who waste weeks finding winning products  
✅ **Amazon FBA sellers** who need validated product ideas  
✅ **Shopify store owners** who want to expand their catalog  
✅ **Print-on-demand sellers** who need trending designs  
✅ **E-commerce agencies** who manage multiple stores  

---

## What You Get

### 🔍 Product Discovery
- **Trending product scanner:** Real-time trending items across platforms
- **Niche explorer:** Identify underserved niches with high demand
- **Seasonal opportunities:** Products trending for upcoming seasons/holidays
- **TikTok virality tracker:** Products going viral on social media
- **AliExpress best-sellers:** Top-selling items with good margins

### 📊 Product Validation
- **Opportunity score:** 0-100 rating based on 15+ factors
- **Competition analysis:** Number of sellers, saturation level
- **Profit calculator:** Estimated margins after all fees
- **Demand assessment:** Search volume, trend trajectory
- **Red flag detection:** Copyright issues, oversaturation, quality concerns

### 💰 Profitability Analysis
- **Cost breakdown:** Product cost + shipping + fees + ads
- **Margin calculator:** Expected profit per sale
- **Break-even analysis:** Sales needed to profit
- **ROI projections:** Conservative/realistic/optimistic scenarios
- **Pricing recommendations:** Optimal price points for conversions

### 🏭 Supplier Research
- **Supplier comparison:** 5-10 suppliers per product ranked by quality/price/shipping
- **MOQ analysis:** Minimum order quantities and bulk pricing
- **Shipping time estimates:** Delivery times by method
- **Supplier reliability:** Reviews, ratings, response times
- **Negotiation templates:** Email templates to negotiate better pricing

### 🎯 Competitor Intelligence
- **Top seller analysis:** Who's dominating the niche and why
- **Pricing strategies:** How competitors price their products
- **Marketing tactics:** Ad copy, images, bundles they use
- **Review analysis:** What customers love/hate about competitor products
- **Differentiation opportunities:** How to stand out from competition

### 📈 Market Research Reports
- **Niche reports:** Deep-dive analysis of specific niches
- **Trend forecasts:** What's gaining/losing momentum
- **Seasonal calendars:** Best times to launch products
- **Import lists:** CSV exports ready for Shopify/WooCommerce
- **Action plans:** Step-by-step launch strategies

---

## Quick Start (5 Minutes)

### 1. Install in OpenClaw

```bash
# Install from ClawHub
openclaw skills install ecommerce-product-researcher

# Or download this template manually
git clone https://github.com/G-HunterAi/openclaw-templates.git
cd openclaw-templates/templates/ecommerce-product-researcher
```

### 2. Configure Your Research Criteria

Edit `config.json`:

```json
{
  "business_model": "dropshipping",
  "target_marketplaces": ["amazon", "shopify", "etsy"],
  "budget": {
    "max_product_cost": 25,
    "min_profit_margin": 30,
    "monthly_ad_budget": 500
  },
  "preferences": {
    "avoid_niches": ["health_supplements", "electronics"],
    "target_customer": "Women 25-45",
    "shipping_regions": ["USA", "Canada", "UK"]
  }
}
```

### 3. Start Researching

**Option A: Find Trending Products (Recommended)**
```
Hey OpenClaw, find me 10 trending products for dropshipping. Budget: $15-25 product cost, 40%+ margin, low competition.
```

**Option B: Validate a Product Idea**
```
Research this product: [product name/link]. Give me full analysis: competition, profitability, suppliers, and launch strategy.
```

**Option C: Explore a Niche**
```
Analyze the [niche name] niche for Shopify. Find top 5 product opportunities with supplier recommendations.
```

---

## Configuration Files

### `config.json` - Your Research Settings
```json
{
  "business_info": {
    "business_model": "dropshipping",
    "store_platform": "shopify",
    "experience_level": "beginner",
    "monthly_budget": 1000
  },
  "product_criteria": {
    "price_range": {"min": 10, "max": 50},
    "min_profit_margin": 30,
    "max_competition_score": 60,
    "min_demand_score": 50,
    "shipping_time_max": 21
  },
  "target_marketplaces": {
    "primary": ["amazon", "aliexpress"],
    "secondary": ["tiktok_shop", "etsy", "walmart"]
  },
  "filters": {
    "avoid_categories": ["Health", "Electronics"],
    "prefer_categories": ["Home & Garden", "Pet Supplies", "Fashion"],
    "avoid_materials": ["fragile", "liquid", "oversized"],
    "preferred_suppliers": ["Gold Medal", "Top Brand"]
  }
}
```

### `research_templates.json` - Analysis Frameworks
Pre-built research templates:
- Trending product scanner
- Niche opportunity analyzer
- Competitor intelligence report
- Supplier comparison matrix
- Profitability calculator

### `scoring_criteria.json` - Product Scoring
15-factor scoring algorithm:
- Demand (search volume, trends)
- Competition (number of sellers, saturation)
- Profitability (margins, pricing power)
- Differentiation (uniqueness, positioning)
- Supplier quality (reliability, pricing)

---

## Example Outputs

### 🔍 Product Discovery Report
```
TRENDING PRODUCT ALERT: LED Galaxy Projector

OPPORTUNITY SCORE: 87/100 (EXCELLENT)

📊 MARKET ANALYSIS:
- Monthly searches: 45,000+ (growing 15% monthly)
- Competition level: Medium (saturation: 45%)
- Trend status: Rising (TikTok viral: 2.3M views)
- Seasonality: Year-round demand

💰 PROFITABILITY:
- Supplier cost: $12.50 (AliExpress)
- Shipping: $5.00 (ePacket 14-21 days)
- Total cost: $17.50
- Recommended retail: $49.99
- Profit per sale: $32.49 (65% margin)
- Break-even: 16 sales (covers ads)

🏆 TOP COMPETITORS:
1. StarrySky Store ($39.99, 1,200 reviews, 4.5★)
2. GalaxyLights Co ($44.99, 850 reviews, 4.3★)
3. NightSky Official ($49.99, 2,100 reviews, 4.7★)

🎯 DIFFERENTIATION OPPORTUNITIES:
→ Bundle with bluetooth speaker (+$15 perceived value)
→ Target kids' rooms (parents willing to pay more)
→ Offer custom colors (premium positioning)
→ Create TikTok content (viral potential)

🏭 RECOMMENDED SUPPLIERS:
1. ⭐⭐⭐⭐⭐ Shenzhen LED Co (4.9★, 5K orders, $12.50)
2. ⭐⭐⭐⭐ Galaxy Tech Ltd (4.7★, 3K orders, $13.20)
3. ⭐⭐⭐⭐ LED World Factory (4.6★, 2K orders, $11.80)

✅ RED FLAGS: None detected
⚠️ WATCH OUT FOR: Copyright issues with some designs

🚀 LAUNCH STRATEGY:
Week 1: Order 10 samples ($125), test shipping times
Week 2: Create product page, 5 TikTok videos
Week 3: Launch with $300 FB ads, $200 TikTok ads
Week 4: Scale winners, test bundles

ESTIMATED RESULTS (90 days):
- Conservative: 50 sales, $1,624 profit
- Realistic: 120 sales, $3,899 profit
- Aggressive: 250 sales, $8,123 profit
```

### 📊 Niche Analysis Report
```
NICHE REPORT: Pet Products - Dog Anxiety Solutions

NICHE SCORE: 82/100 (HIGH OPPORTUNITY)

📈 DEMAND METRICS:
- Total monthly searches: 125,000+
- Trend: Growing 25% year-over-year
- Peak season: July-December (fireworks, holidays)
- Customer LTV: High (repeat purchases)

🎯 TARGET CUSTOMER:
- Demographics: Dog owners 30-55, income $50K+
- Pain point: Anxious dogs (thunderstorms, separation)
- Willingness to pay: High (pet parents prioritize pet health)
- Purchase triggers: Vet recommendation, viral content

💡 TOP 5 PRODUCT OPPORTUNITIES:

1. Calming Dog Bed (Opportunity Score: 89)
   - Cost: $18, Retail: $69.99, Margin: 74%
   - Competition: Medium, Differentiation: Easy
   
2. Anxiety Vest/Wrap (Opportunity Score: 85)
   - Cost: $8, Retail: $34.99, Margin: 77%
   - Competition: High, Differentiation: Moderate
   
3. Calming Treats (Opportunity Score: 78)
   - Cost: $6, Retail: $24.99, Margin: 76%
   - Competition: Very High, Differentiation: Hard
   
4. White Noise Machine for Dogs (Opportunity Score: 91)
   - Cost: $12, Retail: $49.99, Margin: 76%
   - Competition: Low, Differentiation: Very Easy
   
5. Pheromone Diffuser (Opportunity Score: 73)
   - Cost: $7, Retail: $29.99, Margin: 77%
   - Competition: Very High, Differentiation: Hard

🏆 RECOMMENDED ENTRY PRODUCT: White Noise Machine
→ Lowest competition, highest differentiation potential
→ Unique positioning (not saturated yet)
→ Easy to create educational content around
→ Great upsell potential (bundles)

[Full competitive analysis, supplier list, launch plan included...]
```

### 🏭 Supplier Comparison
```
PRODUCT: Wireless Phone Charger (Fast Charging 15W)

SUPPLIER COMPARISON (Top 5):

1. ⭐⭐⭐⭐⭐ TechPro Manufacturing (RECOMMENDED)
   - Price: $6.50 (500+ units: $5.80)
   - MOQ: 50 units
   - Rating: 4.9★ (2,341 reviews)
   - Response time: <2 hours
   - Shipping: 12-16 days (ePacket)
   - Quality: Premium (samples confirmed)
   - Custom branding: Yes ($0.30/unit)
   - Payment: PayPal, Alibaba Trade Assurance
   - Why choose: Best quality-to-price ratio, reliable

2. ⭐⭐⭐⭐ ElectroWave Factory
   - Price: $5.20 (1000+ units: $4.50)
   - MOQ: 100 units
   - Rating: 4.6★ (1,892 reviews)
   - Response time: 4-6 hours
   - Shipping: 15-20 days
   - Quality: Good (slight defect rate)
   - Custom branding: Yes ($0.25/unit)
   - Why choose: Lowest cost for volume orders

3. ⭐⭐⭐⭐ ChargePlus Co
   - Price: $7.20 (200+ units: $6.80)
   - MOQ: 20 units
   - Rating: 4.8★ (987 reviews)
   - Response time: <4 hours
   - Shipping: 10-14 days (DHL option)
   - Quality: Premium
   - Custom branding: Yes (free over 200 units)
   - Why choose: Fastest shipping, low MOQ

[2 more suppliers + negotiation templates included...]
```

---

## Advanced Features

### 🤖 Automated Monitoring
- **Daily trending reports:** New opportunities delivered every morning
- **Price change alerts:** Notify when supplier prices drop
- **Competition tracking:** Monitor when new sellers enter your niche
- **Trend warnings:** Alert when demand is declining

### 📈 Analytics Dashboard
- **Portfolio performance:** Track all your products in one place
- **Profit tracking:** Actual vs. projected margins
- **Supplier ratings:** Track which suppliers perform best
- **Niche saturation:** Watch competition levels over time

### 🚀 Launch Automation
- **Import list generation:** CSV exports ready for Shopify/WooCommerce
- **Product page templates:** Pre-written descriptions and bullet points
- **Ad copy generation:** Facebook/TikTok ad copy and headlines
- **Email sequences:** Launch campaigns for new products

### 🎯 Custom Research
- **Reverse engineer competitors:** Analyze successful stores
- **Seasonal research:** Find products for upcoming holidays
- **Trend forecasting:** Predict next viral products
- **White label opportunities:** Find products you can brand

---

## Research Methodology

### Product Scoring Algorithm (0-100)

**Demand (30 points):**
- Search volume trend
- Social media mentions
- Competitor sales estimates

**Competition (25 points):**
- Number of sellers
- Market saturation
- Barrier to entry

**Profitability (25 points):**
- Margin percentage
- Price elasticity
- Upsell potential

**Differentiation (10 points):**
- Unique selling points
- Branding opportunities
- Positioning gaps

**Risk Assessment (10 points):**
- Copyright issues
- Supplier reliability
- Shipping complexity

### Data Sources
- Amazon Best Sellers, Movers & Shakers
- AliExpress Trending, Weekly Deals
- TikTok Shop, Instagram Shopping
- Google Trends, Google Shopping
- Reddit product discussions
- Niche subreddit mentions

---

## Pricing & ROI

### 💰 What This Agent Replaces
- **Product research tool subscriptions:** $50-200/month
- **VA doing manual research:** $500-1,500/month
- **Trial and error failures:** $1,000-5,000 in wasted inventory
- **Your time:** 20-40 hours/month

**Total value:** $1,570-6,700/month  
**OpenClaw template cost:** $97 one-time

### 📈 Expected Results
- **Time saved:** 20-40 hours/month on research
- **Better product selection:** 3-5x higher win rate
- **Faster validation:** Days instead of weeks
- **Reduced risk:** Avoid saturated/unprofitable products

### 💸 Real ROI Example
**Before this agent:**
- Research time: 30 hours/month
- Products tested: 5/month
- Winners: 1 (20% success rate)
- Profit per winner: $2,000/month
- Total profit: $2,000/month

**After this agent:**
- Research time: 5 hours/month
- Products tested: 15/month
- Winners: 9 (60% success rate)
- Profit per winner: $2,000/month
- Total profit: $18,000/month

**Net gain:** $16,000/month from better product selection + 25 hours saved

---

## Support & Updates

- **Documentation:** Full video walkthrough included
- **Updates:** Free updates for life
- **Support:** Email support@openclaw-templates.com
- **Community:** Join Discord for product ideas & tips

---

## FAQ

**Q: Do I need coding experience?**  
A: No. Just tell OpenClaw what you're looking for in plain English.

**Q: What marketplaces does this work with?**  
A: Amazon, AliExpress, Shopify, Etsy, TikTok Shop, Walmart, eBay.

**Q: Can it find suppliers automatically?**  
A: Yes. It finds 5-10 suppliers per product, ranks them, and provides contact info.

**Q: Does it work for Amazon FBA?**  
A: Absolutely. Includes FBA fee calculations and profitability analysis.

**Q: How often should I research new products?**  
A: Weekly for trending products, monthly for niche deep-dives.

**Q: Can it track my competitors?**  
A: Yes. Monitor competitor pricing, inventory, reviews, and marketing tactics.

**Q: Does it work for print-on-demand?**  
A: Yes! Great for finding trending designs and niches for POD.

---

## Next Steps

1. **Install the template** (5 minutes)
2. **Configure your criteria** (10 minutes)
3. **Run your first product research** (5 minutes)
4. **Order samples from recommended suppliers** (1-2 weeks)
5. **Launch your winning product** 🚀

**Ready to stop guessing and start winning?**

[Get the E-commerce Product Researcher →](#)

---

## License & Usage

- ✅ Use for your own e-commerce business (unlimited)
- ✅ Research products for your clients (agencies)
- ✅ Generate reports to sell (if you add value)
- ❌ Do not resell this template as-is
- ❌ Do not share your OpenClaw API keys

---

**Built by:** Hunter (OpenClaw Templates)  
**Version:** 1.0.0  
**Last Updated:** February 2026  
**Support:** [Discord](https://discord.gg/openclaw) | [Email](mailto:support@openclaw-templates.com)
