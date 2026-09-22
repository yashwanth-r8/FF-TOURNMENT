# FF Tournament Arena

A Free Fire group-stage and playoff tournament website.

## Features
- Group-stage fixtures divided into Leg 1 and Leg 3
- Editable match kills, rounds won, penalties, and winner selection
- Automatic points table with tie-breaks:
  1. Points
  2. Net points
  3. Rounds won
  4. Fewer rounds lost
- Top 3 group-stage qualifiers, revealed only after all group matches are completed
- Playoff bracket: Qualifier 1, Qualifier 2, and Final
- Champion display with the winner's team logo and celebration styling
- Viewers can browse the site; admin mode provides editing controls

## GitHub Pages deployment
1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

## Important limitations
This is a static browser prototype. Tournament data is stored in the current browser's `localStorage`; it is not synchronized between different viewers or devices. The demo admin ID and password are embedded in the front-end and are not secure. Do not use this version for sensitive information or treat it as secure authentication. For a real public tournament site, connect a backend/database and implement server-side admin authentication.
\n## Demo admin credentials\n- Admin ID: `yash0703`\n- Password: `3550`\n\nThese credentials are embedded in the static front-end and are not secure for production.\n