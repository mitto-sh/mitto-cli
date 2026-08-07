# mitto-cli

CLI — deploy and manage your apps from the terminal.

## Commands
```bash
mitto login              # authenticate
mitto deploy             # deploy current directory
mitto logs --tail        # stream live logs
mitto env set KEY=value  # set environment variable
mitto env list           # list env vars
mitto db create postgres # provision a managed database
mitto domains add        # add custom domain
mitto rollback           # rollback to previous deployment
```

## Install
```bash
# npm
npm install -g @mitto-sh/cli

# curl
curl -fsSL https://get.mitto.sh | bash
```

## Stack
> TBD
