System Monitor Agent
====================

NOTE: UoD/SLS SpaceWalk managed servers only. This role requires access to a particular version of the Check_MK agent, which RHEL 7/ CentOS 7 repositories do not carry. UoD/SLS spacewalk repositories do provide this rpm.

Installs Check_MK agent and deps so a system can be externally monitored.

Currently this also installs and enables xinetd, this could be moved into a separate role.

Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
