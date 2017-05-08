<div id="container">

# What are the limitations of IMAP / SMTP support?

<div class="timeline-comment-wrapper js-comment-container">

<div id="issuecomment-162102445" class="comment previewable-edit timeline-comment js-comment js-task-list-container owner-comment current-user" data-body-version="2c4bbb9349b9d3fa995382d20a8c58be">

<div class="comment-content">

<div class="edit-comment-hide">

<div class="comment-body markdown-body markdown-format js-comment-body">

To connect your email account to N1, your SMTP and IMAP servers must:

*   **Be accessible on the public internet**. Mail servers behind corporate proxies or on private networks are not supported, since N1 uses a sync engine hosted in the cloud.
*   **Authenticate over SSL**. Mail servers that do not support authentication or send usernames and passwords in plaintext are not supported. We do not plan to expand support for these configurations in the future. 

</div>

</div>

</div>

</div>

</div>

</div>
