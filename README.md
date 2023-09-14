# 3ersW
Three R's Workflow: Rminth, Rpms, Rul (Made for ArchCraft).

## Introduction
Hello! My name is Myna and this is my workflow!

Currently (09/14/2023), I use **ArchCraft** with **TaskWarrior**. Therefore these codes cannot be universal!
I'm also working on a distro based on ArchCraft concepts and Arch code so you can use these applications without any configuration and tweaks, but it's limited to a single system so don't consider this a final solution (I'll work hard on this issue ...).

The goal of this project is not just to make a system pretty, clean, or fast. But combine these attributes of a famous distro and add a touch of spice called “productivity”. This is why **three R's**:

1. **RMINTH**: This is the most essential app in this workflow.  
   The main purpose of **R**ust **M**anager **In**i**t**eger is to organize the startup, shutdown and management of the system in general. It also makes your files easy to backup, save, rescue and find. He is as if he were the 3ersW representative of the system, performing the most general and least specific functions.
2. **RPMS**: This is your productivity manager.  
   **R**ust **P**productivity **M**anager and **S**cheduler was initially called "RPM", but as there is already a known project with the same name, this it would be confusing. Then I had two problems: the name and... TaskWarrior's fragile recurrence system, which I would have to correct to adapt to my workflow. So I thought, "Why not put a scheduler on this and add an S at the end?"  
   It's basically a layer between your actual usage and the TaskWarrior system. So you will rarely use the "task" command (and you would be at risk if you used it without the hook that RPMS will add to your installation. So focus on rpms and forget about TaskWarrior if I don't specify otherwise in the documentation, the which will rarely happen).
3. **RUL**: 3. **R U L**: Contrary to what you may have thought, the first **R** is not from Rust. It's from Rofi.  
   The **R**ofi **U**tilities **L** library is the interface you will use to interact with some visual things. I can't see this as more than a library at the moment, but I plan to add a CLI if I need to edit themes more easily. But for now, it’s just a dependency on the other R’s.
