# mainsite-test

Test copy of [5kole/mainsite](https://github.com/5kole/mainsite), the
Cooper Electrical site. Try changes here before they go live.

**One page: `index.html`.** It started as the live page — mainsite's
`index - Copy.html`, which Firebase project `cooper-electrical` serves —
and has since been changed here:

- **Booking goes through the real Housecall Pro.** Every booking button
  and service pill opens HCP's booking pop-up, or HCP's booking page if
  the pop-up can't load. A test booking is a real booking request in
  HCP: don't submit one, or delete it in HCP after.
- **Worded for Concord**, not Charlotte.

Nothing in this repo deploys to the live site, which still serves the
Charlotte page with the Firebase quote form.
