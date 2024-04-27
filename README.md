This is a demo that showcases using CopilotKit to build a PowerPoint like web app.

USE DEMO CAN BE VIEWED HERE: https://www.youtube.com/watch?app=desktop&v=gCJpH6Tnj5g&embeds_referring_euri=https%3A%2F%2Fdev.to%2F&source_ve_path=MjM4NTE&feature=emb_title

## Getting Started

### 1. install the needed package:

```bash
npm i
```

### 2. Set the required environment variables:

copy `.env.local.example` to `.env.local` and populate the required environment variables.

> ⚠️ **Important:** Not all users have access to the GPT-4 model yet. If you don't have access, you can use GPT-3 by setting `OPENAI_MODEL` to `gpt-3.5-turbo` in the `.env.local` file.

### 3. Run the app

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.


### 4. Use the Copilot
Create a new campaign, or edit an existing campaign, and use the Copilot assitant to configure the form without requiring domain knowledge.


## Zoom in on the CopilotKit code
  1. Search for `useMakeCopilotReadable` to see where frontend application information is being made accessible to the Copilot engine

  2. Search for `updateCurrentCampaign` and `retrieveHistoricalData` to see where the frontend application action is made accessible to the Copilot engine.


## Learn More

To learn more about CopilotKit, take a look at the following resources:

- [CopilotKit Documentation](https://docs.copilotkit.ai/getting-started/quickstart-chatbot) - learn about CopilotKit features and API.
- [GitHub](https://github.com/CopilotKit/CopilotKit) - Check out the CopilotKit GitHub repository.
- [Discord](https://discord.gg/6dffbvGU3D) - Join the CopilotKit Discord community.
