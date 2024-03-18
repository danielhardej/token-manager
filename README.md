# token-manager

Welcome to my repo where I'm testing the [List fine-grained personal access tokens](https://docs.github.com/en/rest/orgs/personal-access-tokens?apiVersion=2022-11-28#list-fine-grained-personal-access-tokens-with-access-to-organization-resources) endpoint.

We're testing the app installation on this org/repository: https://github.com/Mysterious-Organisation-LLC/expert-octo-pancake

See the [issues](https://github.com/Mysterious-Organisation-LLC/expert-octo-pancake/issues) and [pull requests](https://github.com/Mysterious-Organisation-LLC/expert-octo-pancake/pulls), as this app listens for issues and pull requests webhook events.

Open me in a Codespace or in VS Code and run me with:

```bash
npx smee -u https://smee.io/s0jQFttCseN8xSyP -t http://localhost:3000/api/webhook
```

And then

```bash
npm run server
```

Next changes:

- [ ] Add a new feature