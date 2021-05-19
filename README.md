# Fluent Bit

This README documents the Fluent Bit integration as Nirmata add-on on Kubernetes clusters.

### What is Fluent Bit?
Fluent Bit is a completely open source Log Processor and Forwarder which allows you to collect any data like metrics and logs from different sources, enrich them with filters and send them to multiple destinations.



### How do I get set up?
1. Clone this repository or add its contents to your own private Git repository.
2. Create a Nirmata catalog application with a Git upstream and select the fluent-bit repository. You can optionally select the kustomization.
3. Edit the catalog application and select an add-on category (e.g. Logging). This is required to select the application as a add-on.
4. Update a Cluster Type, or create a new one, and select the Fluent-bit add-on application in the "Add-Ons" section. Ensure that the namespace you use is "**logging**" and environment is "logging-< cluster-name >"
5. Create clusters using the cluster type.
6. If addon is to be added to a running cluster, create a environemnt with namespace "**logging**" and choose this environment while deploying the application
6. Verify that the application is running.


### Who do I talk to?
For issues, contact support@nirmata.com
