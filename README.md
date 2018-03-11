[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/enogrob/ebook-project/master)
```
Roberto Nogueira  
BSd EE, MSd CE
Solution Integrator Experienced - Certified by Ericsson
```
# eBook Docker Containers

![ebook image](assets/ebook.png)

**About**

Learn everything you need to about the subject of this `eBook` project.

[Homepage](https://www.pearson.ch/Informatik/Pearson/EAN/9780134136561/Docker-Containers-includes-Content-Update-Program)

## Topics
```
Table of Contents
Preface   xv
Acknowledgments   xxi
About the Author   xxiii

Part I: Getting Going with Containers   

Chapter 1: Containerizing Applications with Docker   
Understanding Pros and Cons of Containerizing Applications   
  ...An Application Running Directly on a Host Computer   
  ...An Application Running Directly within a Virtual Machine   
  Understanding the Upside of Containers   
  Understanding Challenges of Containerizing Applications   
Understanding What Makes Up Docker   
  The Docker Project   
  The Docker Hub Registry   
  Docker Images and Containers   
  The docker Command   
Approaching Containers   
Summary   

Chapter 2: Setting Up a Container Run-Time Environment   
Configuring a Standard Linux System for Docker   
  Configuring Ubuntu for Docker   
  Configuring Fedora for Docker   
  Configuring Red Hat Enterprise Linux for Docker   
  Configuring Other Operating Systems for Docker   
Configuring a Container-Style Linux System for Docker   
  Configuring an Atomic Host for Docker   
  Configuring CoreOS for Docker   
Summary   

Chapter 3: Setting Up a Private Docker Registry   
Getting and Starting a Private Docker Registry   
  Setting Up a Docker Registry in Fedora   
  Setting Up a Docker Registry in Ubuntu   
Configuring a Private Docker Registry   
  Configuring the docker-registry Package   
  Configuring the registry Container   
Understanding the Docker Image Namespace   
Summary   

Part II: Working with Individual Containers   

Chapter 4: Running Container Images   
Running Container Images Interactively   
  Starting an Interactive Bash Shell   
  Playing Some Character-Based Games   
  Running Administrative Commands Inside a Container   
Running Containerized Services   
  Running a Containerized Web Server   
  Limiting Resources When Running Services in Containers   
Running Privileged Containers   
Summary   

Chapter 5: Finding, Pulling, Saving, and Loading Container Images   
Searching for Images   
  Searching for Images with the docker Command   
  Searching for Images on Docker Hub   
  Searching Other Repositories for Images   
Pulling Images from Registries   
Saving and Loading Images   
Summary   

Chapter 6: Tagging Images   
Assigning Names to Images   
Assigning Tags to Images   
Assigning Repository Names to Images   
  Attaching a User Name to an Image   
  Attaching a Repository Name to an Image   
Summary   

Chapter 7: Investigating Containers   
Inspecting Images and Containers   
Inspecting an Image   
  Inspecting Base Images with docker inspect   
  Inspecting Application Images with docker inspect   
  Looking at the History of an Image   
Inspecting Running Containers   
  Start a Container to Inspect   
  Inspect an Entire Container Configuration   
  Inspect Individual Container Attributes   
Finding More Ways to Look into Containers   
  Using docker top to See Container Processes   
  Using docker attach to Interact with a Service Inside a Container   
  Using docker exec to Start a New Process in a Running Container   
  Using docker logs to See Container Process Output   
  Using docker diff to See How a Container Has Changed   
  Using docker cp to Copy Files from a Container   
Summary   

Chapter 8: Starting, Stopping, and Restarting Containers   
Stopping and Starting a Container   
  Stopping and Starting a Detached Container   
  Starting and Stopping an Interactive Container   
Restarting a Container   
Sending Signals to a Container   
Pausing and Unpausing Containers   
Waiting for a Container’s Exit Code   
Renaming a Container   
Creating a Container   
Summary   

Chapter 9: Configuring Container Storage   
Managing Storage for a Container   
  Using Volumes from the Host   
  Data Volume Container   
  Write-Protecting a Bind Mount   
  Mounting Devices   
  Mounting Sockets   
Storage Strategies for the Docker Host   
  Attaching External Storage to a Docker Host   
Summary   

Chapter 10: Configuring Container Networking   
Expose Ports to Other Containers   
Map Ports Outside the Host   
  Map a Port from Linked Containers   
  Connect Containers on Different Hosts   
Alternatives to the docker0 Bridge   
  Changing Network Mode for a Container   
  Examining Network Options   
Changing the Docker Network Bridge   
Summary   

Chapter 11: Cleaning Up Containers   
Making Space for Images and Containers   
Removing Images  
  Removing Individual Images  
  Removing Multiple Images  
Removing Containers  
  Removing Individual Containers  
  Removing Multiple Containers  
Cleaning Up and Saving Containers   
  Cleaning Up and Saving an Ubuntu Container  
  Cleaning Up and Saving a Fedora Container  
Summary   

Chapter 12: Building Docker Images   
Doing a Simple docker build   
Setting a Command to Execute from a Dockerfile  
  Using the CMD Instruction  
  Using the ENTRYPOINT Instruction  
  Using the RUN Instruction   
  Adding Files to an Image from a Dockerfile  
Exposing Ports from an Image within a Dockerfile  
Assigning Environment Variables in a Dockerfile
Assigning Labels in a Dockerfile  
Using Other docker build Command Options   
Tips for Building Containers  
  Clean Up the Image  
  Keep Build Directory Small  
  Keep Containers Simple  
  Manage How Caching Is Done  
Summary   

Part III: Running Containers in Cloud Environments   

Chapter 13: Using Super Privileged Containers   
Using Super Privileged Containers in Atomic Host   
Understanding Super Privileged Containers  
  Opening Privileges to the Host   
  Accessing the Host Process Table   
  Accessing Host Network Interfaces   
  Accessing Host Inter-Process Communications   
  Accessing Host File Systems   
Preparing to Use Super Privileged Containers  
Using the atomic Command   
  Installing an SPC Image with atomic   
  Getting Information about an SPC Image with atomic  
  Running an SPC Image with atomic  
  Stopping and Restarting an SPC with atomic  
  Updating an SPC Image  
  Uninstalling an SPC Image   
Trying Some SPCs   
  Running the RHEL Tools SPC   
  Running the Logging (rsyslog) SPC   
  Running the System Monitor (sadc) SPC   
Summary   

Chapter 14: Managing Containers in the Cloud with Cockpit  
Understanding Cockpit   
Starting with Cockpit   
Adding Servers into Cockpit   
Working with Containers from Cockpit   
  Adding Container Images to Cockpit   
  Running Images from Cockpit   
Working with Network Interfaces from Cockpit   
Configuring Storage from Cockpit   
Doing Other Administrative Tasks in Cockpit   
  Managing Administrator Accounts in Cockpit   
  Open a Terminal in Cockpit   
Summary   

Part IV: Managing Multiple Containers   

Chapter 15: Orchestrating Containers with Kubernetes   
Understanding Kubernetes   
Starting with Kubernetes   
Setting Up an All-in-One Kubernetes Configuration   
  Installing and Starting Up Kubernetes  
  Starting Up a Pod in Kubernetes   
  Working with Kubernetes  
Summary  

Chapter 16: Creating a Kubernetes Cluster   
Understanding Advanced Kubernetes Features   
Setting Up a Kubernetes Cluster   
  Step 1: Install Linux   
  Step 2: Set Up Kubernetes Master   
  Step 3: Set Up Kubernetes Nodes   
  Step 4: Set Up Networking with Flannel   
Starting Up Pods in a Kubernetes Cluster   
Deleting Replication Controllers, Services, and Pods   
Summary   

Part V: Developing Containers   

Chapter 17: Developing Docker Containers   
Setting Up for Container Development   
  Choosing a Container Development Environment for Red Hat Systems  
  Container Development Environments from Docker  
Using Good Development Practices   
  Gathering or Excluding Files for a Build   
  Taking Advantage of Layers   
  Managing Software Packages in a Build   
  Learning More about Building Containers   
Summary   

Chapter 18: Exploring Sample Dockerfile Files   
Examining Dockerfiles for Official Docker Images   
  Viewing a CentOS Dockerfile   
  Viewing a Busybox Dockerfile   
Examining Dockerfiles from Open Source Projects   
  Viewing a WordPress Dockerfile   
  Viewing the MySQL Dockerfile   
Examining Dockerfiles for Desktop and Personal Use   
  Viewing a Chrome Dockerfile   
  Viewing a Firefox Dockerfile   
Summary   
```
