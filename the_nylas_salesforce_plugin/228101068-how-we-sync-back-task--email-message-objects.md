# How we sync back Task & Email Message objects

When you “Sync an Opportunity with a Thread”, we display the opportunity details above the thread’s messages.

We currently can only sync with one Opportunity.

Once a thread is synced, we take each email message and create an individual email Task as well as an Email Message object on Salesforce associated with the opportunity.

The Tasks we create should show up in the Activity history of the Opportunity and look similar to email messages that you’d see if you bcc’d Salesforce.

Salesforce Lightning has extended support for HTML Email Message objects as well. To support the Lightning Interface we associate Email Message objects for each message on the thread.

If we see there are Salesforce Contact records on the thread that are not already associated with the synced Opportunity (via a Contact Role), we will attempt to link the Contacts to the Opportunity


