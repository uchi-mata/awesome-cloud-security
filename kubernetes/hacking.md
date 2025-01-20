# Hacking

* writeable hostpath volumes equal escape:
  * https://jackleadford.github.io/containers/2020/03/06/pvpost.html
  * https://blog.aquasec.com/kubernetes-security-pod-escape-log-mounts
* http://carnal0wnage.attackresearch.com/2019/01/kubernetes-master-post.html
* Dino Dai Zovi Basics: https://docs.google.com/presentation/d/10DxdTdJTcQuDjk4KHI0DEgK4tnJaRafZNbh5WWxoUeA/edit#slide=id.g3cbab6b963_0_9
* https://github.com/cncf/financial-user-group/tree/master/projects/k8s-threat-model
* Attack surface: https://github.com/gg-sec/kubernetes_security_slides/blob/master/Kubernetes%20Attack%20Surface.pdf
* breakout testing: https://www.jeffgeerling.com/blog/2020/everyone-might-be-cluster-admin-your-kubernetes-cluster
* Default ports and stuff:
  * https://github.com/kubernetes/kubernetes/issues/81023
  * https://github.com/mauilion/blackhat-2019
  * https://github.com/appsecco/attacking-and-auditing-docker-containers-and-kubernetes-clusters
  * https://hackernoon.com/capturing-all-the-flags-in-bsidessf-ctf-by-pwning-our-infrastructure-3570b99b4dd0
  * https://docs.google.com/document/d/1llfz5kgUoT9ARJnVQg9KQnwwUvogIxa9aIPC442EznE/edit
  * https://github.com/appsecco/attacking-and-auditing-docker-containers-and-kubernetes-clusters
  * https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/
* https://github.com/bgeesaman/kube-env-stealer
* https://github.com/madhuakula/kubernetes-goat
* https://blog.quarkslab.com/kdigger-a-context-discovery-tool-for-kubernetes.html
* https://static.sched.com/hosted_files/kccnceu2022/35/Trampoline%20Pods_%20Node%20to%20Admin%20PrivEsc%20Built%20Into%20Popular%20K8s%20Platforms.pptx.pdf - Privilege Escalation in cluster via pods w higher permissions on nodes
* Another K8s attack matrix, also not great: https://www.weave.works/blog/mitre-att-ck-matrix-for-kubernetes-tactics-techniques-explained-part-1
* https://github.com/Rolix44/Kubestroyer
* https://kubenomicon.com/
* kube-proxy: <https://raesene.github.io/blog/2025/01/18/Exploring-the-Kubernetes-API-Server-Proxy/>