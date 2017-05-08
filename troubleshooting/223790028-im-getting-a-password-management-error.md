# I'm getting a Password Management Error

Here at Nylas, we take security very seriously. That's why we store your Nylas ID password in your computer's keyring -- a database that encrypts your passwords on disk using your system's login password.

**Why am I getting a Password Management Error?**

If you are getting a Password Management Error, it's because something went wrong when we tried to access your computer's keyring. This could mean that you don't have a keyring installed on your computer, or you are using N1 from a user account that doesn't have permission to access the keyring. Make sure that you aren't on a "guest" user account or any user account without a password.


**I'm not on a guest account, but I'm running on Linux**

If you are getting this error on Linux, and aren't on a guest account, it's likely that you don't have the proper keyring installed. Run `sudo apt-get install libgnome-keyring-dev` to make sure that you do. (Or `sudo yum install libgnome-keyring-devel` if you are using a Red Hat system.)

**I'm on Windows and I have a LOT of accounts**

Windows has sever restrictions on the amount of data we can securely store. Since we store secure data for each email account you have, we've found once you link more than a dozen or so email accounts, we can approach the limit of the Windows password manager.

**Thanks, but I'm still getting the error**

If you still need help, we recommend you [contact support](mailto:support@nylas.com) with a detailed description of the issue you are experiencing.



