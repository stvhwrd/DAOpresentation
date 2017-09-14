# DAO Attack

![](https://www.ethereum.org/images/logos/ETHEREUM-LOGO_LANDSCAPE_Black.png)

This is a 12 minute presentation on
[The DAO attack](https://www.coindesk.com/understanding-dao-hack-journalists/)
for UVic's SENG 360 class.

### [Live demo](https://steviehoward.com/DAOpresentation/)

We assume that the audience is technically savvy but unfamiliar with
blockchain technology - specifically Ethereum.

This presentation aims to address the following points:

-   What is the nature of the vulnerability?
-   How can an attacker exploit it?
-   What controls can mitigate this vulnerability?
-   How to learn more about this vulnerability? (By providing reference to information resources)


## Deck Dev

The slides are written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and can be edited in the `Deck/presentation/markdown` folder.  Any renames or file additions must be reflected accordingly in the `Deck/presentation/markdown/index.js` file.

To run the dev server locally with Yarn/NPM and NodeJS:

-   Clone repo
-   `cd` into `Deck/`
-   `yarn` or `npm install`
-   `npm run dev`

The presentation will run at [localhost:8080](http://localhost:8080).  Updates to project files will trigger a rebuild, and changes will be reflected in browser.


## Deployment

The presentation is served by [GitHub Pages](https://pages.github.com/) and GitHub Pages dictates that static files be served from the `/docs` folder at the root of the repository.

-   `npm run predeploy` to build to `/docs`
-   `git add /docs`
-   `git commit -m "deploy updated presentation $(date +"%r") on $(date +"%Y/%m/%d")"`
-   `git push origin master`


## Credit

**ALL** credit for this particular
[Spectacle](http://formidable.com/open-source/spectacle/) boilerplate goes to
[UVic SDAML](https://sdaml.club).

This is a direct fork of
[SDAML's 2017 Introduction](http://introduction.sdaml.club/) presentation.
