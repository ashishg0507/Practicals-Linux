1. Open the editing_final_lab.txt file in Vim and Nano:
-> VIM- vim editing_final_lab.txt
   NANO- nano editing_final_lab.txt
   ![Screenshot 2025-03-18 194331](https://github.com/user-attachments/assets/308959a7-b313-4015-b56d-ff593fe965b5)
   ![Screenshot 2025-03-18 194522](https://github.com/user-attachments/assets/17ebd8a1-b3dd-46d8-9a54-f29645322e0b)

   ![Screenshot 2025-03-18 194648](https://github.com/user-attachments/assets/7b6106c1-c24f-442f-acea-b93aef9b11f3)
   ![Screenshot 2025-03-18 194730](https://github.com/user-attachments/assets/9a62a4d0-982b-4c78-ad1f-e27cfdc66400)


3. Use the lab_file shell variable:
-> lab_file="editing_final_lab.txt"
   vim $lab_file
   ![Screenshot 2025-03-18 194945](https://github.com/user-attachments/assets/ff10131d-1193-4abb-a0a2-e61447ab0818)

   
5. Enter visual mode in Vim:
-> Open Vim.
   Press v to enter visual mode.
   ![Screenshot 2025-03-18 195044](https://github.com/user-attachments/assets/f6433970-58b6-4431-96c3-b8a8bfa530d1)

   
7. Remove the last seven characters from the first line:
-> Press ^ (caret) to go to the beginning of the line.
   Press v to start selecting characters.
   Move to the end of the line using $.
   Press d7 to delete the last 7 characters.


8. Preserve only the first four characters of the first column:
-> Go to the beginning of the line using 0.
   Press v and move to the 4th character using l (right arrow).
   Press d to delete everything after the 4th character.


9. Save and exit:
-> :wq

