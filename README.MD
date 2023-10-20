# Getting Started with AWS - Serverless Web Application

This Git repository contains a fully developed serverless web application built with AWS services, including AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito. The application allows users to request unicorn rides from the Wild Rydes fleet. It features user registration, login, and ride request functionalities.

## Introduction

Welcome to the "Getting Started with AWS - Build a Serverless Web Application" project. In this project, we have created a serverless web application that allows users to request unicorn rides from the Wild Rydes fleet. The application includes features for user registration, login, and ride requests.

## Application Architecture

The application architecture uses several AWS services to create a seamless experience for users. Here's an overview of the key components:

- **Static Web Hosting**: AWS Amplify hosts static web resources, including HTML, CSS, JavaScript, and image files loaded in the user's browser.

- **User Management**: Amazon Cognito provides user management and authentication functions to secure the backend API.

- **Serverless Backend**: Amazon DynamoDB serves as a persistence layer for data storage, used by the API's Lambda function.

- **RESTful API**: JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.

## Getting Started

Follow these steps to deploy your own instance of the serverless unicorn ride application:

1. Clone this repository to your local environment.

2. Configure AWS services: Set up AWS Lambda function, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito according to your preferences. 

3. Remove existing configurations and replace them with your own.

## Resources

- [AWS Lambda](https://aws.amazon.com/lambda/)
- [Amazon API Gateway](https://aws.amazon.com/api-gateway/)
- [AWS Amplify](https://aws.amazon.com/amplify/)
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/)
- [Amazon Cognito](https://aws.amazon.com/cognito/)
