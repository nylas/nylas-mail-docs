<div id="container">

# How we sync back Task & Email Message objects

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">When you “Sync an Opportunity with a Thread”, we display the opportunity details above the thread’s messages.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">We currently can only sync with one Opportunity.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">Once a thread is synced, we take each email message and create an individual email Task as well as an Email Message object on Salesforce associated with the opportunity.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">The Tasks we create should show up in the Activity history of the Opportunity and look similar to email messages that you’d see if you bcc’d Salesforce.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">Salesforce Lightning has extended support for HTML Email Message objects as well. To support the Lightning Interface we associate Email Message objects for each message on the thread.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">If we see there are Salesforce Contact records on the thread that are not already associated with the synced Opportunity (via a Contact Role), we will attempt to link the Contacts to the Opportunity</span></div>

</div>
