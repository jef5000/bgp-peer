# bgp-peer
This skillet will configure a BGP peer.  It needs to be combined with a redistribution profile in order to advertise routes to the peer.  This configuration assumes all of the default timers and values for BGP.

To use, fill out the requested variable values.  Once the configuration has been completed, combine this skillet with one that configures the redistribution profile, or configure the profile manually on the firewall.  The requested variables are:

•	local_address

•	local_as

•	local_interface

•	peer_as

•	peer_group_name

•	peer_ip

•	peer_name

•	peer_as

•	router_id

•	virtual_router_name
 
