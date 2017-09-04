# Enterprise Registry

An enterprise registry with native integration with Kubernetes.  
A turn-key solution to regulation of image distribution over your
infrastructure.

An impressive set of features:

- Fine-Grained Access Controls
  - Restrict Roles to certain:
    - Repository
    - Image
    - Tag
    - Sha
    Make changes to policy and have it apply in seconds
  - Blacklisting/Whitelisting of all the things
  - Integration with Kubernetes RBAC
  - Image Signing support/enforcement
    - Only trusted images from now on!
  - Extensible Blacklisting Support through webhooks
    - Image scanning
    - freeze deploys in trading hours
  - Audit trails
    What version of each program is deployed for every team, in real time!
  - Designed for High-Availability
  - Optionally enforce tag immutability
    - Set explicitly allowed mutable tags (latest)
  No more tags changing when least expected
  - Pull through cache of whitelisted images?... (By sha...)
  - Metrics! (Prometheus, others...)
  - Good logging
