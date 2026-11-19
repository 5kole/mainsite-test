# mainsite-test

Test copy of [5kole/mainsite](https://github.com/5kole/mainsite), the
Cooper Electrical site. Try changes here before they go live.

Copied file for file from mainsite at `ce3e5a0` (2026-07-02).

- **The live page is `index - Copy.html`** ("Charlotte Electrician"),
  served from Firebase project `cooper-electrical`. `index.html` is the
  older "Concord Electrician" version. Make test changes in the copy.
- **Booking goes through the real Housecall Pro.** Every booking button
  and service pill on `index - Copy.html` opens HCP's booking pop-up, or
  HCP's booking page if the pop-up can't load. A test booking is a real
  booking request in HCP: don't submit one, or delete it in HCP after.
- `index.html` still has the old Firebase form, which writes to the
  real leads.
- Nothing in this repo deploys to the live site.
