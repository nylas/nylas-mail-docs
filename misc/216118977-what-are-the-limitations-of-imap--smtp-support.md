# What are the limitations of IMAP / SMTP support?

To connect your email account to N1, your SMTP and IMAP servers must:

*   **Be accessible on the public internet**. Mail servers behind corporate proxies or on private networks are not supported, since N1 uses a sync engine hosted in the cloud.
*   **Authenticate over SSL**. Mail servers that do not support authentication or send usernames and passwords in plaintext are not supported. We do not plan to expand support for these configurations in the future. 












