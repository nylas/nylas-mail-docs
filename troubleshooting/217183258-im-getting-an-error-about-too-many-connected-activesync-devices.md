# I'm getting an error about too many connected ActiveSync devices.

**Error message: "**Couldn't provision an ActiveSync device. This is typically because your Exchange administrator added a limit on the number of ActiveSync devices for a single account."

**Explanation: **Most Exchange servers have a limit on the number of ActiveSync devices a single user can register. The Nylas Sync Engine requires two ActiveSync devices to sync an email account. If you're getting this error message, it means that we weren't able to create those devices. You should get in touch with your system administrator and ask them to lift this limit or unlink old devices.


