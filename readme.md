# Welcome to the Anythink Market repo


## Prerequiste

- [mongodb](https://docs.mongodb.com/manual/administration/install-community/) - Install MongoDB (Link includes installing + starting MongoDB locally)
    Configure Mongo connection URI - add the following command to your .zshenv or .bash_profile:
    
    `export MONGODB_URI=mongodb://localhost:27017`
    
- Install [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable)

- Node version - Make sure you use lts versions (e.g v16.14.0), you can manage the node version easily using [nvm](https://github.com/nvm-sh/nvm) 
    execute the following commands:
    `nvm install 16.14.0` - Install the desired version
    `nvm use 16.14.0` - Use the desired version
    `nvm current` - Verify current used version
    
## Getting Started

To start the app use: `./start.sh`, it'll start both the backend and the frontend.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
