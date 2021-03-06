---
title: "Piraeus Datastore"
description: 'HA Datastore for Kubernetes'
info: [{
  subtitle: 'High Available',
  desc: 'Supports 1/2/3 replica numbers for persistent volumes. Piraeus place the replicas intelligently across the nodes to balance the workload.',
  imgUrl: '/img/kube/high-available.png',
}, {
  subtitle: 'Linux Native',
  desc: 'DRBD, as the core component, has been a part of Linux kernel for 10 years. LVM, as the backend, is also a Linux cornerstone. There is no un-battle-tested new stack in data plane.',
  imgUrl: '/img/kube/linux-native.png',
}, {
  subtitle: 'Simple',
  desc: 'Manages data accessibility and availability without the need to integrate a complex storage API. All the configurations are explicit and human-readable.',
  imgUrl: '/img/kube/simple.png',
}, {
  subtitle: 'High Performance',
  desc: 'DRBD-9 has great data replication efficiency. It provides synchronous,semi-synchronous and asynchronous replication schemes, and also supports RDMA for high-speed across-node connection.',
  imgUrl: '/img/kube/high-performance.png',
}, {
  subtitle: 'Cloud Agnostic',
  desc: 'Piraeus can run on all kinds of storage medium: RAID, SAN, NAS or EBS. It unifies storage system across different clouds, both public and private.',
  imgUrl: '/img/kube/cloud-agnostic.png',
}, {
  subtitle: 'Secure',
  desc: 'Fully supports OpenSSL encryption and LDAP authentication. Also provides data encryption at DRBD level. Integrates secret-key management with KVDB, AWS-KMS and Azure Key-Vault.',
  imgUrl: '/img/kube/secure.png',
}]
firstBtnName: 'Katacoda (coming soon)'
firstBtnUrl: 'https://www.katacoda.com/piraeus'
secondBtnName: 'View on Github'
secondBtnUrl: 'https://github.com/piraeusdatastore'
btnHint: '100% Open Source, 100% Cloud Native'
hintWatermarkUrl: '/img/kube/k8s-logo.jpg'
hintBtnName: 'DEPLOY'
hintBtnUrl: 'https://github.com/alexzhc/piraeus-appliance/blob/master/README.md'
hintInfo: '$ kubectl apply -f https://raw.githubusercontent.com/piraeusdatastore/piraeus/master/deploy/all.yaml'
hintInfoUrl: 'https://raw.githubusercontent.com/alexzhc/piraeus-appliance/master/deploy/piraeus.yaml'
linbitUrl: 'https://www.linbit.com/en/'
daocloudUrl: 'https://www.daocloud.io/'
---