# Roman API Documentation Artefacts

## About Roman API

[Roman API](https://romanapi.com/v1/numeral/i) is a tiny, [open source](https://github.com/doubleplusco/romanapi/) API to convert Roman numerals to Arabic and vice versa. The API is deployed as a serverless microservice on [Amazon API Gateway](https://aws.amazon.com/api-gateway/) and [AWS Lambda](https://aws.amazon.com/lambda/).

## About Roman API Documentation

The interactive documentation for Roman API is at [docs.romanapi.com](http://docs.romanapi.com), and is served by GitHub directly from this repository.

This repository contains documentation artefacts for Roman API, which have mostly been cloned from [the Swagger UI repository](https://github.com/swagger-api/swagger-ui/tree/master/dist). The only customisations are:

1. [romanapi.json](https://github.com/doubleplusco/romanapi-docs/blob/gh-pages/romanapi.json): The Swagger 2.0 API definition. The same file (pretty much) was used to automatically create the API on Amazon API Gateway (via [the Amazon API Gateway Importer](https://github.com/awslabs/aws-apigateway-importer)).
2. [index.html](https://github.com/doubleplusco/romanapi-docs/blob/gh-pages/index.html): The Swagger UI bootstrap page, with some tweaks.