# Steps Performed
  1-created a resource group<br>
  2-created a storage group in East US region.
  3-created a container inside the storage group and created 3 folders inside that container
  4-copied some files in each of the folders.
  5-Created a flask app that get the folder name and lists the filename present in the corresponding.
  6-Created a VNET with one subnet in East US region.
  7- Created a VM(vm type:Standard_A2_v2) with public ip and 8GB disk in the above resource group and inside the vnet and subnet created
  8-Deployed the flask app to the vm using Putty.
  9-Configured inbound traffic to the vm only from tiger vpn.
  
  # Screenshot of billing information
  ![costanalysis_charts](https://user-images.githubusercontent.com/92777791/162248005-cae35e04-16d2-4d9a-b6ef-cc6c59a77c79.png)
