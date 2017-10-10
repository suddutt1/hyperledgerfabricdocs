# Hyperledger Fabric v1 documentaion and understanding

## GO SDK
The golang sdk uses a configuration file 
1. For each org we need different configs
2. Configs contains 2 parts , private info for the organization. and public information about other organization
3. Altough the channel section contains the list of all the peers from all the orgs those are member of a given channel , channel.Peers() returns only the peers associated with the organizations.Please note that while creating the channel object peers attached to an organization are added using a channel.AddPeer method
