# merged-pcap-conversations
Quick bash script to merge tcp and udp conversations from a pcap into one view and sorted by time; uses tshark to find conversations

Makes it easier to understand what happened in a pcap without flipping between the two tabs in Wireshark

Setup: git clone https://github.com/grecs/merge-pcap-conversations.git
Update: Update: git pull origin master (from within merge-pcap-conversations folder)

Use:
  merge-tcpudp <pcap file>
