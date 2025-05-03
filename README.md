Demo for Kafka connect 

Common Issues:
- Value document is missing or CDC operation is not a string : wrong converting on mongodb side
- Could not create write model: postgresql cdc not set up in mongodb change.data.capture.handler
- make sure that postgresql is configured for replication and has the pgoutput plugin
