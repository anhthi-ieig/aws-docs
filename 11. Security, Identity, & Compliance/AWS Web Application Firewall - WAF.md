## AWS Web Application Firewall (WAF) - Filter malicious web traffic

- AWS WAF is `a web application firewall` that helps `protect web applications from attacks and exploits` by allowing you to `configure rules that allow, block, or monitor (count) web requests` based on conditions that you define

- These conditions include

  - IP addresses
  - HTTP headers
  - HTTP body
  - URI strings
  - SQL injection
  - Cross-site scripting

- When you `use AWS WAF on Amazon CloudFront`, `your rules run in all AWS Edge Locations`. This means security doesn’t come at the expense of performance. `Blocked requests are stopped before they reach your web servers`

- When you `use AWS WAF on regional services(ALB, API Gateway, AppSync)`, `your rules run in Region and can be used to protect internet-facing resources as well as internal resources`
