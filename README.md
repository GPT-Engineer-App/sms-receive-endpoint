# sms-receive-endpoint

Story 2: Receive SMS Endpoint
Summary: Implement the receive SMS endpoint.

Description: Create an endpoint that receives incoming SMS messages and stores the details in the database. This includes the sender's number, recipient's number, message body, and any media URL attached to the message.

Test Cases:

Test that the endpoint stores the incoming SMS details in the database.
Test that the endpoint returns a 200 status code after storing the message.
Test that the endpoint handles messages with and without media URLs.
Test that the endpoint returns an error if required headers are missing.
Dev Instructions:

Use Flask for the backend.
Create a model for storing received messages using SQLAlchemy.
Ensure proper handling of incoming headers and JSON body.
Implement error handling for missing headers or body fields.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/sms-receive-endpoint.git
cd sms-receive-endpoint
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
