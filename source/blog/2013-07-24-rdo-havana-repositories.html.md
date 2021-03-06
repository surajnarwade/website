---
title: RDO Havana repositories
date: 2013-07-24 18:25:56
author: pixelbeat
---

There are now 4 separate Havana repositories available on RDO

**Trunk packages for Fedora and EL6 derivatives**

The _current_ trunk package series, generated by http://smokestack.openstack.org/
with maximum lag of 1 hour from the latest trunk commit are available for Fedora
and more recently EL6 based distributions.
Please see the README or browse these repositories at:
http://rdo.fedorapeople.org/openstack/openstack-trunk/

**Standard Havana repositories for Fedora and EL6 derivatives**

Also we now have the more standard release repository for Havana,
which contains the recently released Havana milestone 2 packages.
The best way to interact with this repository is to follow
the RDO quick start guide at: http://rdoproject.org/Quickstart
while just replacing "grizzly" with "havana" in step 1.
This package set can be used with EL6 based distros or Fedora 19.
Fedora 19 contains OpenStack Grizzly packages in the official Fedora repositories,
and RDO makes the next OpenStack version available for test and evaluation.
These repositories can be browsed at:
http://rdo.fedorapeople.org/openstack/openstack-havana/

A caveat to note with the above repositories, is that
the openstack-neutron packages are not yet available.
These will be made available in the coming days.

thanks,
Pádraig.
