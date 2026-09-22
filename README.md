# Removing-a-User-from-a-Group-in-AWS-using-IAM
Detailed walkthrough of removing a user from a group

First you go into users using your root account
<img width="960" height="1080" alt="image" src="https://github.com/user-attachments/assets/095deb8e-7bbe-41f2-a99e-7d954ee4860d" />
Currently, the IAM user Robert has access to the admin group
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/3f601671-b6b0-4e1a-bec1-635c61b2bfff" />
You select the user you want to remove 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cd8ef9ff-f498-4707-9ac4-07872f56e899" />
Then you select the admins group
<img width="1920" height="1078" alt="image" src="https://github.com/user-attachments/assets/1bb656cd-8c2e-4c4c-b756-c2a84e77ae12" />
Select the group name
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/05f4ee30-1dad-4faa-992b-7859bd0ed619" />
Check the box next to the user or users you would like to remove, and simply press Remove next to the Add users button
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0ecc95ee-6594-4772-a830-0f0a1a8c60a6" />
Confirm the removal
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cd57f234-8bc4-41be-9434-5b048c8f1142" />
User was successfully removed from the admin group
<img width="1920" height="410" alt="image" src="https://github.com/user-attachments/assets/4399bd85-4b2e-4c08-a34a-8939b94db546" />
To confirm this, you can refresh the IAM users account and their access to group is now denied
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c2c6700a-84aa-4e1e-9fae-72d33295b067" />
