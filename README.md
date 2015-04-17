# pd2jira

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Create JIRA tickets when a PagerDuty incident is triggered.  This is a small script that will translate PagerDuty's webhooks to become JIRA tickets.  You can host this yourself or deploy it to Heroku.  Either way, simply create a new webhook on your PagerDuty service(s) that points to the URL of the PHP script.  If using Heroku, you can fill out the necessary fields.  If you are hosting this yourself, you will need to populate the variables at the beginning of the PHP script.

Screenshot of the PagerDuty incident and corresponding note:  http://note.io/1EtD9jT

Screenshot of the JIRA ticket:  http://note.io/1EZTFLp

For a full walkthrough on setting up the integration, please visit the integration guide [here](http://www.pagerduty.com/docs/guides/jira-integration-guide/)