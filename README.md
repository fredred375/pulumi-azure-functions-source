# nodejs-azure-function-example

Example js code for Azure Function App.

## Development

### Requirements

- Node.js
- yarn

### Instruction

#### Clone Code

```bash
git clone git@gitlab.com:moxa/ibg/software/platform/cloud/public/examples/nodejs-azure-function-example/nodejs-function-example.git
```

#### Setup Local Environment

```bash
cd function

# install packages
npm install

# runs nodemon dev server
npm start
```

#### Pipeline

Needed environment variables defined in Gitlab CI/CD settings:

```
ARM_CLIENT_ID
ARM_CLIENT_SECRET
ARM_SUBSCRIPTION_ID
ARM_TENANT_ID
AZ_STORAGE_ACCOUNT
AZ_STORAGE_CONTAINER
GITLAB_TOKEN=your_project_access_token
```
# pulumi-azure-functions-source
