# event-streaming-architecture-golang-kubernetes

Intended to be an implementation of Pub/Sub which has a unidirectional flow of data.

Data flows from Publishers into Consumers without the consumers ever having to publish anything themselves. This means that we have a lot more control when it comes to rate limiting all potential publishers.
