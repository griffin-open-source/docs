# Griffin Documentation

Documentation for the Griffin API testing framework.

Griffin is an open-source project that allows developers to create API tests with code and run those tests against their production APIs. It's like Datadog Synthetics, but it lives in your codebase.

## Repository

- **Main Repository**: [griffin-open-source/griffin](https://github.com/griffin-open-source/griffin)
- **Documentation Site**: This repository

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing Changes

Changes are automatically deployed when pushed to the main branch (if configured with Mintlify).

## Documentation Structure

- **Getting Started**: Introduction, quickstart, and development setup
- **Core Concepts**: Architecture, test system, CLI, executor, and runner guides
- **API Reference**: Complete REST API documentation for the runner service

## Resources

- [Griffin Repository](https://github.com/griffin-open-source/griffin)
- [Mintlify Documentation](https://mintlify.com/docs)
