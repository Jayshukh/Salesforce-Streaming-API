# StreamingAPI

 * Streaming API uses the Bayeux protocol and the CometD messaging library.
 * PushTopic is an sObject that contains the criteria of events that you want to listen to, such as data changes for a particular object.
 * Define the criteria as a SOQL query in the PushTopic and specify the record operations to notify on (create, update, delete, and undelete).  
 * In addition to event criteria, a PushTopic represents the channel that client apps subscribe to.
