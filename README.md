# apig-s3-proxy

Incomplete Cloudformation implementation based on this AWS walkthrough: [Create an API as an Amazon S3 Proxy](http://docs.aws.amazon.com/apigateway/latest/developerguide/integrating-api-with-aws-services-s3.html)

The walkthrough describes how API Gateway can be used as  a proxy to S3.

The `cf.yml` template just implements the `/` `GET` method based on the swagger definition (which I converted to YAML).
