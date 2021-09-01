# Logging of Security Events

## Activities

- Implement logging of security relevant events.

The following events tend to be security relevant:
- successful/failed login/logout
- creation, change, and deletion of users
- errors during input validation and output creation
- exceptions and errors with security in their name
- transactions of value (e.g., financial transactions, costly operations)
- :unicorn: (special things of your application)

## Benefits

- Security incident analysis takes significantly less time with proper security events, such that an attack can be stopped before the attacker reaches his goal.

## Assessment

- Show which events are logged.
- Show a test for one event logging.

## Further Readings

- Literature: [Logging CheatSheet](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)
- Literature: [How attacker can exploit logger](https://owasp.org/www-community/attacks/Log_Injection)
- Tool: [OWASP AppSensor](http://www.appsensor.org)

<p align="right"><a href="https://www.surveymonkey.de/r/MNWNVRB">Send Feedback</a></p>
