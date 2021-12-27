## AWS Edge Locations

- Edge Location is `where end users access services located at AWS`. They `closer to end-users than Regions or Availability Zones`, often in major cities, so responses can be fast and snappy

## Use cases

- CloudFront

  - A CDN service that `caches content in edge locations`
  - Content can be `served directly from the cache`, so it gets to users faster

- Route 53

  - A managed DNS service with `name servers spread across Amazon’s edge locations`
  - DNS `responses come directly from the edge locations`, so they’re as fast as possible

- Web Application Firewall and AWS

  - Provide `a firewall and DDoS protection`
  - `Filter traffic in edge locations` so malicious or unwanted traffic can be discarded

- AWS Global Accelerator
