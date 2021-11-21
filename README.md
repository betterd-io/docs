<!-- PROJECT SHIELDS -->

![Website][website-status]
![GitHub branch checks state][github-checks]
![GitHub repo size][repo-size]

![GitHub pull requests][pull-requests]
![GitHub issues][issues]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Documentation Readme</h3>

  <p align="center">
    Everything you need to know about the documenation project, and how it works!
    <br />
    <a href="https://betterd-io.github.io/docs/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/betterd-io/docs/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5BBug%5D+-+%2AShort+Title%2A">Report Bug</a>
    ·
    <a href="https://github.com/betterd-io/docs/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=%5BFeature%5D+-+%2AShort+title%2A">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://betterd-io.github.io/docs/)

The purpose of this project, is to act as the one stop shop for documentation pertaining to the betterd application. It will contain information that will help to setup and run projects, development guidelines, etc.

Using this application, we can provide proper and quality documentation that is simple to use and follow, for any developer or user.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- [Hugo](https://gohugo.io/)
- [Dot Template](https://docs.gethugothemes.com/dot/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- homebrew

  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

  # verify with
  brew -v
  ```

- hugo

  ```sh
  brew install hugo

  # verify with
  hugo version
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/betterd-io/docs.git
   ```
2. Change into the cloned directory
   ```sh
   cd docs
   ```
3. Start the server

   ```sh
   hugo server

   # OR with drafts
   hugo server -D
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

All pages are written with markdown syntax. It is possible to use HTML if desired. Pages are by default to be in english

- To create a new page
  ```sh
  hugo new <page-title>.en.md
  ```
- To create a new sub page
  ```sh
  hugo new <folder>/<page-title>.en.md
  ```

_For hugo examples, please refer to the [Documentation](https://gohugo.io/getting-started/usage/)_

_For Markdown examples, please refer to the [Documentation](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)_

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: static/images/hero-shot.png
[website-status]: https://img.shields.io/website?style=for-the-badge&url=https%3A%2F%2Fbetterd-io.github.io%2Fdocs%2F
[github-checks]: https://img.shields.io/github/checks-status/betterd-io/docs/main?style=for-the-badge
[repo-size]: https://img.shields.io/github/repo-size/betterd-io/docs?style=for-the-badge
[pull-requests]: https://img.shields.io/github/issues-pr-raw/betterd-io/docs?style=for-the-badge
[issues]: https://img.shields.io/github/issues/betterd-io/docs?style=for-the-badge
