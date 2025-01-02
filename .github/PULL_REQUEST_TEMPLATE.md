Thank you for contributing to Zytron!

Replace this comment with:
  - Description: a description of the change, 
  - Issue: the issue # it fixes (if applicable),
  - Dependencies: any dependencies required for this change,
  - Tag maintainer: for a quicker response, tag the relevant maintainer (see below),
  - Twitter handle: we announce bigger features on Twitter. If your PR gets announced and you'd like a mention, we'll gladly shout you out!

Please make sure your PR is passing linting and testing before submitting. Run `make format`, `make lint` and `make test` to check this locally.

If you're adding a new integration, please include:
  1. a test for the integration, preferably unit tests that do not rely on network access,
  2. an example notebook showing its use.


Maintainer responsibilities:
  - General / Misc / if you don't know who to tag: help@openagents-ai.io
  - DataLoaders / VectorStores / Retrievers: help@openagents-ai.io
  - zytron.models: help@openagents-ai.io
  - zytron.memory: help@openagents-ai.io
  - zytron.structures: help@openagents-ai.io

If no one reviews your PR within a few days, feel free to email OpenAgents AI at help@openagents-ai.io

See contribution guidelines for more information on how to write/run tests, lint, etc: https://github.com/OpenAgentsAI/zytron-ecosystem