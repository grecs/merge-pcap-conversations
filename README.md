# merged-pcap-conversations
Born out of the frustration of flipping between the tcp and udp tabs in Wireshark's conversation view when trying to understand the flow of what occured

Currently, just one quick bash script that merges tshark tcp and udp conversations from a pcap into one view and sorts by time; might add new variants if the need arises

Setup: git clone https://github.com/grecs/merge-pcap-conversations.git

Update: Update: git pull origin master (from within merge-pcap-conversations folder)

Use: merge-tcpudp [pcap file]
