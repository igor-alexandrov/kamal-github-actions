# Kamal GitHub Actions DigitalOcean

Sample GitHub Actions workflow files to deploy with Kamal 2 to Digital Ocean

## Structure

```bash
└──.github
    └── workflows
        ├── 01.deploy_production.yaml # deploy to production on push to branch
        ├── 02.deploy_manually.yaml # deploy to selected envrironment on manual trigger
        ├── 03.kamal_run_command.yaml # run Kamal command on selected environment
        ├── kamal-deploy
        │   └── action.yaml
        └── setup
            └── action.yml
└── config
    ├── deploy.production.yml # production environment configuration
    └── deploy.yml # commom configuration
```