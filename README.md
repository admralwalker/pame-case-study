# PAME: Production Assistant Market Exchange

Live product: https://use-pame.com

A crew marketplace built by production people, for production people. Crew post shifts, pick up work and trade with their department.

## What it does

- Shift board and real-time chat
- AI assistant and call sheet scanner (Amazon Bedrock)
- Billing and payouts (Stripe)
- Referral and QR system, plus SMS infrastructure

## Built with

AWS Lambda, API Gateway, DynamoDB, CloudFront, EventBridge, SQS FIFO, SNS, SES, WebSockets and Amazon Bedrock, shipped across 50+ releases. Production issues are diagnosed through CloudWatch Logs across the API Gateway, Lambda, DynamoDB, Step Functions and SES path.

## My role

Sole architect, builder and operator: infrastructure, deployment and reliability.

Part of UnHidden Holdings LLC. Portfolio: https://admralwalker.github.io
