# Secret Mgmt

* Use AWS secret manager to put secrets into pods: https://github.com/mumoshu/aws-secret-operator
* Good overview of different approaches and how to do: https://www.threatstack.com/blog/cloud-security-best-practices-finding-securing-managing-secrets-part-2
* https://github.com/mozilla/sops - editor for secrets stored in KMSs
* Great approach: Use language-specific analysis for non-syntax strings first and then run secret detection on this:
  * https://hackernoon.com/modernizing-secrets-scanning-part-2-the-semantic-eureka

## Secret Management Solutions

* <https://github.com/tailscale/setec>

## Secret Scanners

* https://github.com/N0MoreSecr3ts/wraith
* https://github.com/dxa4481/truffleHog
* https://github.com/kootenpv/gittyleaks
* https://github.com/auth0/repo-supervisor
* https://github.com/michenriksen/gitrob
* https://github.com/techjacker/repo-security-scanner
* https://github.com/zricethezav/gitleaks
* https://github.com/Damian89/yataf
* https://github.com/nccgroup/ccs
* https://github.com/avito-tech/deepsecrets
* https://github.com/owenrumney/squealer/
* https://github.com/godaddy/tartufo
* https://github.com/Yelp/detect-secrets
* https://github.com/praetorian-inc/noseyparker

Benchmarking secret scanners:

* https://github.com/OWASP/wrongsecrets

### Using backend cloud service

* https://github.com/GitGuardian/ggshield

### Check validity of a found API key

* https://github.com/daffainfo/Key-Checker

### Continuous Monitoring

* https://github.com/hisxo/gitGraber
* DumpMonitor
* https://gitmonitor.com/

### Scan container images

* https://github.com/deepfence/SecretScanner

### Cli plugins

* https://github.com/ezekg/git-hound
* https://github.com/thoughtworks/talisman
* https://github.com/awslabs/git-secrets
* https://github.com/zricethezav/gitleaks

### String Search

* https://github.com/cloudify-cosmo/surch

### Gitlab-specific

* https://github.com/PaperMtn/gitlab-watchman

## K8s

* https://github.com/kubernetes-sigs/secrets-store-csi-driver
* https://medium.com/adevinta-tech-blog/managing-kubernetes-secrets-like-a-pro-93283fb4f06d

## AWS

* https://aws.amazon.com/blogs/mt/the-right-way-to-store-secrets-using-parameter-store/
* https://nedinthecloud.com/2020/08/29/use-hashicorp-vault-aws-engine-with-multiple-accounts/
