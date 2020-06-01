# AZ-104-Azure-DNS

## Steps to create a public zone DNS

1. Create a virtual machine, and make sure it has a public IP address
2. To test, enable IIS on the VM, and make a simple HTML page
3. Create a DNS Zone resource, and give the name of <your-domain-name>.com. Review and create.
4. Add a record set to map domain onto VM
5. Leave name blank
6. Use A record
7. Specify public IP of VM
8. Add the 4 name servers of the DNS Zone on Azure to the domain registrar
9. Test by going to the URL
