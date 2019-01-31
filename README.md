# BLUEPERF - Performance Analysis Application Repository

This is the repository for Public Cloud Environment Performance Analysis Application.
It contains microservices application for fictional Airline Company "Acme Air".  Currently, Java homogeneous microservices are developed & maintained.
These are repositories that should be used to deploy Acme Air Applications:
 - acmeair-authservice-java
 - acmeair-bookingservice-java
 - acmeair-customerservice-java
 - acmeair-flightservice-java
 - acmeair-mainservice-java
 
Helper scripts make it easier to deploy application on IBM Cloud Kubernetes Service (IKS).  It will deploy Acme Air without GUI mode (acmeair-mainservice-java will not be deployed).
To use Acme Air with GUI, please see the README in acmeair-mainservice-java

If simple single application is needed to avoid additional overhead of network latencies and multiple application interaction, use acmeair-flightservice-java for its testing.
 - Note: Set environment variable SECURE_SERVICE_CALLS = false to disable authentication.



