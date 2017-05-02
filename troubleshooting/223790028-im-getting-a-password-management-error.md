<div id="container">

# I'm getting a Password Management Error

<span class="wysiwyg-font-size-medium">Here at Nylas, we take security very seriously. That's why we store your Nylas ID password in your computer's keyring -- a database that encrypts your passwords on disk using your system's login password.</span>

<span class="wysiwyg-font-size-large">**Why am I getting a Password Management Error?**</span>

<span class="wysiwyg-font-size-medium"><span class="wysiwyg-font-size-medium">If you are getting a Password Management Error, it's because something went wrong when we tried to access your computer's keyring. This could mean that you don't have a keyring installed on your computer, or you are using N1 from a user account that doesn't have permission to access the keyring. Make sure that you aren't on a "guest" user account or any user account without a password.</span>
</span>

<span class="wysiwyg-font-size-large">**I'm not on a guest account, but I'm running on Linux**</span>

<span class="wysiwyg-font-size-medium">If you are getting this error on Linux, and aren't on a guest account, it's likely that you don't have the proper keyring installed. Run `sudo apt-get install libgnome-keyring-dev` to make sure that you do. (Or `sudo yum install libgnome-keyring-devel` if you are using a Red Hat system.)</span>

<span class="wysiwyg-font-size-large">**I'm on Windows and I have a LOT of accounts**</span>

Windows has sever restrictions on the amount of data we can securely store. Since we store secure data for each email account you have, we've found once you link more than a dozen or so email accounts, we can approach the limit of the Windows password manager.

<span class="wysiwyg-font-size-large">**Thanks, but I'm still getting the error**</span>

<span class="wysiwyg-font-size-medium"><span class="wysiwyg-font-size-medium">If you still need help, we recommend you [contact support](mailto:support@nylas.com) with a detailed description of the issue you are experiencing.</span>
</span>

</div>
