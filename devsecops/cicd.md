# CICD Security

* https://engineering.mercari.com/en/blog/entry/20220203-defense-against-novel-threats-redesigning-ci-at-mercari/
* https://www.cidersecurity.io/top-10-cicd-security-risks/
* https://engineering.mercari.com/en/blog/entry/20220519-terraform-ci-code-execution-restrictions/
* https://hackernoon.com/what-is-gitops-and-why-is-it-almost-useless-part-2

## Tools

* https://github.com/kudelskisecurity/youshallnotpass
* https://boostsecurityio.github.io/lotp/
* https://boostsecurity.io/blog/unveiling-poutine-an-open-source-build-pipelines-security-scanner

## Image Lifecycle

* Image Validation recommended by azure: https://docs.microsoft.com/en-us/azure/security/security-recommendations-azure-marketplace-images
* Building + Checks + Registry: https://quay.io/
* https://medium.com/sharenowtech/serverless-gitlab-runner-builds-on-lambda-ded4b24b3c4f
* Minimized and hardened docker builds: https://github.com/docker-slim/docker-slim
* Minimal build env for verifiable builds: https://bootstrappable.org/
* Image Scanning on admission: https://sysdig.com/blog/image-scanning-admission-controller/
* https://github.com/estahn/k8s-image-swapper/
* https://www.slim.ai/

### Image/Build Footprinting

* https://github.com/srcclr/build-inspector
* Distroless Images: https://github.com/witchery-project/witchery
* https://github.com/chainguard-dev/apko
* https://www.chainguard.dev/unchained/move-over-dockerfiles-the-new-way-to-craft-containers

## Analysis

* Learn which file is on which layer, how much size one layer has, ... https://github.com/wagoodman/dive

## Vulns / Hacking

* https://about.gitlab.com/blog/2018/10/01/events-api-security-issue/
* SSRF to Root: https://hackerone.com/reports/341876
* Jenkins Vulns: https://www.zdnet.com/google-amp/article/thousands-of-jenkins-servers-will-let-anonymous-users-become-admins/
* Homebrew compromise: https://medium.com/@vesirin/how-i-gained-commit-access-to-homebrew-in-30-minutes-2ae314df03ab
* https://justi.cz/security/2018/08/28/packagist-org-rce.html
* https://blog.orange.tw/2019/02/abusing-meta-programming-for-unauthenticated-rce.html
* https://speakerdeck.com/rung/cd-pipeline
* https://research.nccgroup.com/2022/01/13/10-real-world-stories-of-how-weve-compromised-ci-cd-pipelines/
* https://medium.com/cider-sec/exploiting-jenkins-build-authorization-22bf72926072
* https://www.synacktiv.com/en/publications/cicd-secrets-extraction-tips-and-tricks.html
* https://github.com/CycodeLabs/raven - cicd security scanner

## Registry

* Docker registry authorization frontend: https://github.com/SUSE/Portus

## Case Studies & Examples

* https://sandrino.dev/blog/github-actions-deploy-auth0
* https://alexander.holbreich.org/gitops-journey

## RBAC

* https://www.cidersecurity.io/blog/research/optimizing-ci-cd-credential-hygiene-a-comparison-of-ci-cd-solutions/
