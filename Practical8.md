1. Shell Script to Print System Information
-> (a)Create a file named system_info.sh:
   ![Screenshot 2025-03-18 151104](https://github.com/user-attachments/assets/0b855697-bdbb-4cfa-9155-9f51596f27ce)

   (b)Make the script executable:
      chmod +x system_info.sh

   (c)Run the script:
      ./system_info.sh
   ![Screenshot 2025-03-18 151419](https://github.com/user-attachments/assets/475f306c-100e-485d-8736-75be52322bc0)

   
2. Shell Script to Perform Basic Mathematical Calculation
-> (a)Create a file named calc.sh:
   ![Screenshot 2025-03-18 152443](https://github.com/user-attachments/assets/f4163429-b2aa-4801-9de9-1366d89bcb8f)

(b)Make the script executable:
chmod +x calc.sh

(c)Run the script:
./calc.sh
![Screenshot 2025-03-18 152404](https://github.com/user-attachments/assets/b4d838a6-2164-40e1-942f-235bb2a4288c)


3. Use Redirection Operators to Store Output of Commands
-> (a)Redirect stdout to a file:
      ls > output.txt
   ![Screenshot 2025-03-18 215548](https://github.com/user-attachments/assets/79b1986b-0b5a-482a-aa58-9d1ab57cbfe6)

   (b)Append output to an existing file:
      date >> output.txt
   ![Screenshot 2025-03-18 215814](https://github.com/user-attachments/assets/74bd32ab-1039-4695-8c67-c599d5e961b9)
   ![Screenshot 2025-03-18 215852](https://github.com/user-attachments/assets/e4c92611-ecc0-497f-b45b-83fbe6a28aaa)

   (c)Redirect stderr to a file:
      ls nonexistentfile 2> error.txt
   ![Screenshot 2025-03-18 215950](https://github.com/user-attachments/assets/6f118bb3-e50e-44d3-b54c-fda82a4d0596)
   
   (d)Redirect both stdout and stderr to a file:
      ls . nonexistentfile &> all_output.txt
   ![Screenshot 2025-03-18 220149](https://github.com/user-attachments/assets/2086b102-c905-4d56-a92b-a39fd43a0bad)

   ![Screenshot 2025-03-18 220051](https://github.com/user-attachments/assets/2071980c-951e-42f7-83e5-ce2376e9a6e6)

   (e)Pipe output to another command:
      cat file.txt | grep "keyword"
   ![Screenshot 2025-03-18 220404](https://github.com/user-attachments/assets/d096aadd-4f6e-49ba-80f8-e50f7b0d172d)



