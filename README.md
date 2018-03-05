# WE ARE FINE
*for git commands scroll to the bottom for Cheatsheet.*

### Links: ###
* [Jonas' Resources](http://codingheroes.io/resources/) - An index page that links to nearly every possible website/resouces a web dev need.
* [Google Drive](https://drive.google.com/drive/folders/1KOZXZVLx1-RXY13hTeQaqxnocDWswZJo?usp=sharing) - Documentations and assets.
* Trello - Workflow, Planning, Timeline and etc.
* [placeholder]() - Design system.
* APIs:
  * [placeholder]() -
  * [placeholder]() -
  * [placeholder]() -
---
### Versioning: ###
* The main reason I'm suggesting us to use version numbers is because we can mark every big moves in history during development, so we can easily go back in time if we made anything wrong or jump into future if we are fine.

* The versions will be put onto commits as tags, there's a specific page on the front page of the repository where you can view all the tags in a glance, also we can easily git reset the files using a tag to our desired version.

* Normally, there should be 3 digits in version numbers, since this is a small project we won't have that much bug/fix, we will have only the **Minor Features, Major Version and Commit ID.** e.g **v0.3 (1b2e1d63ff)**

```
v0.0.0 (1b2e1d6) -> commit ID, this is the first 7 digit shown in the git log.
 ^ ^ ^
 | | |
 | | +--- *We are not using the Minor Bugs number
 | +----- Minor Features (adding a div, a navbar, animations and etc)
 +------- Major Version (a complete and functional product ready for testing/UX)
```
---

### Commit & Push: ###
* Always push to **dev branch** only.
* Always Include **version number** as tags for every commit that adds in **Minor Features**.
* Commit/Push every **Minor Features**, personal preference on **Minor Bugs** or a limit of 10 changes/fixes.
* Keep massages short, visible in **one line** and use **present tense** only.
---

### Branching: ###
* To make branching as simple as possible, we are only having two branches, which is the **master branch** where possibly only two commit will be made, the initial commit and the final product. The other one will be the **development branch**, where all developing and bug fixing will take place, after confirmation the branch will merge with the master branch.
---

### Pull Request: ###
* This is just to protect our master branch from accidently merge, we don't really have to worry about this until the near end of the project where we are merging our final product.
---

### Git Cheatsheet: ###

* If you are unsure with any command, try them out on your own repo or fork this project.
---



