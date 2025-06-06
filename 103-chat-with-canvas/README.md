https://same-hq.notion.site/take-home

# Chat With Canvas

## Functionality

1. Build the chat interface from 102-simple-chat-component
2. Add a collapsible **canvas/sidebar**:
    - Opens on demand
    - Displays React code written by the agent
    - Live-renders the component from the code
    - A similar UX to tools like:
        - [OpenAI Canvas](https://chat.openai.com/canvas)
        - [Claude Artifacts](https://www.anthropic.com/index/artifacts)
3. Rendering React code directly in-browser.
   - **You may not use external in-browser code execution services, such as sandpack to do code execution.**
   - Handle edge cases like hooks, errors, or reactivity.
4. Enable the canvas to reflect code changes to the same file live.


## Advanced

The following advanced features are optional:

1. Enhance the chat component to support markdown rendering, autoscroll, and image uploads.
2. Implement function calls, such as retrieving the current time.
3. Allow multiple files to be combined and rendered via React.
4. Add Python code execution.
5. If interested, try to implement any feature from [Same](https://same.new/) that you think a simple version would need.

## Technical Requirements

- The base stack is:
  - [TypeScript](https://www.typescriptlang.org/)
  - [Next.js](https://nextjs.org/) (App Router)
  - [Hono](https://hono.dev/) for API routing
  - [Vercel AI SDK](https://sdk.vercel.ai/) for AI integration

- UI stack:
  - [Shadcn UI](https://ui.shadcn.com/) for components
  - [TailwindCSS](https://tailwindcss.com/) for styling

## Notes

- This challenge includes solving the semi-unsolved problem of **rendering dynamic React code in-browser**. The more work you can show, the better.
- Focus on architecture, UX, and edge case handling.
- Completion time estimate: ~3 days.
- A GitHub repository will be provided. All work should be completed within it.
- Follow clean code practices (e.g., [ESLint](https://eslint.org/), [Prettier](https://prettier.io/), or [Biome](https://biomejs.dev/)).
- All commit messages must be in English.
