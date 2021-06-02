# Follow Security by Design Principles

Get to know the following Security by Design Principles: 
- Least Privilege 
- Defense in Depth
- Fail securely (Fail-safe Defaults)
- No security by obscurity (Open Design // Kerckhoff's Principle)
- Detect and Record
- Don't trust (Be Reluctant to Trust //  Trust but verify)
- Keep It Simple
- Secure the Weakest Link
- Compartmentalization // Decomposition
- Separation of Privilege
- Use secure defaults
- Never invent security technology (Do not reinvent the wheel (e.g., do not build own Parser, Unparser, Crypto, Data languages, protocols)
- Don't trust your supply chain (Use mainstream technology like OpenAPI for REST)

Build a common understanding within the team on how to implement these principles and integrate them into your development process. 


## Benefits

- The team has a common language and understanding of security principles.
- Leverage proven security strategies to improve the resilience of your system.
- Relevant security considerations are performed.
- Security flaws can be discovered or prevented early.

## Assessment

- Explain the different Security by Design Principles. Each member of the team shall explain at least one principle. 
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
