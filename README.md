<!-- markdownlint-disable MD013 MD041 MD043  -->
# AWS Lambda Powertools for Python



[![Build](https://github.com/awslabs/aws-lambda-powertools-python/actions/workflows/python_build.yml/badge.svg)](https://github.com/awslabs/aws-lambda-powertools-python/actions/workflows/python_build.yml)
[![codecov.io](https://codecov.io/github/awslabs/aws-lambda-powertools-python/branch/develop/graphs/badge.svg)](https://app.codecov.io/gh/awslabs/aws-lambda-powertools-python)
![PythonSupport](https://img.shields.io/static/v1?label=python&message=%203.7|%203.8|%203.9&color=blue?style=flat-square&logo=python) ![PyPI version](https://badge.fury.io/py/aws-lambda-powertools.svg) ![PyPi monthly downloads](https://img.shields.io/pypi/dm/aws-lambda-powertools) [![Join our Discord](https://dcbadge.vercel.app/api/server/B8zZKbbyET)](https://discord.gg/B8zZKbbyET)

A suite of Python utilities for AWS Lambda functions to ease adopting best practices such as tracing, structured logging, custom metrics, [and more](https://awslabs.github.io/aws-lambda-powertools-python/latest/#features).

> Also available in [Java](https://github.com/awslabs/aws-lambda-powertools-java), [Typescript](https://github.com/awslabs/aws-lambda-powertools-typescript), and [.NET](https://awslabs.github.io/aws-lambda-powertools-dotnet/).

**[📜Documentation](https://awslabs.github.io/aws-lambda-powertools-python/)** | **[🐍PyPi](https://pypi.org/project/aws-lambda-powertools/)** | **[Roadmap](https://awslabs.github.io/aws-lambda-powertools-python/latest/roadmap/)** | **[Detailed blog post](https://aws.amazon.com/blogs/opensource/simplifying-serverless-best-practices-with-lambda-powertools/)**

> **An AWS Developer Acceleration (DevAx) initiative by Specialist Solution Architects | aws-devax-open-source@amazon.com**

![hero-image](https://user-images.githubusercontent.com/3340292/198254617-d0fdb672-86a6-4988-8a40-adf437135e0a.png)

## Features

* **[Tracing](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/tracer/)** - Decorators and utilities to trace Lambda function handlers, and both synchronous and asynchronous functions
* **[Logging](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/logger/)** - Structured logging made easier, and decorator to enrich structured logging with key Lambda context details
* **[Metrics](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/metrics/)** - Custom Metrics created asynchronously via CloudWatch Embedded Metric Format (EMF)
* **[Event handler: AppSync](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/event_handler/appsync/)** - AWS AppSync event handler for Lambda Direct Resolver and Amplify GraphQL Transformer function
* **[Event handler: API Gateway and ALB](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/event_handler/api_gateway/)** - Amazon API Gateway REST/HTTP API and ALB event handler for Lambda functions invoked using Proxy integration
* **[Bring your own middleware](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/middleware_factory/)** - Decorator factory to create your own middleware to run logic before, and after each Lambda invocation
* **[Parameters utility](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/parameters/)** - Retrieve and cache parameter values from Parameter Store, Secrets Manager, or DynamoDB
* **[Batch processing](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/batch/)** - Handle partial failures for AWS SQS batch processing
* **[Typing](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/typing/)** - Static typing classes to speedup development in your IDE
* **[Validation](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/validation/)** - JSON Schema validator for inbound events and responses
* **[Event source data classes](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/data_classes/)** - Data classes describing the schema of common Lambda event triggers
* **[Parser](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/parser/)** - Data parsing and deep validation using Pydantic
* **[Idempotency](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/idempotency/)** - Convert your Lambda functions into idempotent operations which are safe to retry
* **[Feature Flags](https://awslabs.github.io/aws-lambda-powertools-python/latest/utilities/feature_flags/)** - A simple rule engine to evaluate when one or multiple features should be enabled depending on the input

### Installation

With [pip](https://pip.pypa.io/en/latest/index.html) installed, run: ``pip install aws-lambda-powertools``




## Tutorial and Examples

* [Tutorial](https://awslabs.github.io/aws-lambda-powertools-python/latest/tutorial)
* [Serverless Shopping cart](https://github.com/aws-samples/aws-serverless-shopping-cart)
* [Serverless Airline](https://github.com/aws-samples/aws-serverless-airline-booking)
* [Serverless E-commerce platform](https://github.com/aws-samples/aws-serverless-ecommerce-platform)
* [Serverless GraphQL Nanny Booking Api](https://github.com/trey-rosius/babysitter_api)

## Credits

* Structured logging initial implementation from [aws-lambda-logging](https://gitlab.com/hadrien/aws_lambda_logging)
* Powertools idea [DAZN Powertools](https://github.com/getndazn/dazn-lambda-powertools/)

## Connect

* **AWS Lambda Powertools on Discord**: `#python` - **[Invite link](https://discord.gg/B8zZKbbyET)**
* **Email**: aws-lambda-powertools-feedback@amazon.com

## Security disclosures

If you think you’ve found a potential security issue, please do not post it in the Issues.  Instead, please follow the instructions [here](https://aws.amazon.com/security/vulnerability-reporting/) or [email AWS security directly](mailto:aws-security@amazon.com).

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
