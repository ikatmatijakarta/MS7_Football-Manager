# MS7 Football Manager RC8.2

RC8.2 fixes the Admin **Full Season Control** so the controls are no longer dead/locked by frontend state.

Install order:
1. Run `MS7_SEASON_CALENDAR_CONTROL_V1_3.sql` in Supabase.
2. Deploy `index.html`, `manifest.webmanifest`, and `sw.js` to GitHub Pages.
3. Hard refresh and test Generate / Activate / Pause / Resume.

See `RC8_2_CHANGELOG_ID.md` and `RC8_2_DEPLOY_TEST_ID.md`.
