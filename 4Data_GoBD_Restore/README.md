# 4Data GOBD Restore
----

This pack provides a framework with some useful routes and pipelines to enable customers to store and replay long-term storage data to andn from S3.


## Requirements Section

Before you begin, ensure that you have met the following requirements:

* S3 bucket configured for long-term storage configured as a destination in Cribl
* S3 bucket configured for long-term storage configured as a collector in Cribl
* Splunk configured as a destination in Cribl

## Using The Pack

To use this Pack, follow these steps:

1. Configure a route outside of the pack, using the filter from the first route of the pack, selecting the pack as the pipeline and S3 as the destination
2. Configure a route outside of the pack, using the filter from the second route of the pack, selecting the pack as the pipeline and Splunk as the destination

## Release Notes

### Version 1.0.0 - 2023-03-07
In this release, we have added a number of great features. We've goat you covered!

## Contact
To contact us please dont hesitate to either create an Issue in our github. Or contact us directly via our contact form on https://4datasolutions.com/contact 
