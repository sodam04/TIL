# 1. VM[가상머신] vs Docker 🫐

가상화

```
물리적인 하드웨어 자원을 논리적인 리소스로 제공하기 위한 기술
1. Host Os {VMware, VirtualBox}
2. Hypervisor {VMware Esxi, Linux Xen/Citrix Xenserver, Microsoft Hyper-V}
3. Container {Docker}
```

두가지의 차이점

```
기존의 VM은 특정 하드웨어의 Resource를 할당해 동작하는 반면에, Docker는 VM과 다르게 
OS(Operating System)을 가상화 하여 동작한다.
```
결론
```
VM = 전가상화를 이용
Docker = 반가상화를 이용
```
https://pinnate-menu-22b.notion.site/1-VM-vs-Docker-de1b71d3b9fc41ca9311d5660459eb67