# azure-create-virtual-machine
---
In this lab we are going to create a windows vm and linux vm
---

1. Create a Resource Group 
2. Create a Windows 10 Virtual Machine (VM)
   - While creating the VM, select the previously created Resource Group
   - While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet
3. Create a Linux (Ubuntu) VM
   - While creating the VM, select the previously created Resource Group and Virtual Network—the Virtual Network MUST BE THE SAME.
   - Authentication type: Username/Password
4. Ensure both VMs are in the same Virtual Network / Subnet

---

**Frist we are going to create a resource group. I named it (RG-Network-Activies), from there click on the create button**

![step1](https://github.com/user-attachments/assets/ef3938b5-6606-4265-b9eb-f4c468b6d422)

![step2 review and create](https://github.com/user-attachments/assets/0c008dc2-d9da-47ea-945b-d887f494baa8)

![step3](https://github.com/user-attachments/assets/b3962806-f36a-4304-a0fe-e33ce555a4ae)


**Next we are gonna search for the vitual machines**

![step4](https://github.com/user-attachments/assets/a889c86f-0e61-4727-9e5b-618e66bbee6a)

**Click on the create and then select the virtual machine option**

![step5-b](https://github.com/user-attachments/assets/cca0f1e5-b1c3-4ec2-b211-1805005dfe77)

**Now that we are in the virtual machine area, You will be presented with the option to build out the virtual machine**

![step6](https://github.com/user-attachments/assets/ac712eb4-69b3-4047-8839-822b952834d7)

**we are gong to use Wins 11, select it from the drop down section from the image area. Make sure it's in the same zone as the resource group. Then give the vm a name I went with (windows-vm)**

![step7](https://github.com/user-attachments/assets/5c683e9f-f6af-4e53-83ef-b22afd3749e3)

**Scroll down and you'll see the Size, Username and Passwords sections. For the Size I went with a free option for this lab. You can pick want you need, but be aware that it will charge you.**
**Next pick a username and password, then at the check the checkbox that deals with licensing Window, if not the vm will not build**

![step8](https://github.com/user-attachments/assets/61b4a849-b122-4780-a890-6256437d556d)

**This click on networking. Here we are going to create a new Network Group. Give it name. Then press ok at the bottom. Finally select the newly create virtual network (if not auto-populated)**

![Screenshot_20250611_125423](https://github.com/user-attachments/assets/a534508d-f35d-49db-923a-de36be5b7da8)

**Next, we will press the review and create, then press the create button**

![step9](https://github.com/user-attachments/assets/8ebdb9b3-454e-4a4b-9a8f-7c11db89c0f3)

**Now go back to the resource grouops and click on the resource we created earlier. Note: you might see another resource group we will ignore that for now.**
**As you can see there are a lot of items that were create, the vm, a network and storage and so on...**

![step10](https://github.com/user-attachments/assets/d8ec8ae5-0954-49c5-82b9-57a66abd2ae7)

**From here we are going to repeat the steps all over again. This time we will be a Linux VM. Make sure it's in the same resource group and virtual network.**

---

**Known issues**
There are times where you might not see the virtual network, try to refresh the page if this happens. 


