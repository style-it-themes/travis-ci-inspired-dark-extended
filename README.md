<p align="center">
  <img alt="style-it-themes-logo" src="https://cdn.rawgit.com/style-it-themes/style-it-themes-logos/864bb0c047a612c2c07089901e33d33199c81ef9/style-it-themes-logo-full.svg" width="580">
</p>
<br>
<h2 align="center"><strong>Travis CI Inspired Dark Extended</strong></h2>
<p align="center">
  <a href="https://discord.gg/EpdGSfH">
    <img src="https://img.shields.io/badge/style--it--themes-discord%20channel-blue.svg?style=for-the-badge" alt="Style-it-themes Discord Channel">
  </a>
  <a href="https://github.com/style-it-themes/travis-ci-inspired-dark-extended/releases">
    <img src="https://img.shields.io/github/tag/style-it-themes/travis-ci-inspired-dark-extended.svg?label=Current%20Version&style=for-the-badge" alt="Style-it-themes Current Version">
  </a>
  <a href="https://david-dm.org/Style-it-Themes/travis-ci-inspired-dark-extended?type=dev">
    <img src="https://img.shields.io/david/dev/style-it-themes/travis-ci-inspired-dark-extended.svg?label=devDependencies&style=for-the-badge" alt="devDependencies">
  </a>
</p>

## About

This project started to give Travis CI a dark style, but it soon became apparent that some other sites coverage was needed. So the Extended version was sort of started instead.

I drew some inspiration by [StylishThemes/GitHub-Dark](https://github.com/StylishThemes/GitHub-Dark) and the idea is to transition smoothly from GitHub Dark to other associated projects used sometimes.

At launch, a total of 7 sites are covered either partially or fully.
There are some limitations on a opensource free project account to provide ✳️ full coverage.

if you would like to contribute, please keep reading.

Have fun and save the corneas 😊

## Sites Covered

| Site Name                                      | Partial |  Full  |
| ---------------------------------------------- | :-----: | :----: |
| [Travis CI.org](https://travis-ci.org)         |         |   ✔️   |
| [Travis CI.com](https://travis-ci.com)         |         |   ✔️   |
| [Blog](https://blog.travis-ci.com/)            |         |   ✔️   |
| [About](https://about.travis-ci.com)           |         |   ✔️   |
| [Docs](https://docs.travis-ci.com/)            |         |   ✔️   |
| [Status](https://www.traviscistatus.com/)      |         |   ✔️   |
| [Enterprise](https://enterprise.travis-ci.com) |   ✔️    |        |
| [Support](https://support.travis-ci.com)       |         |   ✔️   |

✳️ Further full coverage is not planned at this time, PR's are welcome though.

## Installing

* Stylus - install the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) and [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

#### Then install this style using:  

[![INSTALL DIRECTLY WITH - STYLUS Stylus](https://img.shields.io/badge/Install_directly_with-Stylus-21d1d0.svg?longCache=true&style=for-the-badge)](https://cdn.rawgit.com/style-it-themes/travis-ci-inspired-dark-extended/master/travis-ci-inspired-dark-extended.user.css)
  > Only available using Stylus (see the [documentation](https://github.com/openstyles/stylus/wiki/Usercss)). 🎉

[Manually](https://raw.githubusercontent.com/style-it-themes/travis-ci-inspired-dark-extended/master/travis-ci-inspired-dark-extended.css) into the editor.
  > Please refer to the [installation documentation](https://github.com/style-it-themes/travis-ci-inspired-dark-extended/wiki/Install) for more details.

## I Found a Bug

At the first instance of finding a bug, have a look if there is already an open issue, if so add the required information as described in the [issue template](.github/ISSUE_TEMPLATE.md).

If your issue is new, please [open an issue](https://github.com/style-it-themes/travis-ci-inspired-dark-extended/issues/new) and report your problem.

## Contributing

At this time any help is appreciated, so if you can help fix a bug or improve the **Travis CI Inspired Dark Extended** theme, just open a pull request to start the ball rolling.

You will need to ideally:

* [Fork](https://github.com/style-it-themes/travis-ci-inspired-dark-extended/fork) the project.

* Limit to the [K&R (KNF variation style)](https://en.wikipedia.org/wiki/Indentation_style#Variant:_BSD_KNF), and **2 SPACE INDENTATION** (no tabs, and no less than 2 spaces).

* K&R - KNF Variation Example:
  ```css
  element[attr='value'] {
  ··property: value;
  }
  ```

* **Not Allman**
  ```css
  element[property='value']
  {
  ··property: value;
  }
  ```

* Strict space between the `selector` and the `{`:
  ```css
  /* good */
  element[attr='value'] { }

  /* bad */
  element[attr='value']{ }
  ```

* 2 Space indentation
  ```css
  /* good */
  ··property: value;

  /* bad */
  ····property: value;
  ----property: value;
  ·property: value;
  ```
✳️ Try to wrap lines at around 250 characters, though the development scripts will clean/indent your CSS.

### Development Scripts

* `npm run clean`: Runs the Perfectionist script, cleans up after it and fixes some CSS via Stylelint.
* `npm run eslint`: Lint the JavaScript code in the `tools` directory.
* `npm run lint`: Run ESlint & Stylelint scripts.
* `npm run major`: Creates a semantic major release.
* `npm run minor`: Creates a semantic minor release.
* `npm run patch`: Creates a semantic patch release.
* `npm run perfectionist`: Runs Perfectionist only. The CSS is not cleaned/fixed!
* `npm run stylelint`: Run stylelint on the CSS file.
* `npm run lintfix`: Run stylelint with `--fix` on the CSS file.
* `npm run test`: Same as `npm run lint`.
* `npm run update`: Update development dependencies.

## Screens

![history](/screens/travis-ci-inspired-dark-extended.gif)

[![MIT](https://img.shields.io/badge/License-MIT-blue.svg?longCache=true&style=for-the-badge)](LICENSE)
