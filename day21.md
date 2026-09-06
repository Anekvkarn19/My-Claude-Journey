# Day 21 — Digital Privacy Dashboard

## Objective

Today's task focused on using Claude to generate and explore an interactive Digital Privacy Dashboard from a sample digital-footprint dataset.

## Dashboard Overview

The dashboard analyzes a reported set of digital services and presents estimated exposure, privacy, risk, and data-value insights.

The report clearly distinguishes between:
- **Facts** — information based on the reported app/service list.
- **Estimates** — modeled scores, risk levels, personas, and behavioral conclusions based on typical published data practices.

No private accounts or private databases were accessed.

## Digital Footprint Scores

| Metric | Result |
|---|---|
| Digital Footprint Score | 78/100 — Significant |
| Privacy Score | 41/100 — Fair |
| Ecosystem Concentration | 27% — Moderate, Google |
| Estimated Tracking Surface | High — Cross-app profiling likely |
| Total Services | 15 |
| Distinct Parent Companies | 11 |
| Services under Google | 4 |
| Broad Data Categories Touched | 6 (Estimate) |

## Exposure Heatmap

The dashboard categorized the reported services by estimated exposure level.

### High Exposure
- Instagram
- Snapchat
- TikTok
- YouTube
- Amazon
- Google Search
- Google Pay

### Medium Exposure
- WhatsApp
- Discord
- Spotify
- Roblox
- PUBG Mobile
- Meesho
- Google Photos

### Low Exposure
- iMessage

## Company Exposure Ranking

The dashboard calculated company exposure based on the number of reported services associated with each company.

Google had the largest single share of the reported footprint at approximately **27%**, with four services:
- Google Search
- Google Pay
- Google Photos
- YouTube

## Risk Radar

The dashboard displayed five estimated risk dimensions:

| Risk Area | Score |
|---|---:|
| Identity Exposure | 80/100 |
| Financial Data Risk | 55/100 |
| Social Graph Exposure | 85/100 |
| Location Tracking | 65/100 |
| Behavioral Profiling | 75/100 |

## Digital Twin Profile

The dashboard generated an estimated digital profile from the reported services.

### Likely Lifestyle Signals
- Heavy short-form video and social consumption
- Mobile-first shopping behavior
- Active mobile gaming usage
- India-based mobile payments usage

### Ecosystem Footprint
- Footprint distributed across Google, Meta, and standalone apps
- Communication spread across WhatsApp, iMessage, and Discord
- Cross-device usage was modeled as likely

These are explicitly presented by the dashboard as **estimates**, not verified facts.

## Most Valuable Data Assets

The dashboard ranked the following data categories:

1. **Social Graph & Contacts**
2. **Purchase & Payment Behavior**
3. **Watch/Search History**
4. **Location Patterns**
5. **Media & Biometrics**

## Privacy Improvement Simulator

The interactive simulator allowed privacy actions to be toggled and showed their projected effect on the footprint and privacy scores.

Available actions included:

- Turn off ad personalization on Google
- Limit Meta ad tracking
- Review Snapchat and TikTok data permissions
- Disable Discord activity status and data sharing
- Audit Amazon and Meesho saved payment data

The simulator starts from:
- Footprint score: **78**
- Privacy score: **41**

and updates the projected scores when actions are selected.

## Final Verdict

The dashboard's final assessment was:

**“Significant footprint, fair privacy — concentrated but manageable.”**

The report identified Google as having the largest estimated share of the reported footprint and highlighted social/entertainment services as major contributors to exposure.

## Key Learnings

1. A structured dataset can be transformed into an interactive privacy-analysis dashboard using Claude.
2. Separating **facts from estimates** is important when analyzing digital privacy.
3. Visual elements such as heatmaps, rankings, radar charts, and score cards make complex privacy information easier to understand.
4. An interactive simulator can demonstrate how privacy settings and permission changes may affect modeled exposure.
5. The dashboard emphasized that modeled privacy insights should not be treated as verified information from private accounts.

## Evidence

Screenshots were captured for the dashboard, including:
- Score Overview
- Exposure Heatmap and Company Exposure Ranking
- Risk Radar, Digital Twin, and Most Valuable Data Assets
- Privacy Improvement Simulator and Final Verdict

## Conclusion

Day 21 demonstrated how Claude can turn a digital-footprint dataset into a visually structured and interactive privacy dashboard.

The generated dashboard combined numerical scores, visual analysis, risk dimensions, data-asset rankings, and an interactive privacy-improvement simulator into one browser-based experience.

### Day 21 Status: Completed ✅
