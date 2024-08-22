# 2023 Annual Report: SIG Node

## Current initiatives and Project Health

1. What work did the SIG do this year that should be highlighted?

<!--
   Some example items that might be worth highlighting:
   - Major KEP advancement
   - Important initiatives that aren't tracked via KEPs
   - Paying down significant tech debt
   - Governance and leadership changes
-->

2. Are there any areas and/or subprojects that your group needs help with (e.g. fewer than 2 active OWNERS)?


3. Did you have community-wide updates in 2023 (e.g. KubeCon talks)?

<!--
  Examples include links to email, slides, or recordings.
-->

4. KEP work in 2023 (v1.28, v1.29, v1.30):
<!--
   TODO: Uncomment the following auto-generated list of KEPs, once reviewed & updated for correction.

   Note: This list is generated from the KEP metadata in kubernetes/enhancements repository.
      If you find any discrepancy in the generated list here, please check the KEP metadata.
      Please raise an issue in kubernetes/community, if the KEP metadata is correct but the generated list is incorrect.
-->

  - Alpha
    - [2371 - cAdvisor-less, CRI-full Container and Pod Stats](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/2371-cri-pod-container-stats) - v1.29
    - [3857 - Recursive read-only mounts](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3857-rro-mounts) - v1.30
    - [4033 - Discover cgroup driver from CRI](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4033-group-driver-detection-over-cri) - v1.28
    - [4176 - New CPUManager Static Policy which spread hyperthreads across physical CPUs to better utilize CPU Cache](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4176-cpumanager-spread-cpus-preferred-policy) - v1.30
    - [4191 - Split Image Filesystem](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4191-split-image-filesystem) - v1.29
    - [4205 - PSI based Node Conditions](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4205-psi-metric) - v1.30
    - [4216 - Image pull per runtime class](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4216-image-pull-per-runtime-class) - v1.29
    - [4369 - Allow special characters environment variable](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4369-allow-special-characters-environment-variable) - v1.30
    - [4381 - DRA Structured Parameters](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4381-dra-structured-parameters) - v1.30

  - Beta
    - [127 - Support User Namespaces](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/127-user-namespaces) - v1.30
    - [2008 - Forensic Container Checkpointing](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/2008-forensic-container-checkpointing) - v1.30
    - [2400 - Node system swap support](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/2400-node-swap) - v1.30
    - [3085 - Pod networking ready condition](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3085-pod-conditions-for-starting-completition-of-sandbox-creation) - v1.29
    - [3673 - KEP Template](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3673-kubelet-parallel-image-pull-limit) - v1.30
    - [3695 - Extend the PodResources API to include resources allocated by DRA](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3695-pod-resources-for-dra) - v1.30
    - [3960 - Pod lifecycle sleep action](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3960-pod-lifecycle-sleep-action) - v1.30
    - [3983 - Add support for a kubelet drop-in configuration directory](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3983-drop-in-configuration) - v1.30
    - [4009 - Add CDI devices to device plugin API](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4009-add-cdi-devices-to-device-plugin-api) - v1.29
    - [4188 - New kubelet gRPC API with endpoint returning local pods information](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4188-kubelet-pod-readiness-api) - v1.30
    - [4210 - ImageMaximumGCAge in Kubelet](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4210-max-image-gc-age) - v1.30
    - [753 - Sidecar Containers](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/753-sidecar-containers) - v1.29

  - Stable
    - [2238 - Liveness Probe Grace Period](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/2238-liveness-probe-grace-period) - v1.28
    - [2403 - Extend kubelet pod resource assignment endpoint to return allocatable resources](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/2403-pod-resources-allocatable-resources) - v1.28
    - [3327 - CPUManager policy option to align CPUs by Socket instead of by NUMA node](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3327-align-by-socket) - v1.28
    - [3545 - Improved multi-numa alignment in Topology Manager](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/3545-improved-multi-numa-alignment) - v1.30
    - [606 - Kubelet endpoint for device assignment observation details](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/606-compute-device-assignment) - v1.28
    - [727 - Kubelet Resource Metrics Endpoint](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/727-resource-metrics-endpoint) - v1.29

## [Subprojects](https://git.k8s.io/community/sig-node#subprojects)


**New in 2023:**
  - [resource-management](https://git.k8s.io/community/<no value>#resource-management)
**Retired in 2023:**
  - noderesourcetopology-api
**Continuing:**
  - ci-testing
  - cri-api
  - cri-tools
  - kernel-module-management
  - kubelet
  - node-api
  - node-feature-discovery
  - node-problem-detector
  - security-profiles-operator

## [Working groups](https://git.k8s.io/community/sig-node#working-groups)

**Retired in 2023:**
 - Multitenancy
**Continuing:**
 - Batch
 - Policy
 - Structured Logging

## Operational

Operational tasks in [sig-governance.md]:
- [ ] [README.md] reviewed for accuracy and updated if needed
- [ ] [CONTRIBUTING.md] reviewed for accuracy and updated if needed
- [ ] Other contributing docs (e.g. in devel dir or contributor guide) reviewed for accuracy and updated if needed
- [ ] Subprojects list and linked OWNERS files in [sigs.yaml] reviewed for accuracy and updated if needed
- [ ] SIG leaders (chairs, tech leads, and subproject leads) in [sigs.yaml] are accurate and active, and updated if needed
- [ ] Meeting notes and recordings for 2023 are linked from [README.md] and updated/uploaded if needed


[CONTRIBUTING.md]: https://git.k8s.io/community/sig-node/CONTRIBUTING.md
[sig-governance.md]: https://git.k8s.io/community/committee-steering/governance/sig-governance.md
[README.md]: https://git.k8s.io/community/sig-node/README.md
[sigs.yaml]: https://git.k8s.io/community/sigs.yaml
[devel]: https://git.k8s.io/community/contributors/devel/README.md
