# Follow Security by Design Principles

Get to know Security by Design Principles. Build a common understanding within the team on how to implement these principles and integrate them into your development process.

## Benefits

- The team has a common language and understanding of security principles.
- Leverage proven security strategies to improve the resilience of your system.
- Relevant security considerations are performed.
- Security flaws can be discovered or prevented early.

## Assessment

- Show the principles you use and explain them.
- Show (in code) how you implemented the principles.

## Examples

For example, *Fail Securely* means whenever an error occurs in your software do not leak internal information and return into a state where the system is good to serve the next request.

When implementing this principle:

- Disable all debug output in production that is useful during development.
- Configure middleware like application servers to not return version numbers, stacktrace, and technical error messages.
- When receiving a malformed HTTP request, reject it rather than guessing the intended content.

## Further Readings

- TODO
- [Secure the Weakest Link: Medium Page 5]()
- https://medium.com/ouspg/security-design-with-principles-a8c045765b93
- https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf
- [page 14 (german)](https://se-rwth.de/phdtheses/Diss-Hermerschmidt-Agile-Modellgetriebene-Entwicklung-von-Software-Security-and-Privacy.pdf)
