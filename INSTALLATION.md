# Installation Guide

## 1. Open your GitHub profile repository

Go to:

https://github.com/sabidahmedsunve/sabidahmedsunve

## 2. Replace the current README

Open `README.md`, click the pencil icon, select everything, delete it, then paste the contents of the new `README.md` from this package.

Commit message:

`Upgrade GitHub profile README`

## 3. Upload the banner

Create an `assets` folder in the repository and upload:

`assets/github-profile-banner.svg`

The README already points to this location.

## 4. Add the snake workflow

Create these folders:

`.github/workflows/`

Upload:

`.github/workflows/snake.yml`

Commit the file. Then open the repository’s **Actions** tab and run the workflow named:

`Generate contribution snake`

The animation will be published to an `output` branch. It may take a minute to appear.

## 5. Verify the profile

Go to:

https://github.com/sabidahmedsunve

Check:

- Banner appears
- LinkedIn, portfolio and email links work
- Stats load correctly
- Contribution snake appears after the workflow runs

## Important accuracy note

The README describes projects and research based on information already provided. Do not add project links, results, certifications or achievements unless they are genuine and publicly available.
