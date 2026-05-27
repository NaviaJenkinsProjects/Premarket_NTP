# Web ReKYC Test

Selenium, Cucumber, and JUnit automation project for the Navia web ReKYC test flow.

## Run

```bash
mvn test
```

## Configuration

The existing defaults are preserved, so the current flow runs without extra setup. To run against another ReKYC test environment, pass values with Maven system properties:

```bash
mvn test -Drekyc.login.url=https://web.navia.co.in/login.php -Drekyc.home.url=https://web.navia.co.in/index.php
```

Supported values:

- `rekyc.login.url`
- `rekyc.home.url`
- `rekyc.client.code`
- `rekyc.password`
- `rekyc.otp.mailbox`
- `rekyc.otp.provider.url`
- `rekyc.upi.id`
