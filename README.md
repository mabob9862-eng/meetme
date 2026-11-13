# MeetMe Kenya — mobile installable prototype

This repository contains a mobile-first Progressive Web App (PWA) prototype. It is not yet a production social network.

## Enable GitHub Pages
1. Open repository Settings.
2. Select Pages in the left sidebar.
3. Under Build and deployment, choose Deploy from a branch.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for the Pages deployment to finish. The URL should be https://mabob9862-eng.github.io/meetme/

## Install on phones
- iPhone: open the HTTPS site in Safari, tap Share, then Add to Home Screen.
- Android: open the HTTPS site in Chrome, tap Install app or Add to Home screen.

## Prototype limitations
Sample profiles are fictional. Location permission only tests the browser permission prompt; it does not perform live nearby-user search. Chat messages are local to the current browser and are not delivered to another user. There is no authentication or server database yet.

## Production work required
Before public launch, connect a secure backend (authentication, profiles, location search and realtime chat), enable database row-level security, add age gating (18+), blocking/reporting and moderation, account deletion, privacy policy and terms. Never expose precise coordinates. Review Kenya's data-protection requirements before collecting personal/location data.