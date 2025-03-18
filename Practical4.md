1. Create the /home/consultants directory:
-> sudo mkdir /home/consultants
![Screenshot 2025-03-18 195907](https://github.com/user-attachments/assets/98094921-8cbb-404f-a7e8-8f70b787f6b2)


2. Add write permission to the consultants group (symbolic method):
-> sudo chmod g+w /home/consultants
   ![Screenshot 2025-03-18 200036](https://github.com/user-attachments/assets/fa95b461-b09e-4d33-9087-5e4a48ecf7af)


3. Forbid others from accessing the /home/consultants directory (octal method):
-> sudo chmod 750 /home/consultants
   ![Screenshot 2025-03-18 200123](https://github.com/user-attachments/assets/e27f158b-92a2-48ba-8ac8-7dde52cb7010)
   ![Screenshot 2025-03-18 200304](https://github.com/user-attachments/assets/c5f2f557-ef6e-416d-81b5-41fc7bd940dc)


4. Change the default umask for the operator1 user:
-> (a)Open the user’s .bashrc or .profile file:
      sudo nano /home/ubuntu/.bashrc
   
   (b)Add the following line to set the umask:
      umask 0074
   ![Screenshot 2025-03-18 200510](https://github.com/user-attachments/assets/6f5fd1a7-4bc1-4244-becd-361dfd0bcc63)
   ![Screenshot 2025-03-18 200539](https://github.com/user-attachments/assets/81200c1f-f7e1-4565-86ff-627d06eac3b5)
   ![Screenshot 2025-03-18 200612](https://github.com/user-attachments/assets/abf15fbd-1d8d-45a7-9cde-1f81277679c6)


5. Confirm the umask:
-> su - ubuntu
   umask
   ![Screenshot 2025-03-18 200729](https://github.com/user-attachments/assets/869fe3a1-827d-42ba-a72d-bf757df62171)


