---
seo:
  title: Google Feedback Loop (Spam Complaints)
  description: Google Feedback Loop (Spam Complaints)
  keywords: 
title: Google Feedback Loop (Spam Complaints)
group: delivery-optimization
weight: 0
layout: page
zendesk_id: 202604713
navigation:
  show: true
---

SendGrid does automatically suppress any spam complaint address reported through traditional feedback loops. However, some webmail providers, notably Gmail, do not provide a traditional feedback loop out of privacy concerns. Rather, they provide an anonymous, aggregate report directly to us about concerning senders.

This matters to you because senders with high spam complaints will often see their mail broadly throttled or blocked during future email campaigns if this remains an unresolved issue. Since Gmail’s reporting is anonymous, you won’t know specifically who flagged your mail as spam, and you likely won’t know this is an issue until SendGrid reaches out to you.

If you receive a report from us about Google spam complaints, or even from traditional feedback loops, we have a few best practices to help you resolve the issue:

1. If you don’t have opt-in, don’t send any more to those lists. It’s against our [Terms of Service](https://sendgrid.com/policies/email/), and considered to be [spam](https://www.spamhaus.org/consumer/definition/) anyway by the email community.
2. If your list is opt-in, track who’s actually engaging with your email, as measured by click and open tracking. Many customers have this data in their own CRM, or you may prefer to use our own Click and Open Tracking apps, coupled with the [Event Webhook]({{root_url}}/for-developers/tracking-events/getting-started-event-webhook/) to consume this data. For recipients who don’t engage with your email, after a certain period of time that you determine to be appropriate based on your customer base and business model, stop sending to them. This tends to be a period between a few weeks and 3 months, depending on your sending frequency.


<call-out-link linktext="EXPERT INSIGHTS" img="/img/expert-insights-promo2.png" link="https://sendgrid.com/solutions/expert-insights/">


### Looking for more visibility into your email performance?


Send better email with Expert Insights. Our detailed monthly reports will enable you to understand your email reputation and recipient engagement and repair issues with expert how-to steps.


</call-out-link>



If you receive a report from us about spam complaints, use this as an opportunity to implement better list acquisition and maintenance.


<call-out>

Looking for customized expert advice to improve your email program? Our team of email experts can help you create a plan to ensure you're optimizing your email delivery and engagement, and avoiding future issues. Learn more on our [Expert Services](https://sendgrid.com/solutions/expert-services/?utm_source=docs) page.

</call-out>
