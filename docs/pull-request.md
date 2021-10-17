# Making a Pull Request

Once you have your environment set up, you can confirm the current code will function by running `npm run start` in your terminal. This will start the bot process - if everything is configured correctly, you should see the bot post an online notice to your webhook.

## Changing Branch

> [!WARNING]
> You should never commit changes directly to the `main` branch. This can result in potential conflicts if you make additional changes, and will make things harder for you.

Change your `git` branch using the `git checkout -b <name>` command. Provide a descriptive name for your branch that reflects your changes.

## Making Changes

After everything works, you can start making changes to the code to implement your fix or feature.

Note that to test your changes, you will need to stop the bot process, run `npm run build` to compile with your new changes, and `npm run start` to launch the process again.

## Testing Changes

Before submitting your changes on GitHub, you should run the following commands to confirm the code will pass our integrations:

- `npm run lint` - This will run the linter across the entire code, ensuring that your changes comply with our style and formatting requirements.

- `npm run test` - This will run the test suite, ensuring that your code passes our validation.

> [!TIP]
> The tests confirm that the structure of data is valid, for example a new monster has item drops that exist.

## Submitting Your Changes

Once you have confirmed everything works as intended and the checks are all passing, you can commit your changes and push them up to your branch.

Then, create a pull request on GitHub, and our team will review your contributions as soon as we are available!
