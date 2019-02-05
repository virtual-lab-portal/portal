# Portal
The Virtual Lab Portal is a project that helps academic instuitions bring together software available for free to VMAP (https://labs.vmware.com/academic) holders and commedity hardware to create an online lab environment backed by VMWare vCenter while using VMWare vRealize Orchestrator for deployment management.  The portal will have features that focus on Adminstrators, professors, and students.  The ultimate goal is to keep users out of the vCenter Web client.

## Problem
it is possible to use commodity hardware cuppled with software available for offer students a remotely accessable virtual lab environemnt for any Computer Science, Business, or Cyber Security academic environment. But administration is cumbersome and student access requires students to actually be in vCenter, which really isn't ideal- it poses a security concern, and is difficult to navigate.

## Solution
The best solution to the adminstration issue is to use VMWare vRealize Orchestrator to manage the provisioning of student labs. But this is still cumbersome.  Another goal is to move the students out of vCenter- I prefer VMRC over a web console (better space utilization for different resolution console windows, if shared clipboard is enabled it is easier via VMRC, and more)

## Requirements
1. VMWare Environment (ESXi hosts to support the load, vCenter)
2. VMWare vRealize Orchestrator (one node included with any vCenter license- More available via On The Hub VMAP Agreement)
3. Active Directory for Authentication
4. A Password Management Portal (https://github.com/pwm-project/pwm)
5. This Project's Virtual Lab Portal

## Roadmap
More to come
