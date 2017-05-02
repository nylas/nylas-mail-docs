<div id="container">

# Why does Nylas Mail store mail data?

Nylas Mail stores a local copy of your mailbox in order to provide fast and efficient access to messages, threads, and attachments. Mutable operations will update the local datastore immediately, and queue changes to sync back to your mail provider. This design is necessary in order to achieve the level of performance expected on modern developer platforms.

See more about how we protect mail data on our [security](https://nylas.com/security) page.

You can also request a much more detailed security white paper by contacting [security@nylas.com](mailto:security@nylas.com).

</div>
