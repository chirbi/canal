![Canal Logo](logos/canal-logo-type-full-color.png)

# Policy based networking for cloud native applications #

Canal brings together [Calico](https://projectcalico.org/) network policy with [flannel](https://coreos.com/flannel/docs/latest/) networking.

The current implementation of this for Kubernetes is in the [coreos/coreos-kubernetes](https://github.com/coreos/coreos-kubernetes) repository which provides an easy way to bring up a Kubernetes cluster which uses flannel for networking and Calico for policy.