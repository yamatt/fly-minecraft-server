# Fly Minecraft Server

This is a scale to zero Minecraft server in fly.io using GitHub Actions and without needing to use Terraform and have to manage state.

When the server is not used, it switches off, reducing costs. Note that you still need to reserve an IP in fly.io which will have a monthly cost.

## Setup

You will need a fly.io account, then install and setup the [fly.io CLI](https://fly.io/docs/flyctl/install/) then run:

```bash
flyctl launch --name <factorio server>
```

Where `<factorio server>` is the name of your minecraft server

## Licence

MIT
