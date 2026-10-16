### Mark McDermott · Senior Software Engineer in Test

I've spent more than 15 years shipping software and building the test systems that keep it shippable. From 2017 to 2026 I worked at Instructure on **Canvas** and **New Quizzes**. My work there covered production Rails and TypeScript as well as the automation, CI and load testing around it. That work was about taking stress and friction off developers: faster builds, fewer manual steps, shorter cycle times and tests they could trust. A better developer experience led to better end-user experiences, which ultimately improved the product's reputation and raised customer sentiment.

**Stack**

| | |
|---|---|
| App code | Ruby on Rails · TypeScript · React · GraphQL |
| Mobile | Swift · SwiftUI |
| Data | PostgreSQL, including query tuning |
| Infra | AWS · Terraform · Ansible |
| Test automation | Selenium (Ruby and JS) · Playwright · RSpec · JMeter |
| CI/CD | Jenkins · GitHub Actions, including a Jenkins → Actions migration |

I'm building my Kubernetes knowledge and skills on my own. I'm still at the novice stage, and my goal is to run and maintain a production-level personal project on it.

**AI-assisted engineering**

- Evals and guardrails for AI-generated tests, so generated code meets the same bar as hand-written code
- Playwright MCP verification loops that let an agent check its own UI changes in a real browser
- Claude Code skills for test-coverage quality analysis
- Claude and OpenAI APIs, with both cloud and local models

**Projects**

- **model-gateway** (private): a Python/FastAPI gateway that speaks the Anthropic Messages API and routes Claude Code to local, tailnet or cloud LLMs. It translates Anthropic ↔ OpenAI in both directions, including streaming and tool calls, and is covered by 117 tests.
- [**llm-start**](https://github.com/mark-tc-mcdermott/llm-start): a plain-English guide and one-line installer for running LM Studio on an 8 GB MacBook Neo, written for non-technical users.
- **Personal iOS project**: an app built in Swift and SwiftUI with MVVM and XCTest.

Chicago · [LinkedIn](https://www.linkedin.com/in/markmcdermott)
