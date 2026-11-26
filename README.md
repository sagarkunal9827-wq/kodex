[![KODEX by Codex.SBS: AI-Powered Full-Stack Web Development in the Browser](./public/social_preview_index.jpg)](#)

# KODEX by Codex.SBS: AI-Powered Full-Stack Web Development in the Browser

KODEX is an AI-powered web development agent by Codex.SBS that lets you prompt, run, edit, and deploy full-stack applications directly from your browser—no local setup required. If you want to build your own AI-powered web dev agent from this codebase, [click here to get started!](./CONTRIBUTING.md)

## What Makes KODEX Different

Claude, v0, etc are incredible- but you can't install packages, run backends or edit code. That's where KODEX stands out:

- **Full-Stack in the Browser**: KODEX integrates cutting-edge AI models with an in-browser development environment powered by **WebContainers from StackBlitz**. This allows you to:
  - Install and run npm tools and libraries (like Vite, Next.js, and more)
  - Run Node.js servers
  - Interact with third-party APIs
  - Deploy to production from chat
  - Share your work via a URL

- **AI with Environment Control**: Unlike traditional dev environments where the AI can only assist in code generation, KODEX gives AI models **complete control** over the entire environment including the filesystem, node server, package manager, terminal, and browser console. This empowers AI agents to handle the entire app lifecycle—from creation to deployment.

Whether you're an experienced developer, a PM or designer, KODEX allows you to build production-grade full-stack applications with ease.

For developers interested in building their own AI-powered development tools with WebContainers, check out the open-source codebase in this repo!

## Tips and Tricks

Here are some tips to get the most out of KODEX:

- **Be specific about your stack**: If you want to use specific frameworks or libraries (like Astro, Tailwind, ShadCN, or any other popular JavaScript framework), mention them in your initial prompt to ensure KODEX scaffolds the project accordingly.

- **Use the enhance prompt icon**: Before sending your prompt, try clicking the 'enhance' icon to have the AI model help you refine your prompt, then edit the results before submitting.

- **Scaffold the basics first, then add features**: Make sure the basic structure of your application is in place before diving into more advanced functionality. This helps KODEX understand the foundation of your project and ensure everything is wired up right before building out more advanced functionality.

- **Batch simple instructions**: Save time by combining simple instructions into one message. For example, you can ask KODEX to change the color scheme, add mobile responsiveness, and restart the dev server, all in one go saving you time and reducing API credit consumption significantly.

## Attribution

This project is based on the open-source Bolt.new codebase, copyright (c) 2024 StackBlitz, Inc., released under the MIT License. The original copyright and license notice is retained in the [LICENSE](./LICENSE) file. KODEX and Codex.SBS are not affiliated with StackBlitz, Inc.
