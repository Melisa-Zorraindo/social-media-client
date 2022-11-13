# Social media client

[![Deploy static content to Pages](https://github.com/Melisa-Zorraindo/social-media-client/actions/workflows/pages.yml/badge.svg)](https://github.com/Melisa-Zorraindo/social-media-client/actions/workflows/pages.yml)
[![Automated Unit Testing](https://github.com/Melisa-Zorraindo/social-media-client/actions/workflows/unit-test.yml/badge.svg)](https://github.com/Melisa-Zorraindo/social-media-client/actions/workflows/unit-test.yml)
[![Automated E2E Testing](https://github.com/Melisa-Zorraindo/social-media-client/actions/workflows/e2e-test.yml/badge.svg)](https://github.com/Melisa-Zorraindo/social-media-client/actions/workflows/e2e-test.yml)


## To use this project

- clone the repository
- do `npm run install` to install package dependencies
- do `npm run start` to preview the site live
- if you don't have a profile, create one by clicking on 'Create Profile'
- if you already have a profile, click on 'Login' to open the login modal and sign in with your credentials

## Configuration

- The project is configured to run the following on commit:
  - `Prettier`
  - `ESLint`

- On merge to default the following configuration is applied
  - runs `Jest`
  - deploys to pages

- Code that doesn't meet the required test cannot be merged
- The project is configured for hosting

## App features

- User with @noroff.no or @stud.noroff.no email can register profile
- Registered user can login
- User can view a post content feed
- User can filter the post content feed
- User can search the post content feed
- User can view a post content item by ID
- User can create a post content item
- User can update a post content item
- User can delete a post content item
- User can create a comment on a post
- User can react to a post content item
- User can edit profile media
- User can log out
