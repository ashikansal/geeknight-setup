# Geeknight Infra Setup

### PREREQUISITE: Docker must be installed.

## 1. Clone git repo
`git clone <git-repo>`

## 2. Switch to cloned repo
`cd geeknight-setup`

## 3. Run GOCD server and agent using docker
`docker-compose up -d`

## 4. Check whether server is up by opening below URL
`https://localhost:8153`

## 5. Check whether agent is configured
```
Go to agents tab in above url.
Check whether agent is listed.

Enable the Agent once it is listed.
```