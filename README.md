1. Open the demo site:
   https://bloominblinds1922.github.io/FranScale/

2. Click the “Connect TikTok” button.

3. You will be redirected to TikTok’s authorization screen.

4. Log in with the sandbox test account (whitelisted in the TikTok Developer Console).

5. Approve the requested scopes:
   - user.info.basic
   - user.info.profile
   - video.upload
   - video.publish
   - video.list

6. After authorization, TikTok will redirect back to the registered OAuth callback:
   https://oauth.n8n.cloud/oauth2/callback

7. The authorization code is then exchanged in n8n for an access token, enabling BB Fran Dev to post content on behalf of the connected TikTok account.
