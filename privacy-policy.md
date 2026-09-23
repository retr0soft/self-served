# Self Served — privacy policy

_Last updated 22 September 2026._

Self Served is an Android app for reading and editing recipes on a recipe server you run yourself. It has
no servers of its own. It talks to the recipe server you point it at, and nothing else.

The same text is in the app under **Settings → Privacy**, so it can be read offline.

## What is kept on your phone

- Your server address, and the API token or password you signed in with.
- The recipes, meal plans, shopping lists and photos Self Served has fetched from your server.
- Settings such as your theme, default servings and sync preferences.

Sign-in details are encrypted with a key held by the Android keystore and are excluded from
Android's automatic backups.

## What leaves your phone

- Requests to your own server: the address, token and any extra headers you configured, and the
  recipes, plans and lists you read or change.
- If you tap **Report a problem**, a new GitHub issue opens in your browser with the app version,
  your device model, your Android version and your server version filled in. Nothing is posted
  unless you submit it, and GitHub issues are public, so your server's address is never included.

## What the developer collects

Nothing. There is no account with us, no analytics, no advertising and no crash reporting. The
developer cannot see your recipes, and nobody but you and your server sees what you cook.

For the Google Play Data Safety form: **no data is collected or shared by the developer.**

## Permissions

| Permission | Why |
|---|---|
| Internet / network state | To reach your recipe server. |
| Notifications | Cooking timers ring when they finish. |
| Foreground service | Timers keep running while the app is in the background. |
| Camera, photo picker | Only when you add a picture to a recipe; the picture goes to your server. |

## Deleting your data

Signing out of a server clears everything Self Served saved for it on this phone. Uninstalling Self Served
removes the lot. Recipes on your own server are yours to delete there.

## Children

Self Served is not directed at children and collects nothing from anybody.

## Changes

If this policy changes, the new version ships with the app update and is published here alongside
the store listing.

## Contact

Questions about this policy: open an issue at
[github.com/retr0soft/self-served/issues](https://github.com/retr0soft/self-served/issues), or use
**Settings → Report a problem** in the app, which does the same with your versions filled in.

---

Self Served is an unofficial app. It requires your own Mealie server and is not affiliated with the
Mealie project.
