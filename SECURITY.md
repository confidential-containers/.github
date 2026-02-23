# Security Policy

## Reporting a Vulnerability

Please do not use public issues to report security vulnerabilities.

To report a vulnerability please select the security tab of the repo and
click `Report a vulnerability`. 
This will create a private GitHub issue that repository maintainers,
security managers, and the steering committee will have access to.

Private GitHub issues provide a structured protocol for addressing security concerns.
The aforementioned parties will use this mechanism to triage the issue in collaboration
with the author of the issue.
If the issue is accepted as a CVE, security managers will make sure that the author
has provided correct information and that an accurate severity score is calculated.
A CVE number will be issued via GitHub.
A private branch may be used to resolve the issue.
Once the issue is fixed, the CVE should be published.
The security managers should share the CVE with the broader community at this point.
Prior to publication, the vulnerability is considered embargoed and information
about it should be shared on a need-to-know basis.

The CoCo community aspires to follow the security best practices defined by OpenSSF,
including responding to vulnerability reports within 14 days.

## Supported Versions

Please note that the CoCo community analyzes security issues only in the the most recent release.

CoCo has not released any long term supported versions yet.

Patches will not be backported to earlier versions.

Patches will be released as point versions of the current version, e.g. releasing 0.8.1 to correct
v0.8, or will be patched in the next release, e.g. v0.9.


## Security Bulletins

CoCo announces security issues and their fixes in the release notes of the patching version.
For example, a vulnerability discovered in v0.8 and fixed in v0.8.1 will be announced in the
release notes for v0.8.1.

# Security Managers

Confidential Containers security managers, along with the Steering Committee, and the maintainers
of individual repos are expected to engage with security issues.
More information about these roles is available in the Confidential Containers
[governance document](https://github.com/confidential-containers/confidential-containers/blob/main/governance.md).
