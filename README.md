# cs336-network-visualization 
- Reads in a pcap file and creates a directed graph with the nodes representing MAC addresses and the edges representing packets. If a node has an edge pointing to another node, then that means that a packet has been sent from that node's MAC address to the MAC address at the node that the edge is pointing to.

- Example usage: python macvisual.py pcap_file

- "testpcap" is a pcap file that can be used to test this program.

- To get a good view of a specific MAC address on the graph, it may be necessary to zoom into its node if there are many nodes present on the graph.
