<div id="container">

# How we find existing Contact objects

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">When you load an email in Nylas N1, we look at all of the participants of that email. This is every email in the from, to, and cc sections. We then ask Salesforce if there are any matching Leads or Contacts for each of those emails.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">If we do not find a match, we prompt you to create a Lead or a Contact.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">If we find one match, we display the name and the corresponding Lead or Contact icon.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">It is possible to find more than one match. This happens if your Salesforce environment has duplicate records for a particular email. If you have duplication alerting turned on in your Salesforce environment, this should rarely happen. If it does, you may delete the duplicate record through the Nylas Salesforce plugin by clicking on the record then clicking “Delete this Lead or Contact”.</span></div>

<div><span class=" author-d-4z65zz66zl57z75zyiz66zfr2fz87zwz89znuj6z89zz78zusrsjz89zz78zhez86zz78z6iz122z1z122zz76z9kq5z66zz88zvz79zz75z">We do NOT lookup Leads or Contacts for any email address that you have connected to Nylas, nor any email address with the same non-common domain as any of your email addresses. For example, if I have “evan@nylas.com” and “evan@gmail.com” connected to Nylas, we will not load Contacts for “evan@gmail.com”, “evan@nylas.com”, “ben@nylas.com”, “joe@nylas.com”, “etc@nylas.com”.  However, we will search for Contacts using @gmail.com or other common email providers.</span></div>

</div>
