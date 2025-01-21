# Welcome to CeyLabs!

## About Us
CeyLabs is a leader in web3 community building and web3 development. We specialize in creating robust software platforms, crypto payment gateways, and are experts in developing Telegram bots. Our mission is to enhance user experience through intuitive design and deploy scalable solutions that meet modern business needs.

## Our Services
- **Software Development:** Crafting custom software solutions tailored to specific business requirements.
- **Crypto Payment Gateways:** Providing secure, efficient crypto transaction solutions.
- **Telegram Bot Development:** Developing interactive, feature-rich Telegram bots for various applications.
- **Cloud Solutions:** Leveraging the cloud for enhanced scalability, performance, and reliability.
- **UI/UX Design:** Designing aesthetically pleasing interfaces that are user-friendly and engaging.
- **Consultancy:** Providing expert advice to optimize your technological strategies.

## Repository Guidelines

### Naming Conventions
- **Repositories:** Repos should be named according to the format: `client-product-subproduct-app-type`. Examples include `bom-ticketing-sc` for a Smart Contract in the Battle of the Maroons ticketing system, `client-product-web-fe` for a client product's frontend web application.
- **Branches:** Use descriptive names for branches, prefixed with the type of work e.g., `cmnisal/feature/add-login`, `rayaanr/bugfix/header-fix`, `scoopa/hotfix/login-issue`.
- **Commits:** Write clear, concise commit messages that explain the why, not just the what.
- **App Types:**
  - `SC` - Smart Contract
  - `FE` - Front End
  - `BE` - Back End
  - `WP` - WordPress
  - `TGBot` - Telegram Bot
  - `TMA` - Telegram Mini App
  - `PWA` - Progressive Web App

### Branching Strategy
- **Main Branch:** The `main` branch is the source of truth and contains the production-ready code.
- **Development Branch:** All feature branches are merged into the `development` branch. After thorough testing, changes in the development branch are merged into `main`.
- **Feature Branches:** Start from the `development` branch and rebase frequently to incorporate updates.

### Production Deployment
- **Server Manager:** We use `sm.ceyl.one` as our server management tool to handle backend deployments smoothly and efficiently.
- **Frontend Deployment:** Frontend updates are deployed via Vercel. Ensure that all merges into the `main` branch are production-ready, as they will be automatically deployed to the live environment.

## Contributing
We appreciate contributions from all developers. To contribute:
1. Fork the repository.
2. Create a new branch for your feature.
3. Submit a pull request against our `development` branch.

## Contact Us
For more information, please visit our [website](https://www.ceylabs.io) or reach out directly through our contact channels.

Thank you for being part of our community!
