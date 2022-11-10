## Links
1.  https://resources.infosecinstitute.com/topic/segmentation-penetration-testing-for-pci-compliance/#:~:text=Firstly%2C%20you%20should%20have%20thorough,PCI%20out%2Dof%2Dscope.
2.  https://insights.sei.cmu.edu/blog/network-segmentation-concepts-and-practices/
# 
There are supportive systems , that sometimes hosted in non  CDE segments . These communications are allowed . But you need to get get the confirmation from the client that these machines are supportive to the CDE segments and it's allowed to communicate. Also check only required communications are established between the CDE to these supportive systems . You can ask em the the firewall rules for this .
# 
firewall rules are verified during port scan or ping scan if you perform it from non segment or public network,

if no ports are open ,then you can confirm it is deny all for the non segment and also for public networks
# 

usually during segmentation assessment, we only perform port scan and ping from one segment of network to another to check whether there is any connection or ports open between two segments

for eg; in pci, from non pci segment to pci segment.
