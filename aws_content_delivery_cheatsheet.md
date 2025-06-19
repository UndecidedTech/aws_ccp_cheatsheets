2025-06-18
AWS Content Delivery and DNS Services

This category of AWS services includes services for caching
content aroudn the world and providing intelligent Domain Name
System (DNS) services for your applications

Services

| AWS Service | Primary Use Case | When to Use                                                                                                                                                                                              |
|-------------|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Route 53    | DNS              | allows you to register domain names, (DNS) translates name to IP addresses, health checking, traffic flow (send users to best endpoint), failover (automatically change domain endpoint if system fails) |
| CloudFront  | CDN              | content deliver network (CDN) that allows you to store (cache) your content at "edge locations" located around the world, also provides protection against DDoS attacks                                  |



Amazon Route 53: is the AWS Domain Name Service, provides 3 main functions:
    * Domain registration - Route 53 allows you to register domain names
    * Domain Name Service (DNS) - Route 53 translates name to IP addresses
    using a global network of authoritative DNS servers
    * Health Checking - Route 53 sends automated requests to your application to verify that it's reachable, available, and functional.

You can use any combination of these functions.

Benefits: 
    * Domain Registration
    * DNS services
    * Traffic Flow (send users to the best endpoint)
    * Health checking
    * DNS failover (automatically change domain endpoint if system fails)
    * Integrates with ELB, S3, and CloudFront as endpoints

Amazon CloudFront: a content delivery network (CDN) that allows you to store (cache)
your content at "edge locations" located around the world.

This allows customers to access content more quickly and provides security 
against DDoS attacks.

CloudFront can be used for data, videos, applications, and APIs.

Benefits:
    * Cache content at Edge location for fast distribution to customers.
    * Built-in Direct Denial of Service (DDoS) attack protection
    * Integrates with many AWS services (S3, EC2, ELB, Route 53, Lambda)

Origins and Distributions:
    * An origin of the files that the CDN will distribute.
    * Origins can be either an S3 bucket, an EC2 instance, an Elastic Load Balancer,
    or Route 53 --  can also be external (non-AWS)
    * To distrubute content with CloudFront you need to create a distribution.


