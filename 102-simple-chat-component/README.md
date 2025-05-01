# Simple Chat Component

## Functionality

1. There needs to be a Textarea for prompts and a send/stop button.
2. There needs to be a chat container that displays the conversation history.
3. There needs to be a `/agent` api to handle requests.
4. Each conversation's data needs to be persistently stored.
5. All results should be returned via stream.

## Advanced

Advanced content is optional and not mandatory.

1. Improve the chat component, support markdown rendering, support autoscroll, support uploading images, etc.
2. Support function calls, you can create a simple function call feature, such as: getting the current time.
3. If you are very interested in this, you can try to implement any feature of [Same](https://same.new), and implement what you think a simple same needs in terms of features.

## Technical Requirements

- The basic tech stack is [TypeScript](https://www.typescriptlang.org/) / [NextJs](https://nextjs.org/) / [Hono](https://hono.dev/) / [DrizzleORM](https://orm.drizzle.team/) / [AI SDK](https://sdk.vercel.ai/).
- Use [Shadcn UI](https://ui.shadcn.com/) for components.
- Use [TailwindCSS](https://tailwindcss.com/) for styling.
- Use [nextjs app router](https://nextjs.org/docs/app) + [hono](https://hono.dev/) for the api.
- Use [DrizzleORM](https://orm.drizzle.team/) for database.
- Use [Vercel AI SDK](https://sdk.vercel.ai/) for model calling.

## Notes

- Estimated time 4 hours.
- We will provide a GitHub repository, please complete development in the repository. We won't provide any help other than creating the repository.
- You can use any libraries you prefer to implement the above features.
- Keep the code clean, you may choose to use [ESLint](https://eslint.org/) / [Prettier](https://prettier.io/) / [Biome](https://biomejs.dev/), or any other code formatter.
- Ensure commit messages are clear and use English.
- We will create a GitHub repository for you, please work within the specified repository.
- If time permits, feel free to add any features that would be appropriate for this extension.
