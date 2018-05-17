Homework, ISTA-422
--
Chapter 03, Fundamentals of Azure
=



1. What is Azure Virtual Machines and the terminology used in the chapter to reference?

--Windows Azure Virtual Machines are a new addition to the services provided by Windows Azure. They allow a much easier and flexible solution for quickly moving an existing workload from on-premises to the cloud or for building new applications that have dependencies on applications that will only run on a server with persistent local storage.

2. How do you stop an Azure VM, and give an example?

--By stopping (deallocating) a VM, you not only stop the VM’s OS, you also free up the hardware and network resources Azure previously provisioned for it (a process called deallocation). 

3. What are three main resource providers used when working with Azure Vitrual Machines, Storage, and Compute?

--the NIC references the virtual machine's assigned IP address (required),

--Virtual Networks

--Cloud Service for Virtual Machines

4. Where are durable disks stored and what are the beneﬁts?

--Queue Storage - It allows you to decouple your components and have reliable asynchronous communication. In Azure Queue Storage, the number of queues is only limited by the capacity of the storage account. 

5. What is required when creating a VM in Azure using the Resource Manager model?

--A CancellationToken enables cooperative cancellation between threads, thread pool work items, or Task objects. You create a cancellation token by instantiating a CancellationTokenSource object, which manages cancellation tokens retrieved from its CancellationTokenSource.Token property. You then pass the cancellation token to any number of threads, tasks, or operations that should receive notice of cancellation. 

6. What is a NIC and what does it what does it do for Azure?

--An NIC is a network interface, it allows you to manage network traffic

7. Why should you deploy at least two instances of the VM? What is provided?

--Azure virtual machines (VMs) can be created through the Azure portal. This method provides a browser-based user interface to create VMs and their associated resources.

8. How many ways can you connect to your VM, and what are they?

--Actions pane

--Virtual machines view

9. Who’s responsibility is it to manage the VM?

--The developer

10. What is important when determining the scale-out approach to VMs, and what model is this referred to?10.  

--Manually-scaled Availability Sets of specialized VM images are easier to roll out 