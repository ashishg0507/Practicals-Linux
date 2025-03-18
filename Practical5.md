1. ps Command
-> (a)Display all running processes:
      ps aux
   ![Screenshot 2025-03-18 211238](https://github.com/user-attachments/assets/a8ea1c57-2423-42c1-b989-217c4c96aedf)

   (b)Show processes for the current terminal session:
      ps
   ![Screenshot 2025-03-18 211259](https://github.com/user-attachments/assets/f0b400c6-58c0-408e-8545-ac09fef579a3)

   (c)Display a process tree:
      ps -e --forest
   ![Screenshot 2025-03-18 211338](https://github.com/user-attachments/assets/a7f9c934-9f9a-4bce-a41a-e57c6a4e84bb)

   (d)Filter by process name:
      ps -C firefox
   ![Screenshot 2025-03-18 211421](https://github.com/user-attachments/assets/55146a8d-1574-401f-9ae4-ccdbb55aaba1)
  
   (f)Show detailed information of a specific process:
      ps -p 1234 -o pid,ppid,cmd,%mem,%cpu
   ![Screenshot 2025-03-18 211536](https://github.com/user-attachments/assets/ce34130b-bbf3-437f-b3c1-60627c615477)


2. kill Command
-> (a)Find the PID: 
      ps aux | grep firefox
   ![Screenshot 2025-03-18 211607](https://github.com/user-attachments/assets/2d572e5c-b775-4224-a903-46089faff13d)

   (b)Kill a process by PID:
      kill 1234
   
   (c)Force kill a process: 
      kill -9 1234
   
   (d)Kill by process name: 
      killall firefox

5. top Command
-> top
   Sort by memory usage: Press M
   Sort by CPU usage: Press P
   Kill a process: Press k → Enter the PID
   Exit top: Press q
   ![Screenshot 2025-03-18 212145](https://github.com/user-attachments/assets/faff89fa-c118-41f1-865b-aaaed9afceec)


3. apt-get Command
-> (a)Update package list:
      sudo apt-get update
   ![Screenshot 2025-03-18 212333](https://github.com/user-attachments/assets/c0fb2fdf-6747-42e3-a2d9-ddbff6ad1f1e)

   (b)Upgrade installed packages:
      sudo apt-get upgrade
   ![Screenshot 2025-03-18 212417](https://github.com/user-attachments/assets/90fad336-082f-47e3-aceb-eb8d0ce94a04)

   (c)Install a package:
      sudo apt-get install vim
   ![Screenshot 2025-03-18 212609](https://github.com/user-attachments/assets/2d880127-63ea-49c5-8773-2d0370334dfb)

   (d)Remove a package:
      sudo apt-get remove vim
   ![Screenshot 2025-03-18 212653](https://github.com/user-attachments/assets/1b4fc88c-69c5-437b-a663-8d129bd056d0)

   (e)Remove package along with configuration files:
      sudo apt-get purge vim
   ![Screenshot 2025-03-18 212735](https://github.com/user-attachments/assets/7ac86397-7bed-4665-8690-62c3837db1bb)

   (f)Clean up unused packages:
      sudo apt-get autoremove
   ![Screenshot 2025-03-18 212835](https://github.com/user-attachments/assets/d269603a-cafc-461c-9db9-abf7d8d770a1)

   (g)Clean package cache:
      sudo apt-get clean
   ![Screenshot 2025-03-18 212903](https://github.com/user-attachments/assets/8e71307a-9bc4-4d91-9da0-7c90bfafcb01)
