---
title: OpenCoPilot
date: 2023-10-13T10:00:00.000Z
extra:
  featured: true
  link: https://github.com/codebanesr/OpenCoPilot
  image: https://avatars.githubusercontent.com/u/134641592?s=48&v=4
description: OpenCopilot allows you to have your own product's AI copilot. It integrates with your underlying APIs and is able to execute API calls whenever needed. It uses LLMs to determine if the user's request requires calling an API endpoint. Then, it decides which endpoint to call and passes the appropriate payload based on the given API definition.

taxonomies:
  tags:
    - Open Source
    - Collaboration
    - Software Development

---

How does it work?

- Provide your API/backend definition, including your public endpoints and how to call them. Currently, OpenCopilot supports Swagger OpenAPI 3.0. We're also working on a UI to allow you to dynamically add endpoints.
- OpenCopilot validates your schema to achieve the best results.
- We feed the API definition to an LLM.
- Finally, you can integrate our user-friendly chat bubble into your SaaS app.
