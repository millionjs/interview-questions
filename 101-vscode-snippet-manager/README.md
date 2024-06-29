# Snippet Manager

## Extension Functionality

1. Create a VS Code extension named "Snippet Manager."
2. Create a new view container in the VS Code sidebar and name it "Snippet Manager".
3. Use Webview to display a code snippet management tool UI in the sidebar.
4. The UI should include the following features:
   - **Add Snippet**: Users can input the name, description, and content of a code snippet and save it.
   - **Snippet List**: Display all saved code snippets, including names and descriptions (support search and filtering if time permits).
   - **Edit Snippet**: Allow users to edit saved code snippets.
   - **Delete Snippet**: Allow users to delete unwanted code snippets.
   - **Insert Snippet**: Clicking on a code snippet will insert it at the current cursor position in the open editor (optional).

## Technical Requirements

- Use the [Webview API](https://code.visualstudio.com/api/extension-guides/webview) provided by VS Code to implement the UI.
- Use React to build the WebView content.
- Use [TailwindCSS](https://tailwindcss.com/) for styling.
- Use TypeScript instead of JavaScript.

## Notes

- You can use any libraries you prefer to implement the above features.
- Keep the code clean, you may choose to use [ESLint](https://eslint.org/) / [Prettier](https://prettier.io/) / [Biome](https://biomejs.dev/), or any other code formatter.
- Ensure commit messages are clear and use English.
- We will create a GitHub repository for you, please work within the specified repository.
- If time permits, feel free to add any features that would be appropriate for this extension.
- Maximum 14 days, you can finish early if you finish early. You can push commits at any time during these 14 days. Unless there are special circumstances, this task will end after 14 days, regardless of completion status.

## Bonus

- Save snippets to a server
- Create a Slack bot that has the same functionality as the extension (Add Snippet, Snippet List, Edit Snippet, Delete Snippet, Insert Snippet)
