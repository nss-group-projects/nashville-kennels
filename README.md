# Nashville Kennels

## Deployed Working App

You can visit the [deployed Nashville Kennels application](https://kennels.nss.team) to see how the application should work.

## Setup

1. Run `npm install --location=global yarn`. If that doesn't work, try `npm install -g yarn`
1. Clone the repository and `cd` into the project directory.
1. Run `yarn install`.
1. Run `npm install typescript --save-dev`
1. Run `yarn start` to verify that the application compiles and starts in the browser.

### API

Each teammate will run their own API instead of using a shared one. In the `data` directory, you will see a `database.json.fixture` file that each teammate will use to [seed their database](https://en.wikipedia.org/wiki/Database_seeding).

Each teammate should create a **separate** directory in their workspace directory named `kennel-api`. Then create a `database.json` file in that directory. Copy pasta the example data into the new file. Then start json-server in that directory.

We repeat, **DO NOT CREATE A `database.json` FILE ANYWHERE IN THE APPLICATION REPOSITORY**.

