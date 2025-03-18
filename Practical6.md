1. Create the operator1 user:
-> sudo useradd -m operator1
   ![Screenshot 2025-03-18 214350](https://github.com/user-attachments/assets/46b29714-05d8-4b51-96ec-ba4d9d1a8448)


2. Confirm that operator1 exists:
-> cat /etc/passwd | grep operator1
   ![Screenshot 2025-03-18 214400](https://github.com/user-attachments/assets/335f6e3a-8e67-49a8-b892-91144ca20bfd)


3. Set the password for operator1:
-> sudo passwd operator1
   ![Screenshot 2025-03-18 214434](https://github.com/user-attachments/assets/cf8dc1fc-1bbb-4b73-aeec-9f403ee700fb)


4. Create operator2 and operator3 users:
-> sudo useradd -m operator2
   sudo passwd operator2
   sudo useradd -m operator3
   sudo passwd operator3
   ![Screenshot 2025-03-18 214630](https://github.com/user-attachments/assets/d7e30833-1dba-48d2-b7ab-63bc670101c7)


5. Update the comment for operator1 using usermod -c:
-> sudo usermod -c "System Operator 1" operator1
   ![Screenshot 2025-03-18 214742](https://github.com/user-attachments/assets/ae13db46-cdcf-4dd2-b061-9c43b06471cf)


6. Remove the operator3 user:
-> (a)To delete operator3 without removing the home directory:
      sudo userdel operator3
    ![Screenshot 2025-03-18 214832](https://github.com/user-attachments/assets/7842d158-4e49-40ad-ad7a-22a310f842f9)

      (b)To delete operator3 and its home directory:
      sudo userdel -r operator3
    ![Screenshot 2025-03-18 214942](https://github.com/user-attachments/assets/009d03d1-c9c5-4976-90d3-72a774910134)


