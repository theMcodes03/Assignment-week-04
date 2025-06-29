# Docker & Containerization Fundamentals - Week 4 Task 1

This document outlines the steps performed to understand the core concepts of containerization and Docker, and to demonstrate basic Docker commands.

---

### 1: Introduction to Containerization and Docker Fundamentals, Basic Commands

**Objective:**  
To identify and understand the core concepts of containerization and Docker, and to execute fundamental Docker commands.

---

### Actions performed:

1. **Explored Containerization Concepts:**  
   Learned about containerization, how it differs from virtual machines, and why Docker is preferred for lightweight, isolated, and reproducible application environments.

---

2. **Executed `docker run` command:**  
   To verify Docker installation and functionality:
   ```bash
   docker run hello-world
   ```
   ![Docker Run Hello World](Images/imagestask1/Docker_Run_Hello_World.png)

   ```bash
   docker run hello-world
   ```
   ![Docker Run Hello World 2](Images/imagestask1/Docker_Run_Hello_World_2.png)

---

3. **Pulled the BusyBox Image:**
   ```bash
   docker pull busybox
   ```
   ![Docker Pull Busybox](Images/imagestask1/Docker_Pull_Busybox.png)

---

4. **Listed Docker Images:**
   ```bash
   docker images
   ```
   ![Docker Images List](Images/imagestask1/Docker_Images_List.png)

---

5. **Ran a Command in BusyBox:**
   ```bash
   docker run busybox echo "Hello from BusyBox"
   ```
   ![Docker Run Busybox Echo](Images/imagestask1/Docker_Run_Busybox_Echo.png)

---

6. **Checked Running Containers (should be empty):**
   ```bash
   docker ps
   ```
   ![Docker PS Empty](Images/imagestask1/Docker_PS_Empty.png)

---

7. **Listed All Containers (including stopped):**
   ```bash
   docker ps -a
   ```
   ![Docker PS All Containers](Images/imagestask1/Docker_PS_All_Containers.png)
   ![Docker PS All](Images/imagestask1/Docker_PS_All.png)

---

8. **Ran an Interactive Ubuntu Container:**
   ```bash
   docker run -it ubuntu bash
   ```
   ![Docker Run Ubuntu Bash](Images/imagestask1/Docker_Run_Ubuntu_Bash.png)

---

9. **Exited & Stopped Ubuntu Container:**
   From within container:
   ```bash
   exit
   ```
   ![Docker Run Ubuntu Exit Stop](Images/imagestask1/Docker_Run_Ubuntu_Exit_Stop.png)

---

10. **Removed a Stopped Container:**
   ```bash
   docker rm <container-id>
   ```
   ![Docker RM Container](Images/imagestask1/Docker_RM_Container.png)

---

11. **Pruned All Exited Containers:**
   ```bash
   docker container prune
   ```
   ![Docker Prune Containers](Images/imagestask1/Docker_Prune_Containers.png)

---

12. **Command Prompt Environment:**
   ![CMD Window](Images/imagestask1/CMD_Window.png)

---

13. **Application Setup Before Dockerization:**
   ```bash
   ls
   npm install express
   ```
   ![Project Directory](Images/imagestask1/Dir_Dempwebapp.png)  
   ![Install Express](Images/imagestask1/NPM_Install_Express.png)

---