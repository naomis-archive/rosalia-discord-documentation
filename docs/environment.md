# Environment Variables

Now you need to set the environment variables. Copy the `sample.env` file to a file named `.env`, and fill in the values accordingly.

> [!WARNING]
> These values should be kept secret. Do NOT add the values to the sample.env file, or they will be committed to git and publicly exposed.

- `DISCORD_TOKEN` - This is your bot's token from the previous step.

- `WH_URL` - This is your Webhook URL from the previous step.

- `HOME_GUILD` - This is the Discord ID for your test server. You can grab this by right clicking on your server icon and selecting "Copy ID" - you'll need to enable Developer Mode in your Discord client for this option to appear.

- `APP_ID` - This is the ID of your application. You can find this on the Discord Developer Portal.

- `MONGO_URI` - This is your MongoDB Atlas connection string.

- `SENTRY_DSN` - This is your DSN for Sentry.

- `NODE_ENV` - This is the environment you want to run in. This should be either `development` or `production`. For testing your changes locally, leave this as `development`.
