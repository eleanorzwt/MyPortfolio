<div align="center">
<a href="https://victoreke.com"><img src="./public/logo.png" width="60px"></a>
</div>

<div align="center">
<h1>Eleanor</h1>
<p>My personal portfolio website</p>
</div>

## Run Project Locally

Follow this guide to get this site runnning locally:

### Clone Repository

```js
git clone https://github.com/eleanorzwt/MyPortfolio.git

cd MyPortfolio

npm install
```

- Rename [`.env.example`][env-example] to `.env.local`

### Get Env variables

The minimal `env` variables required to boot this project locally includes:

- `Project Id`
- `Dataset`
- `API Version`
- `Access Token`

These variables come from Sanity. To get them, you need to setup your own Sanity instance. Follow the steps below to do this:

### Create a new sanity project

Run the command below in a terminal to create a new Sanity project:

```js
npm create sanity@latest -- --template clean --create-project "portfolio-site" --dataset production
```

- **Create an account**: If you already have a Sanity account, this will automatically connect to it, if not, select a login provider from the list of options, hit `Enter` and follow the prompt to create one.
- **Choose an Output path**: Hit the `Enter` key to select the default path.
- Install the dependencies with your preferred package manager

Once completed open up the studio directory.

```js
cd portfolio-site

code .
```

## Additional Information

Need more guidiance, check out this [tutorial][sanity-guide] that provides a step-by-step guide to setting up Sanity studio for your portfolio site.

## Build

```bash
npm run build
```
