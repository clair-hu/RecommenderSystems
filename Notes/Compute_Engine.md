# Compute Engine

----
## Compute Engine offers managed virtual machines
* Pick memory and CPU: use predefined types, or make a custom VM
* Pick GPUs if you need them



----
## Compute Engine offers managed virtual machines
* Pick persistent disks: standard or SSD
* Pick local SSD for scratch space too if you need it  

Just like physical computers need disks, so do VMs.

### Two kinds of persistent storage
* Standard
* SSD

> If your application needs high performance scratch space, you can attach a local SSD
> But be sure to store data of permanent value somewhere else because local SSD's content does not last past when the VM terminates.
This is why local SSD is **not** considered as persistent disks.

----
## Compute Engine offers managed virtual machines
* Pick a boot image: Linux or Windows Server  

You also choose a **boot image**.

> GCP offers lots of versions of LINUX and Windows.
> You can import your own images too.

----
## Compute Engine offers managed virtual machines
* Define a startup script if you like

### To have VMs to always come up with certain configurations, like installing software packages on first boot
* It's very common to pass GCP VM startup scripts that do just that.
* You can also pass in other kinds of metadata too.

----
## Compute Engine offers managed virtual machines
* Task disk snapshots as backups or as migration tools

Once your VMs are running, it is easy to take a durable **snapshot** of their discs.
* You can keep these as backups or use them when you need to migrate a VM to another region.

----
## Compute Engine offers managed virtual machines
* Preemptible instances

> Suppose you have a workload that no human being is sitting around waiting to finish, for example, a bash job analyzing a large data set. You can save a lot of money by choosing preemtible VMs to run the job.

### Preemptible VM
It is different from an ordinary compute engine VM in only one respect:  
You have given compute engine permission to terminate it if its resources are needed elsewhere.

**Note** - Be sure to make your job able to be stopped and restarted.

----
## Compute Engine offers managed virtual machines
* Custom machine types: Only pay for the hardware you need

> You can choose the machine proper use of your instances, such as the number of virtual CPUs and the amount of memory, by using a set of predefined machine types or by creating your own custom machine types

----
## Scale up or scale out with Compute Engine  
Use big VMs for memory- and compute-intensive applications.  

Use Autoscaling for resilient, scalable applications.

> Most GCP customers start off with **scaling out**, not scaling up.  

Compute engine has a freature called **auto scaling** that lets you add and take away VMs from your application based on load metrics.

The other part of making that work is balancing the incoming traffic across the VMs.

Google VPC supports several different kinds of **load balancing**.

----
Question: What is the main reason customers choose Preemptible VMs?

Answer: To reduce cost.

Question: True or false: You can create Compute Engine virtual machines from the command line.

Answer: True - It's advantageous to create virtual machines from a command line when you want their configurations to be scripted and repeatable. The gcloud command, provided by Google Cloud as part of the GCP SDK, can create virtual machines with parameters you specify.