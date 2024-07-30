# NexusIQTools

<!-- Badges Section -->
[![shield_gh-workflow-test]][link_gh-workflow-test]
[![shield_license]][license_file]
<!-- Add other badges or shields as appropriate -->

---

This Python script can be used to list applications, list organizations, and move applications to a new organization in Nexus IQ.  We built this script to enable us to move applications around in Nexus IQ easily using regular expressions to match application names.  The reason this script was needed is that we built a hierarchy of organizations in Nexus IQ to mimic our team structure, and we needed to move applications under this hierarchy.  Instead of using the GUI in Nexus IQ and moving one application at a time, this script would use regex to match the application name and then move all of those matches under an organization.
- [Usage](#usage)
- [Development](#development)
- [The Fine Print](#the-fine-print)

## Usage

Use this section (and any additional sub-sections) to explain how to use this project.

Include:
- Installation
- Configuration
- Execution

## Development

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## The Fine Print

Remember:

This project is part of the [Sonatype Nexus Community](https://github.com/sonatype-nexus-community) organization, which is not officially supported by Sonatype. Please review the latest pull requests, issues, and commits to understand this project's readiness for contribution and use.

* File suggestions and requests on this repo through GitHub Issues, so that the community can pitch in
* Use or contribute to this project according to your organization's policies and your own risk tolerance
* Don't file Sonatype support tickets related to this project— it won't reach the right people that way

Last but not least of all - have fun!

<!-- Links Section -->
[shield_gh-workflow-test]: https://img.shields.io/github/actions/workflow/status/sonatype-nexus-community/community-project-template/test.yml?branch=main&logo=GitHub&logoColor=white "build"
[shield_license]: https://img.shields.io/github/license/sonatype-nexus-community/community-project-template?logo=open%20source%20initiative&logoColor=white "license"

[link_gh-workflow-test]: https://github.com/sonatype-nexus-community/community-project-template/actions/workflows/test.yml?query=branch%3Amain
[license_file]: https://github.com/sonatype-nexus-community/community-project-template/blob/main/LICENSE
