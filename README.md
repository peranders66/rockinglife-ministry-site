# Rocking Life Ministry Website

Multi-page site for rockinglife.org — Google Ad Grants compliant.

## Structure

```
/index.html              -> Homepage
/about/index.html        -> About, mission, founder story, invite-only
/forge-groups/index.html -> FORGE groups detail + discipleship journey
/give/index.html         -> Donation page (Give Lively integration)
/contact/index.html      -> Contact form
/privacy/index.html      -> Privacy policy (required for Google Ad Grants)
/invite/index.html       -> Ambassador invite landing page (personalized)
/css/style.css           -> Shared stylesheet
/js/main.js              -> Shared JavaScript (embers, scroll animations)
```

## Google Ad Grants Checklist

- [x] Multi-page site with distinct crawlable URLs
- [x] Clear nonprofit status on every page (footer EIN)
- [x] Original content throughout
- [x] No commercial activity, ads, or affiliate links
- [x] Mobile responsive
- [x] Privacy policy page
- [x] Contact page
- [x] Add your actual EIN (99-2499686)
- [ ] Add Give Lively URL (replace # in donate button)
- [ ] Install Google Analytics 4 tracking code
- [ ] Set up at least one GA4 conversion event
- [ ] Verify SSL after DNS switch (https://)
- [ ] Test PageSpeed Insights score (target: 50+)

## Deployment

Hosted on Vercel. Auto-deploys on push to main branch.

## Ambassador Invite URL Format

```
https://rockinglife.org/invite?utm_source={circlePublicUid}&invitation_from={ambassadorName}
```
