# Serverless code execution demo

This repository is an example of how to run Python, NodeJs and Golang code in a serverless orchestration engine.

## Workflow overview

The workflows in this repository are different implementations of retrieving Tweets for Python, NodeJS and Golang. Each of the folders represent a language and implementation:
 - golang\serverless-golang.yaml: running the go-tweets.go implementation 
 - 

## Variables

 - go-tweets.go: Go implementation of Twitter API calls
 - nodejs-tweets.go: NodeJS implementation of Twitter API calls
 - py-tweets.go: Pythono implementation of Twitter API calls

## Secrets

 - None

## Namespace Services

 - None

## Input examples

```json
{
    "bearer_token": "AAAAAAAAA...........jhYlNYLrhlZ6F",
    "twitter_searchstring": "direktiv",
    "max_search_returns": 10
}
```

## External links:

 - Blog article: https://blog.direktiv.io/turn-your-code-into-a-serverless-api-748490acd470ß