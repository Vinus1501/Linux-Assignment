**Assignment-4**
**

Q1.	Create a directory named "MyFiles" in your home directory. Navigate into this directory and list its contents.
![1](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/15d35942-8d12-4fde-bcba-82958ffa6761)
**
Q2.	Copy a file named "document.txt" from your home directory to the "MyFiles" directory. Move the file to a subdirectory named "Documents" within "MyFiles."
![2](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/3ab564ee-0925-4876-9c8d-03d58b4869eb)

**
Q3.	Create an empty file named "notes.txt" in the "MyFiles" directory. Afterward, delete the file.
![3](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/f6a77344-76d7-4664-a8d8-086e15ed2680)

**
Q4.	Create a hard link named "hardlink.txt" for the file "document.txt" within the "Documents" subdirectory. Also, create a symbolic link named "symlink.txt" in the same location.
![4](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/acbfeb92-eca9-4c21-aac3-33bec3f3e1b5)

**
Q5.	In the "MyFiles" directory, use a single command to list all files that start with the letter "a" and have a ".txt" extension.
![5](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/df98c724-ce26-4362-95ed-cc685e4ba9c8)

**
Q6.	Rename all files in the "Documents" subdirectory of "MyFiles" with a ".bak" extension. Ensure the original file names are preserved.


Q7.	Use a wildcard character to copy all files from the "Documents" subdirectory of "MyFiles" to another directory named "Backup."
![7](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/ecb5e7d2-e611-40f4-90dc-a6ae2f4134c0)
**
Q8.	Execute the ls command to list files in the current directory. Save the output to a file named "file_list.txt." Then, use a pipe to filter the output through grep to display only files with a ".txt" extension.


![Screenshot from 2024-02-03 16-54-02](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/9912ce72-1e70-423d-aa13-4b36665d8fe0)
**
Q9.	Create a new text file named "my_notes.txt" using the touch command. Open the file in the Vim editor, add some text, and save the changes.

![9](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/33d4d95e-bda8-4a27-a659-b463736dd39a)
**
Q10.	Run the date command and store the output in a variable named "current_date." Display the value of the variable and append it to the "my_notes.txt" file.

![10](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/fa683391-9809-4485-9141-d42b329567cf)
**
Q11.	Edit the Bash startup script (e.g., .bashrc) to set an environment variable named "CUSTOM_PATH" to a specific directory path. Ensure the variable is available in new shell sessions.

Q12.	Use the echo command to add a new line of text to the "my_notes.txt" file without overwriting existing content. Verify that the new text is appended.

![12](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/312b2788-4ff9-4dce-bd11-a6402443a600)
**
Q13.	List all files in the "/etc" directory, filter the output to include only those containing the word "conf," and save the result to a file named "conf_files.txt."

![13](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/95c623f6-74ef-4cdb-ac8f-c8fbd01e0512)
**
Q14.	Open the "my_notes.txt" file in Vim. Use Vim's search and replace functionality to replace all occurrences of the word "important" with "critical." Save the changes.
      ![image](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/9ba9990b-b535-4098-b55a-03d5ce60f202)
**
      
Q15.Create a new user account named "john_doe." Set the user's home directory to "/home/john_doe" and assign the user to the "users" group.

![15](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/897070e2-5896-4a48-bc66-637b10c8a698)
**
Q16.	Add the user "john_doe" to the sudoers file, allowing them superuser privileges. Confirm that "john_doe" can execute commands with sudo.

![16](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/82b3e0aa-e5b6-4f92-8697-9fc670150d71)
**
Q17.	Modify the user account "john_doe" to change the default shell to "/bin/bash" and set the account's expiration date to one month from today.

![17](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/e85ed3be-8769-43f9-a4ef-d777d3703ecc)
**
Q18.	Create a new group named "development_team." Add "john_doe" to this group and verify the group's existence.

![18](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/d6a0d969-998c-4c10-aafa-ed760ddd6422)
**
Q19.	Remove "john_doe" from the "users" group and add them to the "development_team" group. Confirm the changes.

![19](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/ede3c188-af8e-40e9-87cd-7395d59e23fb)
**
Q20.	Delete the user account "john_doe" and ensure that their home directory is also removed.

![20](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/2c6d4614-a386-4c4d-bab9-7b9947cb0ef4)
**
Q21.	Delete the group "development_team" and ensure that all users previously belonging to the group are appropriately handled.

![21](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/37da23a8-2fc8-4483-9b7f-5f82b7452c87)
**
Q22.	Implement a password policy that requires users to change their passwords every 90 days. Apply this policy to all existing and new user accounts.

![22](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/f414dab9-4bd0-4865-abb4-e2c1ede0b834)
**
Q23.	Manually lock the user account "john_doe." Attempt to log in as "john_doe" to confirm that the account is locked. Then, unlock the account.

Q24.	Use the id command to display detailed information about the "john_doe" user, including user ID, group ID, and supplementary groups.

![24](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/d5c589df-c075-4fe6-8b6c-f0d9716048bf)
**
Q25.	Configure the password aging for the user "john_doe" to enforce a maximum password age of 60 days. Confirm that the changes take effect.

![25](https://github.com/Vinus1501/Linux-Assignment/assets/153744714/8121ebc5-f97e-4534-9cc6-b263150f4106)
**


