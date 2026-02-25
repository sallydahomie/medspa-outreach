# MedSpa Lead Pipeline CRM + Follow-Up Sequence Generator

Built by Jarvis — Nightly Build, Feb 24, 2026.

## What's Inside

### 1. `index.html` — Lead Pipeline Dashboard
A full CRM dashboard for tracking your 29 med spa leads through the sales pipeline.

**Features:**
- 📊 Real-time stats: total leads, pipeline count, DMs sent, replies, meetings, close rate
- 🔍 Search + filter by status and priority
- ⚡ Quick-advance status with one click (New → DM Sent → Follow-Up → Replied → Meeting → Closed)
- 📅 Follow-up tracker with overdue/today/upcoming views
- 📝 Per-lead timeline tracking (every touchpoint logged)
- 💾 Auto-saves to localStorage (works offline)
- 📤 Export/Import JSON (backup your data)
- 📋 One-click follow-up report generator (copies to clipboard)
- 🎯 Pre-loaded with all 29 leads from your research, 14 already marked as "DM Sent"

### 2. `followup-sequences.html` — Follow-Up Message Generator
Generates personalized 5-touch, 21-day follow-up sequences for each lead.

**Features:**
- 🎯 7 weakness categories (copy, CTAs, social, proof, before/after, pricing, booking)
- 📝 Day 0, 3, 7, 14, 21 touchpoints with channel recommendations
- 💡 Timing tips and strategic notes for each message
- 📋 One-click copy per message or entire sequence
- 🧠 Personalized with business name, city, follower count, and specific details

## Why This Matters

You sent 10 DMs today (Day 1). By Day 3, you'll need to follow up. By end of week, you'll have 70+ touchpoints to track across 29 leads. Without a system, leads fall through the cracks.

This gives you:
- **Zero leads forgotten** — every follow-up date is tracked
- **Consistent messaging** — sequences are pre-written, just copy-paste
- **Pipeline visibility** — know exactly where every lead stands
- **Time savings** — ~30 min/day on follow-ups instead of 2 hours

## Quick Start

```bash
# Just open in a browser — zero dependencies
open index.html
# Or serve locally
npx serve .
```

All data lives in localStorage. Export regularly as backup.

## PR Description

This is Day 1 infrastructure for the 90-day med spa push. Trevor needs to track 29 leads across a multi-touch outreach sequence while sending 10+ DMs per day. Without a CRM, he'll lose track by Day 5. This gives him pipeline visibility, automated follow-up scheduling, and pre-written sequence templates — all in two zero-dependency HTML files that work offline.
