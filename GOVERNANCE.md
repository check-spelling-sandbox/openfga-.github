## Overview

This document outlines a set of policies in order to provide a level playing field and open process for contributors to join the OpenFGA project.

Governance activities are currently performed manually. In the future we might use [terraform](https://www.terraform.io/) or similar technology to automate tasks, but we're currently a small team and iterating quickly - for now it makes sense to do things in a way that doesn't scale.

### License

For information on the project's license, see the [LICENSE.md](https://github.com/openfga/openfga/blob/main/LICENSE).

### Copyright

For copyright and trademark information, see [Trademark Usage](https://www.linuxfoundation.org/legal/trademark-usage)

## Roles and Responsibilities

OpenFGA uses a Teams concept to divide up roles and responsibilities. Teams are defined in GitHub.

### Teams
Currently there are three main teams:

* Core
* Product
* Contributors

#### Core

The @core team is concerned with the codebase and technical implementation details for the product. 

*Responsibilities include:*
- review RFCs or delegate their review to a more relevant team
- reach consensus and usher each RFC through the resolution process
- collaborate with @community to collect feedback for RFCs
- ensure RFCs are acceptable to maintain
- govern OpenFGA repos
- PR review and merging
- curating releases

Secondary priorities involve collaborating with @product on the roadmap, user research, and iterating on the product experience.

#### Product

The @product team is concerned with iterating on the product itself. They govern the product roadmap, product marketing, design principles, user research and subject matter expertise, and other product concerns.

*Responsibilities include:*
- develop and iterate on the governance model
- review RFCs or delegate their review to a more relevant team
- maintain OpenFGA's design principles through the RFC review process
- clarify OpenFGA's design principles over time
- collaborate with @core to develop a roadmap that fits OpenFGA's design principles
- collaborate with @core and @contributors on user research
- iterate on the product experience

#### Contributors

The @contributors team exists to keep track of and grant certain privileges to anyone who contributes to the product.

### Joining a team

Anyone can become a member of @contributors team: reach out to anyone on the @core or @product teams via any of the channels in the [Support](#support) section with a request to join and they will make the change.

From there, when someone has a will to be more involved in any of the other teams' responsibilities, and have made significant enough contributions to the product, being promoted to being a member of the @core or @product teams requires making a request and receiving a majority vote from those teams. For more info, see the [Governance-Related Policies and Procedures](#governance-related-policies-and-procedures) section.

### Leaving a team

Should someone wish to leave a team, they can reach out to a member of the Core team via any of the channels in the [Support](#support) section with a request.

### Creating a new team

As the product grows, it will become more useful to further subdivide the teams. This will enable the project to assign code coverage, streamline conversations, and create subject-matter-expertise where possible. If you have an idea for a new team, start a [GitHub Discussion](https://github.com/orgs/openfga/discussions) in order for the community to track it and gain alignment.

## Governance-Related Policies and Procedures

Decisions regarding any of the processes or policies outlined in this Governance model are reached through consensus among the team members through a 66%+ supermajority unless otherwise expressly stated through the team's own processes.

Voting can be expressed through pull request review, leaving a comment, or through some other form of record - ideally permanent.

Teams are not required to have designated leaders. Teams may choose to designate a leader and define their role and responsibilities through a vote amongst the team.

### Amending the Governance Model

Nothing here is set in stone. Please improve this document as necessary. Pull requests to this process (`GOVERNANCE.md`) will be reviewed by the @core and @product teams.

## Contributing

We welcome contributions from the broader community! If you would like to contribute to OpenFGA, take a look at the [CONTRIBUTING.md](https://github.com/openfga/.github/blob/main/CONTRIBUTING.md) guide.

## Support

If you have any questions, feedback, or ideas for OpenFGA, we would love to hear from you. Here are a few ways you can get in touch:

* Join the [OpenFGA Community](https://openfga.dev/community) in the CNCF Slack or [GitHub Discussions](https://github.com/orgs/openfga/discussions).
- Reach out to us [on Twitter](https://twitter.com/OpenFGA)
- Send an email to [contact@openfga.dev](mailto:contact@openfga.dev)
