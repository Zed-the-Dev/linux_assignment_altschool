# Linux User Management Guide

In this guide, we'll cover the process of creating and managing users on a Linux system using the command line.

1. Open a terminal.

2. ![Creating a new user](1.png)
   I created a user named "tobiloba".

3. ![Set an Expiry Date](2.png)
   The expiry date of the user account was set to two weeks after it was created.

4. ![Confirmation of the expiry date](3.png)
   The expiry date of the user account was confirmed.

5. ![Prompt User to Change Password](4.png)
   The user was prompted to change their password on their next login.

6. ![Creating a new group](5.png)
   I created a new group called "altschool".

7. ![Attach User to a Group](9.png)
   I added the user "tobiloba" to the "altschool" group.

8. ![Allow "altschool" Group to Run `cat` on /etc/](7.png)
   I edited the sudoers file to allow the "students" group to run the `cat` command on files in the `/etc/` directory.

9. ![Create Another User Without a Home Directory](8.png)
   I created a user named "nohometobiloba" without a home directory.
