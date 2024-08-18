# solar-JULIST

**solar-JULIST** is a fork of the Julist codebase, enhanced with a SOLAR LLM backend, developed specifically for the [Upstage Global AI Week | AI Hackathon](https://www.upstage.ai/global-ai-week-ai-hackathon).

## Project Overview

### Features

- **Image to Document Conversion:** Seamlessly transform images into editable documents via OCR.
- **Document Organization:** Efficiently organize and name your documents for easy access and management.
- **Document Searching:** Quickly search through your documents via vector search.

### Project Demo Video
Watch the video showcase of this project [here](<vdo link>).

## Installation Method

### Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

### Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with:

```bash
npm run preview
```

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Usage Instructions

(Include any specific usage instructions here)

## Upstage API

| **Code File**                 | **Upstage API Usage**                                               |
| ----------------------------- | ------------------------------------------------------------------- |
| `src/lib/server/llm.ts`       | **Chat API:** for RAG document search and conversational chatbot    |
|                               | **Function Calling:** for RAG document search                       |
| `src/lib/server/vectorstore.ts` | **Embedding:** for creating embedding vectors for RAG document search |
|                               | **OCR:** for extracting text from legal document images             |

---