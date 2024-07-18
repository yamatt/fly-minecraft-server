# Fly Minecraft Server

This is a scale to zero Minecraft server in fly.io using GitHub Actions and without needing to use Terraform and have to manage state.

## Setup

You will need a fly.io account, then install and setup the [fly.io CLI](https://fly.io/docs/flyctl/install/) then run:

```bash
flyctl launch --name <minecraft server>
```

Where `<minecraft server>` is the name of your minecraft server

## Licence

MIT
