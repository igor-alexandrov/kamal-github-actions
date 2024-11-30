# Kamal GitHub Actions

A collection of GitHub Actions workflows to work with Kamal 2

## Digital Ocean

```bash
└── digital-ocean
    └──.github
        └── workflows
            ├── 01.deploy_production.yaml # deploy to production on push to branch
            ├── 02.deploy_manually.yaml # deploy to selected envrironment on manual trigger
            ├── 03.kamal_run_command.yaml # run Kamal command on selected environment
            └── setup
                └── action.yml
    └──.kamal
        └── secrets-common
    └── config
        ├── deploy.production.yml # production environment configuration
        └── deploy.yml # commom configuration
```

## AWS

```bash
└── aws
    └──.github
        └── workflows
            ├── 01.deploy_production.yaml # deploy to production on push to branch
            ├── 02.deploy_manually.yaml # deploy to selected envrironment on manual trigger
            ├── 03.kamal_run_command.yaml # run Kamal command on selected environment
            └── setup
                └── action.yml
    └──.kamal
        └── secrets-common
    └── config
        ├── deploy.production.yml # production environment configuration
        └── deploy.yml # commom configuration
```

## GCP

```bash
└── gcp
    └──.github
        └── workflows
            ├── 01.deploy_production.yaml # deploy to production on push to branch
            ├── 02.deploy_manually.yaml # deploy to selected envrironment on manual trigger
            ├── 03.kamal_run_command.yaml # run Kamal command on selected environment
            └── setup
                └── action.yml
    └──.kamal
        └── secrets-common
    └── config
        ├── deploy.production.yml # production environment configuration
        └── deploy.yml # commom configuration
```
