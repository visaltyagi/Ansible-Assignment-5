# Ansible-Assignment-5
Install Java and MySQL on Test and Prod Nodes Using Ansible Roles - Ansible Assignment 5

Replace index.html With Original index.html file using Ansible Roles

**For the detailed solution to this assignment, click this link:**  https://medium.com/devops-guides/install-java-and-mysql-on-test-and-prod-nodes-using-ansible-roles-ansible-assignment-5-b3a17a1a983a

**Step 1:** Use an additional two instances here.

**Step 2:** Update the Slave3 & Slave4 Machines.

**Step 3:** Paste the public key content in the authorized_keys file in both Slave3 & Slave4 machines.

**Step 4:** Create two groups of slave names as test and prod. Paste these groups in the hosts file.

**Step 5:** Create the test and prod role here.

**Step 6:** Go to the tasks section in both the test and prod roles. Paste the Java and MySQL installation code in the install.yaml file.

**Step 7:** Include the install.yaml file to main.yml file.

**Step 8:** Create a play5.yaml file.

**Step 9:** Runt the play5.yaml via ansible playbook run command.

**Step 10:** "Java" and "MySQL" will be successfully installed on "Slave1 & 2" & "Slave3 & 4" respectively.

**Step 11:** Check the Java and MySQL versions using the commands.
