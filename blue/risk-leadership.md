# Risk Leadership

The economic benefit of fixing security vulnerabilities is not visible to the Product Owner, but that of features is.

## Activities

- Damage mitigation must be made visible to the Product Owner and management so that the value is seen in relation to a feature.
- Show the Product Owner which vulnerabilities you have fixed via the belt activities (i.e., [Treatment of Vulnerabilities With Severity High or Higher](../green/treatment-of-vulnerabilities-with-severity-high-or-higher.md)) and how much damage you have prevented.
- If vulnerabilities are not fixed, identify the potential risk damage and make this visible to the Product Owner. A simple approach would be:
  - Derive the risk damage from the *maximum damage to the application* multiplied with the *CVSS score* of the vulnerability.
  - The *maximum damage to the application* results from the criticality of the application in view of CIA (confidentiality, integrity, and availability). The estimation from the activity [Think about where the journey is going](../white/think-about-where-the-journey-is-going.md) is a good source here.
  - The *CVSS score* of a vulnerability can be calculated using a [CVSS calculator](https://www.first.org/cvss/calculator/3.0). If the vulnerability was found using a security tool, the tool may already provide the score. If the score is doubted, you can set the CVSS environment attack vector (MAV) correctly to get a more accurate result.
- To better identify the economic benefit of fixing vulnerabilities, it is helpful if the damage is expressed in a monetary currency for a certain period of time (e.g. loss of euros per hour).
- Define and introduce/implement risk mitigation measures.
- Risks that cannot be mitigated are reported to the risk owner / management.

## Benefits

- TODO

## Assessment

- TODO

## Examples

- TODO

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/01_security-belt-white.svg" width="25" />](#) [Think about where the journey is going](../white/think-about-where-the-journey-is-going.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/04_security-belt-green.svg" width="25" />](#) [Treatment of Vulnerabilities With Severity High or Higher](../green/treatment-of-vulnerabilities-with-severity-high-or-higher.md)

## Further Readings

- TODO

<p align="right"><a href="https://www.surveymonkey.de/r/MNWNVRB">Send Feedback</a></p>
