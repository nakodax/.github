# Security policy

NakodaX builds security software, so we take reports seriously.

## Reporting a vulnerability

Please do not open a public issue for a security problem. Email **info@nakodax.com** with the subject "Security report" and include:

- what you found and where
- steps to reproduce it
- the version of the tool or release affected

You can also use [GitHub private vulnerability reporting](https://docs.github.com/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) on this repository's Security tab.

## Verifying our releases

Release binaries are signed with Sigstore cosign and each release includes a `SHA256SUMS` file. See the repository README for the verification command.

More about how NakodaX protects content: [nakodax.com/security](https://nakodax.com/security).
