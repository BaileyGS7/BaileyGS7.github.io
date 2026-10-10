# Trend Shorts Bot website

Public pages for Trend Shorts Bot, served at https://baileygs7.github.io/. They serve both the TikTok
developer app and the Google Cloud (YouTube API) client of the same personal tool: the TikTok developer
portal, Google's OAuth consent screen and the YouTube API audit form all link to them.

- `index.html`: what the app does, the TikTok and YouTube permissions it uses, and the contact address
- `privacy.html`: the Privacy Policy (TikTok and YouTube data, the `youtube.upload` and
  `yt-analytics.readonly` scopes, what is stored where and for how long, revocation and deletion)
- `terms.html`: the Terms of Service (TikTok's and YouTube's rules, YouTube uploads, account access)
- `callback.html`: the OAuth redirect URI for both TikTok and Google. It shows the one-time code that comes
  back after the owner approves the app, so it can be pasted into the "Connect TikTok" or "Connect YouTube"
  workflow of the bot's repository.
- `tiktok*.txt`: TikTok's URL prefix verification file

The pages load only their own files (no cookies, analytics, ads or outside scripts). Contact:
jonj65854@gmail.com.
