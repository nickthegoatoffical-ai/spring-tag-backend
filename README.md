# Spring Tag Backend (Vercel + Flask)

Environment variables (Vercel -> Settings -> Environment Variables):

| Name | Value |
|---|---|
| PLAYFAB_TITLE_ID | C0760 |
| PLAYFAB_SECRET_KEY | secret key of the C0760 title |
| META_API_KEY | OC\|<Meta App ID>\|<Meta App Secret> |
| DISCORD_WEBHOOK_URL | Discord webhook for auth logs |
| LOGIN_MODE | titleplayer (new players become normal title players) |
| LIBS_REQUIRED | 0 |
| INTEGRITY_REQUIRED | 0 |

Photon custom auth URL: https://<your-vercel-domain>/api/photon
