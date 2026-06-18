# github-app


## Features

Here's a list of features included in this project:

| Name                                     | Description                                |
|------------------------------------------|--------------------------------------------|
| /health                                  | Healthcheck endpoint returning HTTP OK 200. |
| /{conversation_id}/{conversation_domain} | Webhook endpoint.                          |

## Building & Running

To build or run the project, you can use the IDE Run configuration with environment variables.

| Project            | Environment Variables                                                                               |
|--------------------|-----------------------------------------------------------------------------------------------------|
| `GitHub App (this)` | Please check [EnvironmentVariables.kt](src/main/kotlin/com/wire/github/util/EnvironmentVariables.kt) |
| `Wire App SDK`     | Please check [Wire App SDK](https://github.com/wireapp/wire-apps-jvm-sdk)                           |

An example of this project environment variables:
```
GHAPP_API_HOST=https://127.0.0.1/github
GHAPP_SERVER_PORT=8083
GHAPP_REDIS_HOST=redis://redis
GHAPP_REDIS_PORT=6380
WIRE_SDK_API_HOST=https://nginz-https.chala.wire.link
WIRE_SDK_API_TOKEN=myApiToken
WIRE_SDK_APP_ID=f562e146-dec2-4d85-93c7-7132746b5cca
WIRE_SDK_CRYPTOGRAPHY_STORAGE_PASSWORD=myDummyPasswordmyDummyPassword01
```

## Deployment
Currently, we are only deploying in our Integrations VM.

When a proper release is done we will update this section.
