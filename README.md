# ansible-nova\_server\_facts

Setup custom interface facts for a machine based on the assigned ips to 3 Rackspace networks:-

- public
- srvnet
- private ( one you define )

Rackspace baremetal servers assign random interface names making it difficult to setup a firewall without a mapping

# Dependencies

Machines setup with ansible-nova\_server role.

# Examples

see firehol\_example directory for an example of how to use the interface name
