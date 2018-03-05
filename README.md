# WE ARE FINE

### Links:
* Google Drive - Documentations and assets.
* Trello - Workflow, Planning, Timeline and etc.
* placeholder - Design system.
* APIs:
  * placeholder
  * placeholder
  * placeholder

### Versioning:
The main reason I'm suggesting us to use version numbers is because we can mark every big moves in history during development, so we can easily go back in time if we made anything wrong or jump into future if we are fine. <br><br>
Normally, there should be 3 digits in version numbers, since this is a small project we won't have that much bug/fix, we will have only the **Minor Features and Major Version.** e.g **v0.3 (1b2e1d63ff)**

```
v0.0.0 (1b2e1d6) -> commit id, this is first 7 digit shown in the git log.
 ^ ^ ^
 | | |
 | | +--- *We are not using the Minor Bugs number
 | +----- Minor Features (adding a div, a navbar, animations and etc)
 +------- Major Version (a complete and functional product ready for testing/UX)
```

### Commit & Push:
* Always push to **dev branch** only.
* Always Include **version number** inside commit message.
* Commit/Push every **Minor Features**, personal preference on **Minor Bugs** or a limit of 10 changes/fixes.
* Keep massages short, visible in **one line** and use **present tense** only.

### Git Cheatsheet:
If you are unsure with any command, try them out on your own repo or fork the project.
