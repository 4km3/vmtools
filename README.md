# (K)VM Tools

Set of helpers to quickly handle local KVM instances
(Caveat: your user must belong to kvm group or equivalent)

## vminstall

Will install Ubuntu 18.04 via network with a minimal set of packages (OpenSSH and Avahi)

It will also enable the option trustGestRxFilters for macvtap interface in order to propagate broadcast traffic correctly

## vmclone

Will clone a previously installed image updating basic core settings

## vmstart, vmstop, vmdestroy, vmdelete, vmlist

Simple hepler scripts matching standard virsh verbs

## Staging

Contains Ubuntu preseed file for vminstall provision
