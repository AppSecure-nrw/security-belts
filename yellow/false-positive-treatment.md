# False Positive Treatment

## Activities

- Suppress false positives so that they will not show up on the next tests again.
- This will help you to see the real vulnerabilities (not hidden among many many false positives anymore).

For suppressions:
- Document a reasonable justification (use the locality principle: as close to the code as possible).
    - Note on reasonable: Determine how much information your company needs, maybe it could be interesting for assessments as well?
- Review your suppressions in a team (use [help](security-consulting-on-request.md) if necessary).

## Benefits

- Easier to spot real positives, as the false positives will be automatically ignored.
- Higher motivation to look at the found results as same false positives findings are not checked over and over.

## Assessment

- Provide your false positive list.
- Provide your justifications for your false positives and explain some of them.

## Related Activities

- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Security Consulting on Request](../yellow/security-consulting-on-request.md)
- [<img src="https://raw.githubusercontent.com/AppSecure-nrw/security-belts/assets/belt-img/02_security-belt-yellow.svg" width="25" />](#) [Security Code Review](../yellow/security-code-review.md)

<p align="right"><a href="https://www.surveymonkey.de/r/MNWNVRB">Send Feedback</a></p>
