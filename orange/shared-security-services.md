# Shared Security Services

Prefer shared security services and components over implementing security controls yourself. Challenge that these services perform well and secure and make deficiencies transparent.

## Risk

- Using security controls right is hard enough, don not try to implement them yourself.
- Security controls often have subtile details that lead to vulnerabilities if not done right.

## Assessment

- Show the shared security services in your architecture.
- What do you use for:
  - Crypto
  - Parser (like file upload validation)
  - Unparser (like HTML generation)
  - Authentication, authorization
  - Session management
