# Net&Sys Assignment: Running Containers for Application Development

Group Name: __Fill your team name__. 

Team Mates:
1. DANISH HAIKAL BIN MOHAMMAD (2219885)
2. __Fill name__ and __matric no__
3. __Fill name__ and __matric no__

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** __Fill answer here__.
    https://github.com/denihhh/NatSysProject.git
2. How many files and folders are in this repository. ***(1 mark)*** __Fill answer here__..

   There is 1 file named README.md and 1 folder named images


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)***

    __Linux OS virtual environment__.

2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 

    __RAM = 4GB/8GB__.
   
    __DISK = 32GB/64GB__.
   
    __VCPU = 2/4__.


3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Fill answer here__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** __Fill answer here__.
    
   ![image](https://github.com/denihhh/NatSysProject/assets/152835701/0ed4b731-0839-47b8-aa06-866735434db3)

2. Run the command **cat /etc/passwd** . ***(1 mark)*** __Fill answer here__.

![image](https://github.com/denihhh/NatSysProject/assets/152835701/22796132-0505-4e9f-9b12-116794eb15bd)

3. Run the command **df** . ***(1 mark)*** __Fill answer here__.

![image](https://github.com/denihhh/NatSysProject/assets/152835701/3b1e1aa0-f3ff-4d6d-bfaa-09f7ba89466a)

4. Run the command **du** . ***(1 mark)*** __Fill answer here__.
__du

1972    ./images
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
68      ./.git/hooks
4       ./.git/branches
8       ./.git/refs/heads
4       ./.git/refs/tags
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
8       ./.git/objects/fc
8       ./.git/objects/f6
8       ./.git/objects/ab
8       ./.git/objects/fe
12      ./.git/objects/70
8       ./.git/objects/f2
8       ./.git/objects/3f
8       ./.git/objects/0b
8       ./.git/objects/eb
12      ./.git/objects/44
8       ./.git/objects/81
8       ./.git/objects/86
8       ./.git/objects/c3
8       ./.git/objects/fd
8       ./.git/objects/20
8       ./.git/objects/57
8       ./.git/objects/1b
8       ./.git/objects/24
8       ./.git/objects/b9
8       ./.git/objects/b2
8       ./.git/objects/3a
12      ./.git/objects/17
8       ./.git/objects/45
8       ./.git/objects/93
4       ./.git/objects/info
8       ./.git/objects/c6
8       ./.git/objects/71
8       ./.git/objects/5b
8       ./.git/objects/e7
12      ./.git/objects/1c
8       ./.git/objects/58
8       ./.git/objects/60
12      ./.git/objects/af
8       ./.git/objects/a3
12      ./.git/objects/14
8       ./.git/objects/d8
8       ./.git/objects/83
8       ./.git/objects/b6
8       ./.git/objects/fa
12      ./.git/objects/b5
12      ./.git/objects/d2
12      ./.git/objects/73
8       ./.git/objects/cb
12      ./.git/objects/e5
12      ./.git/objects/a1
8       ./.git/objects/0d
12      ./.git/objects/72
12      ./.git/objects/ff
8       ./.git/objects/7b
8       ./.git/objects/4a
12      ./.git/objects/64
8       ./.git/objects/4f
8       ./.git/objects/74
12      ./.git/objects/6e
8       ./.git/objects/e9
8       ./.git/objects/41
12      ./.git/objects/62
1824    ./.git/objects/pack
12      ./.git/objects/2e
12      ./.git/objects/06
8       ./.git/objects/a6
12      ./.git/objects/3d
8       ./.git/objects/49
16      ./.git/objects/fb
8       ./.git/objects/52
8       ./.git/objects/91
8       ./.git/objects/47
8       ./.git/objects/96
8       ./.git/objects/f9
8       ./.git/objects/cd
8       ./.git/objects/4b
8       ./.git/objects/04
2476    ./.git/objects
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
2656    ./.git
4648    .__


5. Run the command **ls** . ***(1 mark)*** __Fill answer here__.
__ls__

![image](https://github.com/denihhh/NatSysProject/assets/152835701/c0937592-4c08-4fc5-8068-0c28021ace25)

6. Run the command **ls -asl** . ***(1 mark)*** __Fill answer here__.

![image](https://github.com/denihhh/NatSysProject/assets/152835701/3694da30-3d8f-4ad5-8e9b-7d8843325cd9)

7. Run the command **free -h** . ***(1 mark)*** __Fill answer here__.

![image](https://github.com/denihhh/NatSysProject/assets/152835701/c8ecc3ce-4a58-4c43-9016-5b0dd789e1a9)

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** __Fill answer here__.

cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3175.360
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb
 rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm                                           bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.84
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3224.308
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb
 rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm                                           bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.84
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:


9. Run the command **top** and type **q** to quit. ***(1 mark)*** __Fill answer here__.

![image](https://github.com/denihhh/NatSysProject/assets/152835701/5d89f618-54d3-4abc-91f8-fbb93789bdf1)

10. Run the command **uname -a**. ***(1 mark)*** __Fill answer here__.

![image](https://github.com/denihhh/NatSysProject/assets/152835701/2b89be4e-6350-4247-adb8-74b0e529eb76)

11. What is the available free memory in the system. ***(1 mark)*** __Fill answer here__.
    177Mi 

12. What is the available disk space mounted on /workspace. ***(1 mark)*** __Fill answer here__.
    
![image](https://github.com/denihhh/NatSysProject/assets/152835701/f8784885-4c36-41e6-a432-7be0db98556a)

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __Fill answer here__.

Linux codespaces-a1782f 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __Fill answer here__.

    ls: Lists filenames.
    ls -asl: Lists all files (including hidden) with sizes and detailed information.

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __Fill answer here__.

    L1 TLB: 64 4-KB pages per core

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __Fill answer here__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __Fill answer here__.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 

docker pull debian
docker run --detach -it debian

bash
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker pull debian
Using default tag: latest

latest: Pulling from library/debian
Digest: sha256:a92ed51e0996d8e9de041ca05ce623d2c491444df6a535a566dabd5cb8336946
Status: Image is up to date for debian:latest
docker.io/library/debian:latest

@farisrosly ➜ /workspaces/NatSysProject (main) $ docker run --detach -it debian
21bc997724f53455054a6a8e2f4fa09732843d4af0c2ea54af79df7777b8844e

2. This will run the debian container. To check if the debian container is running, type
bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson

bash
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
e53e712fdcc0   debian    "bash"    30 seconds ago   Up 27 seconds             stupefied_keller


3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
bash
docker exec -i -t romantic_jackson /bin/bash

bash
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker exec -i -t e53e712fdcc0 /
bin/bash



4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
 
bash
root@e53e712fdcc0:/# apt-get update
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8786 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [160 kB]
Fetched 9214 kB in 1s (8617 kB/s)                         
Reading package lists... Done
root@e53e712fdcc0:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (34.4 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@e53e712fdcc0:/# cd /root
root@e53e712fdcc0:~# nano helloworld.txt


5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing *exit*.
![image](images/helloworld.png)

6. Stop the container and run *docker ps -a*, and restart the container again. Is your file in the container still available?
bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

bash
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker stop e53e712fdcc0

@farisrosly ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS         PORTS     NAMES
e53e712fdcc0   debian    "bash"    15 minutes ago   Up 4 minutes             stupefied_keller

@farisrosly ➜ /workspaces/NatSysProject (main) $ docker restart e53e712fdcc0



7. Stop the container and delete the container. What happened to your helloworld.txt?

bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson

bash
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker stop stupefied_keller
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                       PORTS     NAMES
e53e712fdcc0   debian    "bash"    23 minutes ago   Exited (137) 5 seconds ago             stupefied_keller
@farisrosly ➜ /workspaces/NatSysProject (main) $ docker rm stupefied_keller
e53e712fdcc0


**Questions:**

1. Are files in the container persistent. Why not?. *(1 mark)* _Fill answer here_.

No, files in a Docker container are not persistent by default. This is because containers are designed to be ephemeral and stateless. When a container is deleted, its filesystem and any changes made within the container are also removed. To persist data beyond the life of a container, you need to use Docker volumes or bind mounts, which allow data to be stored on the host system and survive container restarts and deletions.

2. Can we run two, or three instances of debian linux? . *(1 mark)* _Fill answer here_.

 Yes, you can run multiple instances of Debian Linux containers. Docker allows you to create and run multiple containers from the same image simultaneously. Each container runs in its own isolated environment with its own filesystem, processes, and network interfaces. To run multiple instances, you can simply execute the docker run command multiple times, and Docker will create and manage these instances independently.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __Fill answer here__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Fill answer here__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Fill answer here__.
2. What port is the apache web server running. ***(1 mark)***
3. What port is open for http protocol on the host machine? ***(1 mark)***

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __Fill answer here__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
4. What is the network address for the running container c1 and c2.
5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
