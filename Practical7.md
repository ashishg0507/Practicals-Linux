1. chown Command
-> (a)Change the owner of a file:
      sudo chown user1 file.txt
   ![Screenshot 2025-03-18 223941](https://github.com/user-attachments/assets/77725dd5-9d8c-4b0b-8bc8-6e7174fd7006)

   (b)Change the owner and group of a file:
      sudo chown user1:usergroup file.txt
   ![Screenshot 2025-03-18 224054](https://github.com/user-attachments/assets/07a5b71a-7ccc-48b6-9dc5-e44e69fe2164)

   (c)Change only the group:
      sudo chown :usergroup file.txt
   ![Screenshot 2025-03-18 224222](https://github.com/user-attachments/assets/3f84a5a9-2b22-4513-800b-08441fcda986)

   (d)Change ownership recursively (for directories):
      sudo chown -R user1:usergroup /path/to/directory
   ![Screenshot 2025-03-18 224329](https://github.com/user-attachments/assets/2cd21e60-9abf-4cbf-a4c3-ab8da9fd080a)

   (e)Transfer ownership to root:
      sudo chown root file.txt
   ![Screenshot 2025-03-18 224435](https://github.com/user-attachments/assets/295ce607-b8f5-4365-b3fa-66e4f4593629)

   (f)Use --from to change from a specific owner:
      sudo chown --from=current_owner new_owner file.txt
   ![Screenshot 2025-03-18 224603](https://github.com/user-attachments/assets/ca59f328-83f3-462d-ac6d-443ae0754609)


2. chmod Command
-> (a)Give execute permission to the user:
      chmod u+x file.txt
   ![Screenshot 2025-03-18 224802](https://github.com/user-attachments/assets/eb427d3f-3fa9-4128-8e22-07d2db7a56bf)

   (b)Remove write permission for others:
      chmod o-w file.txt
   ![Screenshot 2025-03-18 224839](https://github.com/user-attachments/assets/bdab0042-c1be-49d2-953a-3682ed497ccd)

   (c)Give read and execute permission to the group:
      chmod g+rx file.txt
   ![Screenshot 2025-03-18 224912](https://github.com/user-attachments/assets/c127a27b-d583-4cc4-a8df-2838167466e6)

   (d)Set specific permissions:
      chmod u=rwx,g=rx,o=r file.txt
   ![Screenshot 2025-03-18 225000](https://github.com/user-attachments/assets/03104c31-2b8a-45bd-b9bb-cb98496e2d5c)

   (e)Set permissions to rwxr-xr-- using octal mode:
      chmod 754 file.txt
   ![Screenshot 2025-03-18 225000](https://github.com/user-attachments/assets/c14e6e59-5ef7-4ba7-8dd8-1a58789cc465)

   (f)Recursive Change of Permissions:
      chmod -R 755 /path/to/directory
   ![Screenshot 2025-03-18 225116](https://github.com/user-attachments/assets/075ab9dd-ffda-4be1-a041-65c64ac330f1)

   (g)Change permissions based on existing files:
      chmod --reference=ref_file.txt target_file.txt
   ![Screenshot 2025-03-18 225232](https://github.com/user-attachments/assets/a12da36d-0dbd-4e5c-b218-665ac1686c03)

 

