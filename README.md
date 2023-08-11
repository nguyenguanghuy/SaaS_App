# [SaaS App](https://github.com/nguyenguanghuy/SaaS_App)

ReactJS and NodeJS SaaS boilerplate for your next SaaS application.

## Features
- **ReactJS:** High-performance and powerful interactive UI with React.
- **GraphQL API:** Fetching all the data you need with a single API call using GraphQL. Multiple GraphQL is merged in a single request.
- **Subscription payments:** We have integrated Stripe subscription payments to allow you to monetize your SaaS.
- **Teams:** Your users are able to invite their teammates to their account.
- **Roles and Permissions:** Your users are only able to access the data and perform the actions that are allowed within their roles and permissions.
- **Authentication:** User authentication with email and password, or via Google, Github, Facebook. Signup, login, reset password are included out of the box.
- **Cross-browsers and mobile responsiveness:** Every single components have been tested across many different browsers and devices to make sure it works every where.
- **HTML Emails:** Send beautiful and responsive HTML emails to your customers with SendGrid and MJML.
- **Easy to upgrade:** Easy release is planned and tailored carefully to make sure your upgrade experience smooth and painless.

## Requirements
- NodeJS v14 or above
- Yarn or NPM
- MySQL

## Get started
- Clone this repo: `git clone https://github.com/nguyenguanghuy/SaaS_App`
- Follow [this guide](https://github.com/nguyenguanghuy/SaaS_App/blob/master/docs/prerequisite.md) to setup services and update .env file in `app` and `api` folder.
- Install NodeJS dependencies in `app` and `api`
- Follow [this guide](https://github.com/nguyenguanghuy/SaaS_App/blob/master/docs/database.md) to setup MySQL database
- Set Stripe subscriptions `cd api && yarn run db:create-products`. You may need to update your subscription price and name before running this command. The script is located at `api/scripts/create-products`.
- Launch API server `cd api && yarn start`
- Launch front-end server `cd app && yarn start`



## Technology stack

### Front-end
- TypeScript
- React
- Tailwind
- Apollo
- Redux Toolkit
- React Hook Form
- DayJS
- DraftJS

### Back-end
- TypeScript
- NodeJS
- ExpressJS
- MySQL
- Mailgun
- MJML
- Knex
- Apollo Server
- Stripe

## Developer
- Quang Huy Nguyễn Võ - [nvoquanghuy](https://www.linkedin.com/in/nvoquanghuy/)

## License
All code in this repository is provided under the MIT
<br>
