## Hi there 👋

CI/CD in general is a powerful tool. Actions adds to this by extracting common use-cases into their own repositories so that their functionality can be shared across projects.

Metaverse Standards Actions aims to encourage the usage of GitHub Actions throughout Metaverse Standards repositories while conforming to security best practices.

### Metaverse Stanrdards Actions Security Best Practice

- All Third-Party Actions used by the Metaverse Standards Forum should be referenced from this organisation. See [Using Third Party Actions](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#using-third-party-actions)
- If a new Third Party Action is needed. It must be audited and forked into this organisation, **especially** if used in private repositories.
- Any secrets or tokens must be scoped appropriately to a repository using a bot account. See [Using Secrets, Use credentials that are minimally scoped](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#using-secrets)
- If in doubt always refer to the [Security Hardnening For Github Actions Guide](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions)
- If you usage of Actions are not covered by the Security Hardening Guide, make contact with an Administrator of the Metaverse Standards Forum GitHub Organisation's for further guidance before continuing
