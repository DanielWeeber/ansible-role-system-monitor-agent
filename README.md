System Monitor Agent
====================

[![Build Status](https://travis-ci.org/ome/ansible-role-system-monitor-agent.svg)](https://travis-ci.org/ome/ansible-role-system-monitor-agent)
[![Ansible Role](https://img.shields.io/ansible/role/41946.svg)](https://galaxy.ansible.com/ome/system_monitor_agent/)

NOTE: UoD/SLS SpaceWalk managed servers only. This role requires access to a particular version of the Check_MK agent, which RHEL 7/ CentOS 7 repositories do not carry. UoD/SLS spacewalk repositories do provide this rpm.

Installs Check_MK agent and deps so a system can be externally monitored.

Currently this also installs and enables xinetd, this could be moved into a separate role.

Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
