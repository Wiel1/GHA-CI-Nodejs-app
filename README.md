# Continuous IntergrationCI

## Project structure

```sh
.
├── .gitignore
├── CODEOWNERS
├── LICENSE
├── README.md
├── infra
│   ├── README.md
│   └── instances
│       ├── production
│       │   ├── .terraform.lock.hcl
│       │   ├── main.tf
│       │   └── terraform.auto.tfvars.example
│       └── staging
│           ├── .terraform.lock.hcl
│           ├── create_staging_resource.sh
│           ├── extra_staging.tf.example
│           ├── main.tf
│           └── terraform.tfvars.auto.example
└── web
    ├── README.md
    ├── app.js
    ├── bin
    │   └── www
    ├── package-lock.json
    ├── package.json
    ├── public
    │   ├── javascripts
    │   └── stylesheets
    │       └── style.css
    ├── routes
    │   ├── index.js
    │   └── users.js
    ├── tests
    │   ├── app.test.js
    │   └── routes.test.js
    └── views
        ├── error.jade
        ├── index.jade
        └── layout.jade

12 directories, 26 files
```

### Test your setup

1. Create a new branch from the `main` branch and make some changes to the app
1. Push the new branch to GitHub
1. Watch the CI workflow being triggered
1. Troubleshoot issues as they rise

## LICENSE

[Copyright (c) 2021 Bassem Dghaidi (@Link-)](LICENSE)
# GHA-CI-Nodejs-app
