## Introducing: OpenFGA 👋

[![Join our community](https://img.shields.io/badge/slack-cncf_%23openfga-40abb8.svg?logo=slack)](https://openfga.dev/community)
[![Twitter](https://img.shields.io/twitter/follow/openfga?color=%23179CF0&logo=twitter&style=flat-square "@openfga on Twitter")](https://twitter.com/openfga)
[![CLOMonitor](https://img.shields.io/endpoint?url=https://clomonitor.io/api/projects/cncf/openfga/badge)](https://clomonitor.io/projects/cncf/openfga)
[![OpenFGA YouTube Channel](https://img.shields.io/badge/YouTube-Subscribe-red?style=flat&logo=youtube)](https://www.youtube.com/@OpenFGA)

OpenFGA is a high performance and flexible authorization/permission engine built for developers and inspired by [Google Zanzibar](https://research.google/pubs/pub48190/). It incorporates powerful [Relationship-Based Access Control (ReBAC)](https://en.wikipedia.org/wiki/Relationship-based_access_control) and [Attribute Based Access Control (ABAC)](https://en.wikipedia.org/wiki/Attribute-based_access_control) concepts with a domain-specific language that makes it easy to craft authorization and permission solutions that can grow and evolve to any use case, at any scale.

OpenFGA was originally developed by Auth0/Okta, and [donated to the Cloud Native Computing Foundation](https://www.cncf.io/projects/openfga/) on September 14, 2022, and is currently at the Sandbox level of graduation.

---
### 🙋‍♀️ What's OpenFGA all about?

This community wants to solve authorization for everyone, regardless of the scale or complexity required for any given piece of software, and we think OpenFGA's design is the way to do it. In particular, the *fine-grained authorization* approach which OpenFGA incorporates is becoming an increasingly critical element of access control in software:

* **Collaboration and social features are things users expect**. These features range from the ‘Share’ button where users proactively grant specific permissions to a set of users for a specific resource, to ‘Request Access’ workflows that allows users to reactively grant access on demand. These features are useful both for business-related assets such as documents or project boards, as well as social sharing of personal content like photo albums, social media posts, and even IoT devices. OpenFGA makes these scenarios easy to build and govern.

* **Traditional Role-Based Access Control (RBAC) solutions become difficult to administer and scale**, but fine-grained approaches like OpenFGA can create authorization models that are still easy to understand and visualize for complex authorization patterns.

* **Security, compliance, and privacy are mandatory problems** to solve for any software application from day one, and authorization is a big part of any solution. In fact, the [top 2021 OWASP risk is broken access control](https://owasp.org/Top10/).

---
### 💡Why is it important to centralize authorization?

Centralizing your authorization logic and decisions into a single service that has the flexibility to handle use cases across your different products gives you distinct advantages:

* **Deliver faster**: You’ll be able to ship features and products faster, as the system should be easily extensible to new requirements.
* **Simplify authorization policy auditing**: Explicit authorization rules are easier to audit by internal and external parties.
* **Simplify access control auditing**: The authorization service generates logs for all operations out-of-the-box, both reads and writes
* **Lower operational costs**: Having a single authorization system makes it simpler to manage.
* **Simpler to switch teams**:  Developers can use the same authorization concepts and APIs regardless of the team they work on.

---
### 🛠️ Developer Tooling

OpenFGA has high quality developer tooling, including:

- SDKs for [Go](https://github.com/openfga/go-sdk), [JavaScript](https://github.com/openfga/js-sdk), [.NET](https://github.com/openfga/dotnet-sdk), [Python](https://github.com/openfga/python-sdk), [Java](https://github.com/openfga/java-sdk).
- A [CLI](https://github.com/openfga/cli) to operate an OpenFGA server, import/export models and tuples and test models.
- A [Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=openfga.openfga-vscode) with syntax coloring and validation for models and tests.
- A [Helm Chart](https://github.com/openfga/helm-charts) to simplify deployment in Kubernetes clusters.
- GitHub Actions for [testing](https://github.com/marketplace/actions/openfga-model-testing-action) and [deploying](https://github.com/marketplace/actions/openfga-model-deploy-action) models through CI/CD

---
### 👩‍💻 Useful resources

* **Contributing**: Read this [CONTRIBUTING.md](https://github.com/openfga/.github/blob/main/CONTRIBUTING.md) guide for an outline for interacting with the OpenFGA community and its governance structure, as well as details how to write, test, and submit code changes.
* **Documentation**: Read about OpenFGA at the [project's website and documentation repository, https://openfga.dev](https://openfga.dev).
* **Community**: Join the [OpenFGA Community](https://openfga.dev/community) in the CNCF Slack or [GitHub Discussions](https://github.com/orgs/openfga/discussions).
* **Community Projects**: We're building amazing things with OpenFGA. Check them out in our [Community Projects](https://github.com/openfga/community#community-projects) list.
