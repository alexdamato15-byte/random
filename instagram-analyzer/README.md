# Instagram Follower Analyzer

A privacy-first tool to find Instagram accounts you follow that don't follow you back.

**Your data never leaves your device** — everything runs in the browser.

## Usage

1. Open `index.html` in your browser (no server needed).
2. Export your Instagram data:
   - Instagram → Settings → Your activity → Download your information
   - Choose **JSON format** and select only **Followers and Following**
3. Unzip the download and locate these files inside `connections/followers_and_following/`:
   - `followers_1.json`
   - `following.json`
4. Upload both files in the tool.
5. Click **Analyze** and see who isn't following you back, with direct links to unfollow them.

## Features

- Sort by oldest followed / newest followed / A-Z
- Search by username
- Copy the full list of non-followers to clipboard
- Direct links to each profile on Instagram
- Paginated for large lists
