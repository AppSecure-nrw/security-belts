# Follow Security by Design Principles

## Activities

- Get to know the following Security by Design Principles:
  - [Least Privilege](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#least-privilege)
  - [Defense in Depth](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#defense-in-depth)
  - [Fail Securely](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#fail-securely)
  - [No Security by Obscurity](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#no-security-by-obscurity)
  - [Detect and Record](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#detect-and-record)
  - [Don't Trust](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#dont-trust)
  - [Keep It Simple](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#keep-it-simple)
  - [Secure the Weakest Link](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#secure-the-weakest-link)
  - [Decomposition](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#decomposition)
  - [Separation of Privilege](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#separation-of-privilege)
  - [Use Secure Defaults](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#use-secure-defaults)
  - [Don't Reinvent the Wheel](https://github.com/AppSecure-nrw/security-belts/wiki/Security-by-Design-Principles#dont-reinvent-the-wheel)
- Build a common understanding within the team on how to implement these principles and integrate them into your development process.

## Benefits

- The team has a common language and understanding of security principles.
- Leverage proven security strategies to improve the resilience of your system.
- Relevant security considerations are performed.
- Security flaws can be discovered or prevented already in the design.

## Assessment

- Explain the different Security by Design Principles. Each member of the team shall explain at least one principle.
- Show (in code) how your implementation follows the principles.

## Examples

For example, *Fail Securely* means whenever an error occurs in your software do not leak internal information and return into a state where the system is good to serve the next request.

When implementing this principle:

- Disable all debug output in production that is useful during development.
- Configure middleware like application servers to not return version numbers, stacktrace, and technical error messages.
- When receiving a malformed HTTP request, reject it rather than guessing the intended content.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Security Code Review](../yellow/security-code-review.md)

## Further Readings

- [Security design with principles](https://medium.com/ouspg/security-design-with-principles-a8c045765b93)
- [MITRE - Cyber Resiliency Design Principles](https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf)
- [Agile Modellgetriebene Entwicklung von Software Security & Privacy - page 14 (german)](https://se-rwth.de/phdtheses/Diss-Hermerschmidt-Agile-Modellgetriebene-Entwicklung-von-Software-Security-and-Privacy.pdf)
