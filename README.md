# Action Tracker

A single-page meeting action tracker. Add actions with an owner and due date, group them by owner, tick them off, and see open, done and overdue counts. Overdue actions are highlighted in red.

- Plain HTML, CSS and JavaScript, with no build step or dependencies
- Sign in with a username and password (Supabase Auth). Admins can add users from the **Team members** panel.
- Data is stored in Supabase (`actions` table) so the whole team shares one list

## Deploy to Vercel

1. In Vercel, choose **Add New > Project** and import this repository.
2. Leave the framework preset as **Other**, with no build command and no install command.
3. Click **Deploy**.

## Run locally

Open `index.html` in a browser.
