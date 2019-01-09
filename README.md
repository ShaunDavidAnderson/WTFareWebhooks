# WTFareWebhooks
Figuring out webhooks

## Process so far
- Read https://developer.github.com/webhooks/: this goes over some basics of the actual process of subscribing to events
- Implication that the nuts and bolts of Github Webhooks include some sort of MQ / Queuing system PubSsub behind the scenes.
- Find a Webhook Receiver: https://webhook.site/
- This site enables you to recieve data from your Github Webhook as a test
- Supposedly the data sent by Github, or any other Webhook is some sort of Post
- See first 2 messages transmitted from Github subscriptions (Selection was ALL)
- Upload Pdf print of Output on Webhook.site
- Rerun demo for my understanding


### Questions so far
- Can the above be achieved using Postman in some way.
- HTH can you build a Webhook publisher/poster? Azure Service Bus? RabbitMQ? Redis?
