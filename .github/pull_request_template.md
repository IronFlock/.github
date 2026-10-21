## What and why

<!-- What does this change do, and why is it needed? Link the issue if there is one. -->

## How it was tested

<!-- Tests added or run, manual checks. -->

## Security checklist

<!-- Tick what applies; explain anything you leave unticked that applies. -->

- [ ] No secrets, tokens, private keys or password hashes in code, configuration, test data, logs or console output (log the fact — present, length, id — never the value).
- [ ] A new secret is generated per installation, read from the secret store, and added to the rotation register — or this change adds no secret.
- [ ] Input from users, devices and other services is validated, and authorisation is checked on the server side.
- [ ] New or updated dependencies are needed, maintained, and have a compatible licence.
- [ ] Containers, compose files and charts: no new root user, privileges, capabilities or exposed ports — or the reason is stated above.
- [ ] Security-relevant behaviour (authentication, permissions, crypto, update paths) is covered by tests, including a negative case.
