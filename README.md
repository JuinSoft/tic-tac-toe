Tic Tac Toe Game with Linera SDK
Overview
# Tic Tac Toe Game with Linera SDK

## Overview
This project is a Tic Tac Toe game built using the Linera SDK. The game allows two players to compete in a classic Tic Tac Toe match.

## Prerequisites
- Rust and Cargo installed
- Linera SDK installed
- Bash shell

## Building the Project
To build the project, run the following command:
`cargo build`

## Deployment
To deploy the Tic Tac Toe game, use the provided `deploy.sh` script. This script builds the project, sets up the Linera network, and starts the necessary services.

## Steps to Deploy
1. Ensure the `deploy.sh` script is executable:
2. Run the deployment script:
`./deploy.sh`

## `deploy.sh` Script
The `deploy.sh` script performs the following actions:
- Builds the project using Cargo.
- Adds the `target/debug` directory to the PATH.
- Initializes the Linera network and spawns wallet variables.
- Defines chain and owner variables.
- Publishes and creates the application, capturing the `APP_ID`.
- Starts the Linera services and keeps them running.

## Running the Game
After deployment, the game services will be running on ports 8080 and 8081. You can interact with the game using the Linera SDK commands or through a web interface if provided.
