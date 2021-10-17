# Create a Local Instance

Rosalia runs on TypeScript, using Node as the environment. In order to test your changes locally, you will need some specific requirements.

> [!TIP]
> Some of the tooling relies on a UNIX based environment. If you are developing on Windows, we recommend using Git Bash or WSL2 to avoid errors.

## Requirements

| Name      | Version | Instructions                                                                                                        |
| --------- | ------- | ------------------------------------------------------------------------------------------------------------------- |
| Node.js   | 16.10.0 | [Download](https://nodejs.org/en/download/)                                                                         |
| npm       | 8.0.0   | Comes bundled with node. Update with `npm i -g npm`.                                                                |
| MongoDB   | 4.4.9   | [Atlas Instructions](https://www.freecodecamp.org/news/get-started-with-mongodb-atlas/) \                           |
| Sentry.io | null    | [Sentry Instructions](https://www.freecodecamp.org/news/how-to-add-sentry-to-your-node-js-project-with-typescript/) |

## Installation

When you have met the above requirements, you are ready to install the project. Begin by cloning the [GitHub Repository](https://github.com/RosaliaNightsong/discord-bot). Navigate to the directory containing your newly cloned files in your terminal.

Running the following commands will get things installed:

`npm ci` - This will install all of the `node_modules` dependencies.

`npm run build` - This will compile the TypeScript files in to JavaScript files that Node can run.
