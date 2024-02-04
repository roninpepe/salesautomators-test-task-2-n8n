# n8n Pipedrive + Slack + SMTP Workflow

### Accounts

   1. Pipedrive: [API token](https://app.pipedrive.com/settings/api)
   2. Slack: [API token](https://api.slack.com/tutorials/tracks/getting-a-token), [your apps](https://api.slack.com/apps)
   3. Email with SMTP access

### Setup

1. Install n8n according to [hosting guide](https://docs.n8n.io/hosting)
  > [!WARNING]
  > [Node 20.11.0 LTS](https://nodejs.org/en) required. [nvm](https://github.com/nvm-sh/nvm) can be used as a version manager.
2. `npm i -g n8n`
3. Run n8n. `--tunnel` if runned locally: `n8n start --tunnel`
4. Set up credentials on [credentials page](http://localhost:5678/credentials)
5. Import Workflow: http://localhost:5678/workflow/new → … → Import from URL… → https://raw.githubusercontent.com/roninpepe/salesautomators-test-task-2-n8n/main/Pipedrive_Slack_and_Mail_integration.json
6. Set up credentials for workflow nodes
7. Activate workflow
