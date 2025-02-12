# ModelMerge

Model Merge is an open-source platform that consolidates multiple language models into one place, allowing users to send requests to various models seamlessly from a single interface.

## Features

- Access multiple language models from one platform
- Seamlessly switch between different models
- Easy-to-use interface

## Tech Stack

**Client:** React, Shadcn, Tailwind

**Server:** Node, Express, Postgres, Prisma-ORM

## Screenshots

https://github.com/vverma022/model-merge/assets/109036913/50a1de4c-2d16-4791-badc-09cafcb3ebc5

## Installation

Before you begin, ensure you have the following,

    •	Node.js installed on your machine
    •	API keys from the following services:
    •	Gemini from https://ai.google.dev/gemini-api/docs/api-key
    •	Cohere from https://docs.cohere.com/
    •	Groq from https://console.groq.com/keys
    •	AIMLapi from https://aimlapi.com/app/sign-up/

## Run Locally

Clone the project

```bash
  git clone https://github.com/vverma022/model-merge.git
```

Go to the backend

```bash
  cd backend
```

Install dependencies

```bash
  npm install
```

Create a new .env file

If in Linux environment:

```
touch .env
```

Start the server

```bash
  npm run start
```

Go to the frontend

```bash
  cd frontend
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

## Environment Variables

To run this project, you will need to add the following environment variables to the .env file in `backend` dir

`GEMINI_API_KEY`

`COHERE_API_KEY`

`AI_ML_API_KEY`

`LLAMA_API_KEY`

## Running Tests

To run tests, run the following command

```bash
  npm run test
```

## Roadmap

- Add Additonal Models

- Add Langchain Support

- Dockerize the Models to Servers

- Create a Community

## Support

For support, email vermausav018@gmail.com.

## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
