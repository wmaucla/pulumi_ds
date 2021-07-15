# Pulumi for DS

This project is based on the idea of launching kubeflow on AWS via Pulumi

## Codes to Run

### Setup
1. I'm on a linux machine so I started out installing pulumi: `curl -fsSL https://get.pulumi.com | sh`
2. I have `pipenv` as a primary package manager so install dependencies via `pipenv install`
3. Based on the instructions, create a new sample project `mkdir quickstart && cd quickstart` and `pipenv run pulumi new kubernetes-python`
4. Make sure to have a pulumi account created and add a new token if needed

At this point, after a few additional pulumi items get installed, should have a directory with the base example

