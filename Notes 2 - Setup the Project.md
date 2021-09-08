# [SETUP THE PROJECT](https://learn.figment.io/tutorials/setup-the-polkadot-project)
Let's setup the project to connect & interact with Polkadot
The following software is required to set up and complete the Polkadot pathway
  - [Node.js v14.17.5 or higher installed](Node.js v14.17.5 or higher installed)
  - `yarn` [installed](https://yarnpkg.com/getting-started/install)
  - `git` [installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Start by cloning the repository and installing the dependencies with `yarn` :
`$ git clone https://github.com/figment-networks/learn-web3-dapp.git`
`$ cd learn-web3-dapp`
`$ yarn`

## Set your API Key
The value for `DATAHUB_POLKADOT_API_KEY` can be found on the DataHub Services Dashboard. Click on the **Polkadot** icon in the list of available protocols and then copy your key as shown below. You can now paste your personal API key into `.env.local`. This will authenticate you and enable you to make JSON-RPC requests to Secret via DataHub.

## Start the server
With the API key in place, save the `.env.local` file and start the Next.js development server with:
`$ yarn dev`
Once the development server loads and compiles the application, open your default browser and navigate to `http://localhost:3000`

## Next
You can now move ahead to the next step by clicking on the "Next" button below on the right. There are also links to the instructions for each step on the UI.