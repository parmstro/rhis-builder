# Welcome to rhis-builder

The rhis-builder project is a set of tooling and configuration designed to build, manage and maintain an opinionated model of a hybrid cloud Red Hat Enterprise Linux environment using infrastructure as code and gitOps methodologues with traditional VM and container workloads. You can start where you are, or you can build from scratch. 

The code in this repository is content for a instructional course on using the rhis-builder project, its repositories and the rhis-provisioner container. If you are interested in a guided experience (recommended) with rhis-builder, please reach out to a Red Hatter to discuss or email/message one of the contributors to this project. We will help you get the support that you need to be successful. If you are a determined open source user and enjoy a challenge or want to contribute. Please! Read on! PRs are welcome on all our repositories.

<hr>

If you are diving into the pool...this is the place to start. 
[What the heck is a Red Hat Infrastructure Standard environment?](https://github.com/parmstro/rhis-builder/wiki)


The next thing...
Get the [inventory sample](https://github.com/parmstro/rhis-builder-inventory) and use the provisioner container!

The inventory repository contains our sample environment and a script that will allow you to quick, very basic configuration changes to generate your own custom inventory. Convenient scripts are also created for you to pull and launch the provisioner container to connect to your inventory and start provisioning.

See the wiki to review the bootstrap scenarios and the instances that you need to get started. What you need at a minimum is listed below.

The rhis-provisioner-9 container build is based on RHEL UBI 9 and has all of the binary dependencies and all of the ansible code for all of the rhis-builder projects baked in. This has resulted in consumers getting to a working environment **way** faster. We are working to make "Life is Better with RHIS" a reality. 

<img src=https://github.com/parmstro/rhis-builder/content/modules/ROOT/assets/LifeisBetterwRHIS_web.png>

If you haven't been there yet, please visit the [rhis-builder-provisioner wiki](https://github.com/parmstro/rhis-builder-provisioner/wiki) first

See [rhis-builder-inventory](https://github.com/parmstro/rhis-builder-inventory) repo for all sample configurations and secrets definitions.

## What you will need at a minimum:
A plan! 

What sort of environment do you want to build? For our sample - example.ca - see the wiki. Literally, you can build a hybrid multicloud deployment.

Your best experience will be with 3 systems. They can be VMs, Baremetal or cloud instances for:
- a node to run the rhis-provisioner-9 container
- a node for identity management
- a node for satellite

That gets you off the ground, to get flying you will need:
- more baremetal nodes, or 
- a supported hypervisor environment, or 
- a supported cloud environment, or 
- all of the above

to build out the rest of your architecture...

## See the [Wiki for Instructions on getting started](https://github.com/parmstro/rhis-builder-provisioner/wiki)

#### Helping out
I know that most of you have experience with these things, but we also work with people with less experience. So, please bear with us if a lot of activities that you know well are spelled out. If you have any comments, tips, tricks or suggestions to add to the documentation or README.md file, PRs are greatly appreciated. Let's share the wealth!

