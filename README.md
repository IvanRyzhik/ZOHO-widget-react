# React-widget for ZOHO

## To start project locally

In root folder run:

- yarn (to install dependencies for zoho part, needed only for first launch)

Navigate to `react-part` folder:

- yarn (to install dependencies for react part)
- yarn start

## ZOHO API not working locally

- for development you will need to work with mock data

## To create build

Navigate to `react-part` folder:

- yarn build

This script will create build inside `app` folder -> then `zet pack` will run automatically -> zip package for uploading to ZOHO will be created in `dist` folder

## Important

Correct PATH to index file in ZOHO widget uploading -> Index Page field

```
/build/index.html
```
