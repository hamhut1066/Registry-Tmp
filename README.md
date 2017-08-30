# Cargo Cult Registry

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
  - Blacklisting/Whitelisting of all the things
  - Integration with Kubernetes RBAC
  - Image Signing support/enforcement
  - Extensible Blacklisting Support through webhooks
    - Image scanning
    - freeze deploys in trading hours
  - Audit trails
  - Designed for High-Availability
  - Optionally enforce tag immutability
  - Metrics!
