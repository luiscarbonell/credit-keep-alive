# Credit Keep Alive

A simple React application to help users keep credit cards from getting deactivated from lack of use.

### Infrastructure

- **[Terraform](https://registry.terraform.io/providers/hashicorp/aws/latest/docs):** _infrastructure as code_
- **[AWS CloudFront](https://aws.amazon.com/cloudfront/):** _distributes web artifacts_
- **[AWS S3](https://aws.amazon.com/s3/):** _storage_
- **[AWS Cognito](https://aws.amazon.com/cognito/):** _user authentication_
- **[AWS Lambda](https://aws.amazon.com/lambda/):** _logic_
- **[AWS AppSync](https://aws.amazon.com/appsync/):** _data access controls_
- **[AWS Shield Advance](https://aws.amazon.com/shield/) & [AWS WAF](https://aws.amazon.com/waf/):** _security_

### Web

- **[React](https://reactjs.org/):** _javascript framework_
  - **[Next.js](https://nextjs.org/):** _react framework_
    - **[Redux Thunk](https://github.com/vercel/next.js/tree/canary/examples/with-redux-thunk):** _state management_
    - **[Apollo GraphQL](https://github.com/vercel/next.js/tree/canary/examples/with-apollo):** _data client_
- **[Tailwind CSS](https://tailwindcss.com/):** _styling framework_

### Tools

- **[Stripe Billing](https://stripe.com/billing):** _payment processing_
