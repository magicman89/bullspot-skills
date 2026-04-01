---
name: bullspot-email-marketer
description: Email marketing workflow for Bullspot - creating email sequences, newsletters, campaign copy using Resend API.
category: email
bullspot_agent: Penny
---

# Bullspot Email Marketer Skill

## When to Use
- Creating email campaigns and sequences
- Writing newsletter content
- Building automated email flows
- Writing promotional emails

## Bullspot Core Selling Points
1. Fully Autonomous Agentic AI Trading 24/7
2. Serious Risk Management - Multiple bilevel stops + risk/reward
3. Self-Improving - Auto-learns from mistakes over time

## Tools
- Resend API: Use RESEND_API_KEY environment variable (do NOT hardcode)
- Supabase: vwizzzmcescljw

## Sending Emails via Resend API
```bash
curl -X POST "https://api.resend.com/emails" \
  -H "Authorization: Bearer $RESEND_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "from": "Bullspot <support@bullspot.app>",
    "to": ["recipient@example.com"],
    "subject": "Subject line",
    "html": "<p>Email body</p>"
  }'
```

## Email List Segmentation
| Segment | Content Focus |
|---------|---------------|
| Free users | Value demonstration, upgrade benefits |
| Paid subscribers | Retention, cross-sell |
| Churned users | Win-back offers |

## Email Sequences

### Welcome Sequence (5 emails)
1. Day 1: Welcome - here's what to do first
2. Day 3: Meet your dashboard
3. Day 5: How elite traders use Bullspot
4. Day 7: Your first signal - what to look for
5. Day 10: Upgrade to unlock full capabilities (NO free trial)

### Weekly Newsletter
- Subject: Under 50 chars, curiosity or benefit-driven
- Body: Short paragraphs, scannable, one CTA
- Length: Under 200 words promotional, under 500 newsletter

## Metrics to Track
- Open rate: 25%+
- Click-through rate: 5%+
- Conversion rate: 3%+

## Compliance
- Include unsubscribe link
- Physical address in footer
