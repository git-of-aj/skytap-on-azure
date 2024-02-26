# Benefits of Sky Tap and Azure 
[Good PDF](https://www.skytap.com/wp-content/uploads/2023/11/Skytap-on-Azure-Datasheet-November-2023.pdf)
- [intro by wipro](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE54mh7)
 - [popular casestudies](https://www.skytap.com/case-studies/)
 - [Sktap docs on azure migration](https://www.skytap.com/terms-glossary/azure-cloud-migration/)
 - [Tips and Tricks](https://www.skytap.com/skytap-product-tips-and-tricks/)
 -  WHitepaper why IBM Power Apps to azure - https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE56i7z
# skytap-on-azure
1. Create Env -
- A Skytap environment contains a related set of virtual machines and networks. An environment can be as simple as one virtual machine (with one automatically created virtual network), or it can be a complex application stack with multiple VMs and complex networking.
- [Hands-on](https://help.skytap.com/getting-started.html)
2. Skytap On Azure
  - [Hands-on](https://help.skytap.com/creating-a-skytap-on-azure-account.html)
3. Skytap Features by Region
- https://help.skytap.com/overview-features-by-region.html
4. Pre-Requisites - like latency etc 
- https://help.skytap.com/vm-access-requirements.html
5. ENv on Azure - https://help.skytap.com/creating-an-environment.html
- Creating an environment
There are several ways to create a virtual environment in Skytap:

1. To quickly set up a new environment, create an environment from a public template or a template that has been shared with you. Skytap public templates provide common operating systems and applications that are ready to run. For instructions, see Creating an environment from a template.
2. If you already have an environment in your account, you can quickly clone it to create a separate copy. For instructions, see Copying an environment.
3. To import your own virtual machine into Skytap, see Importing VMs into Skytap.
4. To build your own virtual machine using an ISO image, see Building a VM from an ISO.
- Once you’ve created an environment, you can customize it by adding and deleting VMs, editing the VMs, or modifying the networks.
6. Accessing Vm's - https://help.skytap.com/accessing-vms-with-a-browser.html

## SkyTap On Azure Network Considerations 
- https://www.youtube.com/watch?v=myDUq3UJg4M

## SKyTap & Azure Services Integrations
- https://www.skytap.com/category/skytap-on-azure/
- [Blob](https://www.skytap.com/accessing-azure-blob-storage-from-a-skytap-environment-ibm-i-and-aix/)
- [Step by STep Azure netapp on Azure](https://skytap.github.io/well-architected-framework/operations/ecosystems/azure-native/skytap+netapp-files)
- [Skytap with azure synapse](https://www.skytap.com/wp-content/uploads/2022/04/White-Paper-Skytap-Azure-Synapse.pdf)
- [READ ONLY - HA/DR ON AZURE](https://www.skytap.com/high-availability-disaster-recovery-options-for-ibm-power-running-in-skytap-on-azure/)
- [skytap backup](https://www.skytap.com/skytap-template-backup-and-copy-to-region-for-disaster-recovery/)
- [Assure MIMIX on Skytap](https://www.skytap.com/assure-mimix-ha-dr-for-ibm-i-production-workloads-in-now-available-in-skytap-on-azure/)
- [Reserved Capacity on Azure](https://www.skytap.com/reserve-capacity-in-skytap-on-azure-self-service-now-available/)
- [Data box for quick migration](https://www.skytap.com/using-microsoft-azure-data-box-for-migration-of-ibm-i-workloads-to-skytap/)
- [IGNORE - PROMINIOUS MODE](https://www.skytap.com/what-is-promiscuous-mode-and-why-does-it-matter/)
### do not works on azure free trail : The operation cannot be completed due to the following error: Plan 'hkm1r1_paygo_pub_oct23' can not be purchased on a free subscription, please upgrade your account, see https://aka.ms/UpgradeFreeSub for more details.
