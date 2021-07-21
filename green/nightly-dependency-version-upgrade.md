# Nightly Dependency Version Upgrade

## Activities

- Perform nightly upgrades of all dependencies (e.g., libraries) within the build process of your software.
- Validate the latest dependency updates and upgrade the new dependencies in the repository after successful build and test process.

## Benefits

- All software components are up-to-date and use dependencies with all available fixes for publicly known vulnerabilities.
- Immediate benefit of bugfixes within the dependencies.
- Early notification of deprecated functionality used by your software.

## Assessment

- Show results of nightly upgrade process including successful and failed upgrades.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Test of Components Regarding Known Vulnerabilities](../yellow/test-of-components-regarding-known-vulnerabilities.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/03_security-belt-orange.svg" width="25" />](#) [Nightly Test of Libraries With Known Vulnerabilities](../orange/nightly-test-of-libraries-with-known-vulnerabilities.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/04_security-belt-green.svg" width="25" />](#) [Test of Container Images Regarding Known Vulnerabilities](../green/test-of-container-images-regarding-known-vulnerabilities.md)

## Further Readings

- Tool: [Dependabot](https://dependabot.com/)
- Literature: [OWASP Top Ten: 9. Using Components with Known Vulnerabilities](https://owasp.org/www-project-top-ten/2017/A9_2017-Using_Components_with_Known_Vulnerabilities)
