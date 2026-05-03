## Checklist

**ATTENTION** _Please follow this check list to ensure that you've followed all
items before opening this PR You can check the items by adding an 'x' between
the brackets, like this: `[x]`_

- [ ] Have I enforced proper authentication and authorisation for all views, endpoints, and data objects?

- [ ] Are all user inputs validated and sanitised on the server side, and are outputs safely escaped before rendering?

- [ ] Am I using the Django ORM (no raw or concatenated SQL) and avoiding injection risks?

- [ ] Is CSRF protection enabled for all forms and views?

- [ ] Are secrets kept out of the code?

- [ ] Is the application running with DEBUG=False in the production environment?

- [ ] Are security settings such as HSTS, SSL redirects, and allowed hosts properly configured?

- [ ] Is sensitive data properly protected, with encryption and secure key management (e.g., using a key management service instead of storing secrets directly in environment variables)?

- [ ] Are uploaded files validated, safely stored, and not executable or served directly?

- [ ] Have I checked dependencies for known vulnerabilities and avoided unsafe modules?

- [ ] Are errors handled gracefully without exposing details, and are logs free of secrets or PII?