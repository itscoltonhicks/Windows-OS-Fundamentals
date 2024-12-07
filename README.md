# Windows OS Administration (Project Labs In Progress)
# Table of Contents
[Introduction](https://github.com/itscoltonhicks/Windows-OS-Administration/blob/main/README.md#introduction)

[Lab #1: Navigating the Windows Desktop](https://github.com/itscoltonhicks/Windows-OS-Administration/blob/main/README.md#lab-1-navigating-the-windows-desktop)

[Lab #2: The Windows File System](https://github.com/itscoltonhicks/Windows-OS-Administration/blob/main/README.md#lab-2-the-windows-file-system)

[Lab #3: Managing Windows User Accounts](https://github.com/itscoltonhicks/Windows-OS-Administration/blob/main/README.md#lab-3-managing-windows-user-accounts)

[Lab #4: Managing Windows User Permissions](https://github.com/itscoltonhicks/Windows-OS-Administration/blob/main/README.md#lab-4-managing-windows-user-permissions)

# Introduction

Cybersecurity is a subset of IT.

This is why it's important to have a strong foundation in system administration. Windows OS plays a crucial role in this foundation, as it is the most widely used operating system in business environments worldwide. Understanding Windows OS is key for effective system administration—it helps manage and protect critical infrastructure, support end-users, and drive automation and innovation. It's the backbone of business continuity and productivity.

In this project, I'll be covering the fundamentals of the Windows OS.

# Lab #1: Navigating the Windows Desktop

Let's start with the absolute basics of Windows OS. 

There are two ways to navigate Windows—through the Command Line Interface (CLI), or the Graphical User Interface (GUI). That being said, Windows is a "GUI-first" operating system. It makes navigating Windows systems accessible to a broader range of users (especially non-technical ones). 

Let's start by clicking the Windows icon located in the bottom left corner of the screen.

<img width="750" alt="Start Menu" src="https://github.com/user-attachments/assets/89409754-fd1e-4886-9065-03885f087e7a">

This opens the Start Menu, which is like Windows' central navigation hub.

This allows us to search for applications we want to use. Then we can simply select them to run them. For instance, we can select the ```copilot```application to run it.

<img width="750" alt="run copilot" src="https://github.com/user-attachments/assets/a36bcee6-9650-48bf-87ef-c2b4e15a29c4">

Within this menu view, we can also pin items directly to the Start menu or taskbar for quick access. 

Right-click them to open up a context menu and pin to start.

<img width="750" alt="pin to start" src="https://github.com/user-attachments/assets/97ead9ba-ad07-4f51-ac48-1f9f35022253">

Next we'll check out the taskbar, which is the bar at the bottom of the screen.

We can right-click it to open up another context menu. This allows us to access additional options such as changing taskbar setting or pinning open icons.

<img width="750" alt="task bar and context menu" src="https://github.com/user-attachments/assets/1b63c7a6-3b1a-42d6-8873-c5cc49a1bc5b">

There are a lot of things we can do with the taskbar. 

For instance, we can quickly clear our current view by selecting "Show the desktop." I'll open up copilot to illustrate this.

<img width="750" alt="show the desktop" src="https://github.com/user-attachments/assets/f8861fcc-583a-4e50-ba6c-2a13d3b3f43a">

This will close the open windows on the desktop. 

<img width="750" alt="cleared desktop view" src="https://github.com/user-attachments/assets/5199eacc-f486-4bfc-997f-b0efa2339b10">

We can go back to the context menu and select "show open windows" to bring the app back into desktop view.

<img width="750" alt="show open windows" src="https://github.com/user-attachments/assets/49df24a7-4d7c-4896-82a5-5a1fa9f0d5ee">

We can also customize the taskbar by accessing the taskbar settings again, and adjusting options such as locking it in place or hiding it automatically.

This time we'll use the "Taskbar settings" to view these options.

<img width="750" alt="taskbar settings" src="https://github.com/user-attachments/assets/6817ff3f-7db7-47c0-bd9d-7fe6787d403e">

Now we'll take a look at the file explorer tool. 

This is a common tool Windows users use to visually navigate all the files stored on the system.

<img width="750" alt="file explorer" src="https://github.com/user-attachments/assets/027c0401-1f1a-444d-89bb-146268cec8c5">

We'll also take a look at the Control Panel.

This is where we can interact and change settings to our operating system. Use the search box to open it up.

<img width="750" alt="Control panel" src="https://github.com/user-attachments/assets/77e4089f-f9e3-412b-a5a7-4aa912fd3c63">

Notice how there's a centralized interface where we can adjust a wide range of system and hardware configurations.

That being said, there is a more modern view of this called Windows Settings.

We can view this by going to our Start menu, typing in "Settings," and selecting the app. 

<img width="750" alt="Windows settings" src="https://github.com/user-attachments/assets/c6055b47-ff91-4109-84df-92cd7b67b2a7">

Notice the similarities with the Control Panel, yet with a more simple and modern view. 

This represents how, over time, Windows has tried to make their operating system more accessible and understandable to a broader range of users.

Next let's look at notifications by locating the Action Center, represented by a speech bubble icon on the bottom right of the taskbar.

<img width="750" alt="Action Center" src="https://github.com/user-attachments/assets/2e4f847a-2287-4aa0-bfde-33266f95bf81">

After selecting it, a window will pop up with notifications and additional settings. 

<img width="750" alt="notifications in action center" src="https://github.com/user-attachments/assets/10aa2ce5-75cc-450d-ae90-0c1ca94a3d2c">

Now we'll look at how to open multiple "views" or "desktops" by finding the Task View button on the taskbar.

It's located to the right of the search box.

<img width="750" alt="Task View Icon" src="https://github.com/user-attachments/assets/99403856-89e0-448b-9fb7-5de6f97f0da9">

It's designed to segment work into distinct categories, reducing cognitive load and improving focus on specific tasks or projects.

We can demonstrate the power of this by opening up applications in different "views," which is just a another way of saying virtual desktops. 

<img width="944" alt="Task View" src="https://github.com/user-attachments/assets/72f6c40e-383c-4885-881b-788873f23451">

We can use Task View to manage multiple desktops and applications simultaneously for increased productivity.

# Lab #2: The Windows File System
The Windows File System is a fundamental component of the Windows OS.

It's responsible for organizing, storing, and managing data on storage devices. Understanding it is key for system administrators and cybersecurity professionals. It provides the framework for file and folder organization, access control, and data management.

Let's dive into these key concepts.

Open up the File Explorer. 

Observe the navigation pane on the left side.

<img width="750" alt="Navigation Pane" src="https://github.com/user-attachments/assets/d9366032-b89c-4b41-ba35-e94d26b58157">

```Quick access``` contains pinned locations, functioning like favorite links or bookmarks in a browser. 

We can demonstrate this by pinning the ```This PC``` section to the Quick access section.

<img width="620" alt="Pin to quick access" src="https://github.com/user-attachments/assets/96e614a5-f08f-4f43-bb25-0a7701e9604d">

The ```This PC``` section used to be called ```My Computer``` in previous versions of Windows.

It contains attached drives, network shares, and storage devices.

Now let's take a look at the local disk, also called the C: drive. It's the main drive for our Windows File System. Think of it as the "root" of our file system. 

<img width="621" alt="Local Disk" src="https://github.com/user-attachments/assets/162c5689-98da-4d10-8fc7-a3a0fece3ea9">

Let's explore the ```Users``` folder in the C: drive.

This is where we can find a list of all the user profile folders on the system.

<img width="619" alt="Users Folder" src="https://github.com/user-attachments/assets/859bd74a-6836-40d2-839f-270ea6f71ecf">

Notice how we have ```Colton``` and ```Guest``` user profile folders.

Let's check out the ```Colton``` user profile folder.

<img width="620" alt="Colton User Profile Folder" src="https://github.com/user-attachments/assets/e9129cc9-3e9b-4f3f-8046-11cf254b0547">

Now we can see all of Colton's folders and files. 

If we click the ```Desktop``` folder, we'll see folders and files that live on our desktop. 

This represents the actual Desktop from the GUI.

<img width="800" alt="Desktop folder for Colton User" src="https://github.com/user-attachments/assets/0c1131b5-3b5a-47b0-812c-f2b173b86c83">

We can also navigate the File Explorer using the Address Bar at the top.

Using the same Desktop location, we can navigate there by typing out the following path:

````C:\Users\Colton\Desktop````

<img width="619" alt="Address Bar" src="https://github.com/user-attachments/assets/725c1096-1521-4d3e-9d3d-0a42ca03fde2">

Note that the address bar in File Explorer functions similarly to the address bar in a web browser.

The main difference is we're using a backslash character ```\``` to separate folders and subfolders.

Next let's learn to work with files in the File Explorer. I'll delete my test folder so we have a clean environment. We can create a file by right-clicking in the directory, hover over "new," and select "Text Document."

<img width="619" alt="New Text Document" src="https://github.com/user-attachments/assets/b30c2e97-54d6-40db-9093-3557ef050f46">

We can copy/paste that file to other locations. Let's put it in the ```Documents``` folder.

<img width="620" alt="Copy test file" src="https://github.com/user-attachments/assets/06430978-0bb2-4baf-afb2-ea1fd84ac16d">

Now it's been copied over there.

<img width="621" alt="paste test file" src="https://github.com/user-attachments/assets/aa6a3bf8-084f-48c7-a12a-8526d2d63eac">

I'll delete the file from the ```Documents``` folder before moving forward.

Next, we can cut and paste a file. This deletes it from its original location and brings it somewhere else. 

Right-click the ```test file``` in the ```Colton > Desktop``` folder and select "Cut."

<img width="750" alt="cut test file" src="https://github.com/user-attachments/assets/9ebb419e-4f0f-4ca7-9786-66de594387ca">

Open the ```Colton > Documents``` folder, right-click anywhere in the empty space, and select "Paste."
 
<img width="750" alt="paste the cut test file" src="https://github.com/user-attachments/assets/ebc5a7f1-196f-4a47-9cf6-7dec7ba9e68f">

Notice how we can no longer see the file on the Desktop. This is because the "Cut" feature deleted it from the original location (the Desktop folder). 

Additionally, we can replace a file by selecting "copy" on a new ```test file``` in a different location, then pasting it into the ```Document``` folder where the file with the same name exists. 

An alert will pop up. And we'll select "Replace the file in the destination."

<img width="619" alt="replace a file" src="https://github.com/user-attachments/assets/577b9529-12f9-4e6f-a3b4-ba16b1a3d606">

Finally, we have the option to delete files.

Right-click the file and select "Delete."

<img width="619" alt="Delete a file" src="https://github.com/user-attachments/assets/31ff79d9-009e-4b31-82e9-c37bc05e64c5">

Observe that the Recycle Bin at the top of the left screen is now filled. 

Our file isn't permanently deleted yet. It's just ready to be deleted in the Recycle Bin. Windows has this function to prevent accidental deletions. 

<img width="750" alt="Recycle Bin" src="https://github.com/user-attachments/assets/8d78c7f2-99d0-4801-b64f-8bf671295e44">

Let's actually delete the file by opening up the Recycle Bin from the desktop, right-clicking anywhere in the white space inside it, and selecting "Empty Recycle Bin."

<img width="750" alt="empty recycle bin" src="https://github.com/user-attachments/assets/ee403816-46c8-4d95-a843-289c398fdc29">

# Lab #3: Managing Windows User Accounts

In this lab we'll explore the concepts of managing user accounts on Windows.

For context, I'm using Windows 10. Now let's get started. We'll click on the Start Menu on the bottom left corner of the screen. 

From here, we'll type in Computer Management and select it.

<img width="750" alt="Selecting Computer Management" src="https://github.com/user-attachments/assets/c81d42ee-b131-45c6-b041-c194258799e6">

This allows us to manage all the local computer settings for this endpoint. 

A navigation menu appears to the left. This contains categories for various management options.

<img width="650" alt="Computer Management view" src="https://github.com/user-attachments/assets/35298c7f-02d3-43fa-b9fa-a8469d19c2ee">

Expand "Local Users and Groups" by clicking on it. Then click on the "Users" folder to display a list of current users.

Notice how there are four different user accounts.

<img width="735" alt="List of user accounts" src="https://github.com/user-attachments/assets/5d8bcf9d-9771-4d34-a314-cc7116264c1e">

Next let's create a new user on the local computer.

Right-click in the empty space or directly on the "Users" folder. Then select "New User" to initiate the creation of a new user. 

<img width="733" alt="Create a new user" src="https://github.com/user-attachments/assets/14116ed7-d231-4b5d-b1c2-c9e2c20421fd">

Now we'll need to fill in the user details—username, full name, and password.

Let's also uncheck the checkbox for "User must change password at next logon." This prevents the mandatory password change on first login.

<img width="734" alt="info for new user account" src="https://github.com/user-attachments/assets/d48f1531-a9e3-430f-afcf-95f0f67d2517">

Once we click "Create," a new user will be created and appear on the list of users.

<img width="732" alt="New account successfully created gui" src="https://github.com/user-attachments/assets/cbc73e5f-c210-4527-84f3-417f6d9922c5">

We can look at the properties of our new user.

This is where we can manage user settings and access. Double-click ```ColtonTest``` and select "Properties."

<img width="732" alt="user account properties" src="https://github.com/user-attachments/assets/1d356105-1890-42f4-8fbb-54214fdac2c8">

Now we'll see different tabs for managing our new user. 

<img width="732" alt="ColtonTest Properties" src="https://github.com/user-attachments/assets/d1ce5898-ac25-4b3b-8642-f964d653180c">

Since I'm using a basic Windows 10 VM, I'm only seeing three tabs. I'd see a lot more if I was using an Enterprise Windows Server. For example, here's the same user properties window within an enterprise server:

<img width="525" alt="Enterprise server user properties" src="https://github.com/user-attachments/assets/39a6f207-95ce-48a8-9c75-fdc5a0db9b37">

Here's a brief description of each tab:

- **General:** Set password restrictions and account controls. 
- **Member Of:** Assign group permissions to the user and grant access to various resources.
- **Profile:** Configure desktop settings and script paths to customize the user's environment.
- **Environment:** Set environment variables that'll apply when the user logs in.
- **Sessions:** View and manage active session settings for the user. 
- **Dial-In:** Set permissions for remote access to the server.
- **Remote Desktop Services Profile:** Configure settings for the user's remote desktop experience.
- **Remote Control:** Set permissions for remote control of the user session.

Click OK to exit the new user's properties.

Next let's initiate a password change.

Right-click on ```ColtonTest``` and click "Set Password." 

<img width="733" alt="Set password" src="https://github.com/user-attachments/assets/61e9d10a-a83d-49f1-90c5-4b013bcded93">

Click "Proceed" when the confirmation dialog pops up.

<img width="733" alt="Proceed with password change" src="https://github.com/user-attachments/assets/e45e1225-da7b-4f2f-bced-642061507c9a">

Then set a new password for the user, clicking OK when we're done.

<img width="731" alt="Set new password" src="https://github.com/user-attachments/assets/e7df82a3-a546-429b-8e44-48814a0ae54e">

We can also disable an account. 

Right-click on ```ColtonTest``` again, go to "Properties," and check the "Account is disabled" checkbox. Then click "Apply" and "OK."

<img width="734" alt="Disable user account" src="https://github.com/user-attachments/assets/b1745154-ffb3-4a74-9d85-fe0d6a4415c3">

Next we'll modify group memberships. 

Right-click on ```ColtonTest```, select "Properities," go to the "Member Of" tab, then click "Add."

<img width="737" alt="Add user to group" src="https://github.com/user-attachments/assets/76325a3f-f4e9-4f21-94ab-96acb4515448">

In the field provided, type "Admin" and click "Check Names to validate the entry.

<img width="736" alt="admin name not found" src="https://github.com/user-attachments/assets/a3436f63-ca62-4fd6-b37d-f11825ff5ab7">

There doesn't seem to be a specific group called Admin. 

However, there is a group called "Administrators", which we can find in the "Groups" folder.

<img width="732" alt="Administrators group" src="https://github.com/user-attachments/assets/a328b37c-a8f4-4907-b411-95f6a563dd8c">

Let's add that group to our ```ColtonTest``` user. We'll type "Administrators" and click OK twice to add the user to this group. Here's the end result.

<img width="730" alt="Administrators added as a group" src="https://github.com/user-attachments/assets/4140f9bf-9021-4b61-85a1-037020e3d21e">

Then we'll just remove the user from the Administrators group, as we don't want it to have privileged access.

Select the group name and click "Remove."

<img width="731" alt="Remove group membership" src="https://github.com/user-attachments/assets/f176950a-e1ac-42cc-96d5-92bc557d2382">

Close the properties window.

Let's clean up our environment and delete the new user.

Right-click on ```ColtonTest``` and select "Delete." 

<img width="730" alt="Delete user account" src="https://github.com/user-attachments/assets/c7829129-2ee4-41b2-ab72-d845bae1d520">

When prompted, click "Yes" to confirm.

We're done with the Computer Management window now, so we can close it. 

To finish this section, we'll work with user accounts over the terminal. So let's open up a PowerShell terminal in Windows. 

This is a command-line interface where we can execute PowerShell commands and scripts, allowing us to interact with the operating system and automate tasks.

<img width="750" alt="Powershell app" src="https://github.com/user-attachments/assets/55717182-e5a7-4d30-90d3-28718ec29bd8">

We can manage user accounts by using the ```net user``` command. 

Then we'll add specific flags or options depending on our goals. Let's start by adding a new user through the terminal:

```
net user AnotherColtonUser Password123! /add
```

<img width="800" alt="Add user in powershell" src="https://github.com/user-attachments/assets/500a8d71-dfc4-4a19-8270-3fd9ab30495d">

Quick command breakdown:

- ```net```: A built-in command line utility in Windows. Allows us to manage various network settings and functions.
- ```user```: When following the ```net``` command, it specifies that we want to manage user accounts.
- ```AnotherColtonUser```: The user account we want to add.
- ```Password123!```: The password we want to associate with the user account.
- ```/add```: The flag that specifies we want to add a user.

Next we can update the password by using a similar command without the ```/add``` flag. 

Then just input a new password. For example:

```
net user AnotherColtonUser NewPassword12345!
```

<img width="537" alt="update password in powershell" src="https://github.com/user-attachments/assets/076a5d0d-e278-48d0-8b59-6e05f4647d95">

Quick command breakdown:

- ```net user```: The command for managing user accounts.
- ```AnotherColtonUser```: The existing user account.
- ```NewPassword12345!```: The new password. The computer already knows the user account exists. So typing in a new password will automatically update it.

We can also specify whether or not we want the account active (or disabled). 

Let's start by making sure it's active:

```
net user AnotherColtonUser /active:yes
```

<img width="392" alt="active user account command" src="https://github.com/user-attachments/assets/46d6b355-3350-40b2-9720-6ed9cb0ec04d">

Quick command breakdown:

- ```net user```: The command for managing user accounts.
- ```AnotherColtonUser```: The user account we want to modify.
- ```/active:yes```: The ```/active``` flag specifies that we want to modify the active status of the user account. And the ```:yes``` gives is a value, indicating that we want it to be active.

To disable the account, we'll use the same command with a tiny tweak:

```
net user AnotherColtonUser /active:no
```

<img width="798" alt="disable user account in powershell" src="https://github.com/user-attachments/assets/d3a29fe1-0652-43cd-89f8-7ccbdb470248">

As you can see, we just gave the ```/active``` flag a value of ```no```. This disables the user account. We can check in the Computer Management GUI window to make sure it's disabled. Notice the "down arrow" on the user icon. This indicates it's disabled.

Finally, we'll delete the user from the command line.

Here's the final command:

```
net user AnotherColtonUser /delete
```

<img width="938" alt="delete user account in powershell" src="https://github.com/user-attachments/assets/3ee39201-7392-4c11-a0ec-30c1b53d89a2">

Quick command breakdown:

- ```net user```: The command for managing user accounts.
- ```AnotherColtonUser```: The user account we're deleting.
- ```/delete```: The flag specifying we're deleting the account.

As we can see in the image, the ```AnotherColtonUser``` account is gone.

# Lab #4: Managing Windows User Permissions
Next we'll dive deeper into Windows user permissions.

We'll assign and modify user permissions. That way, we can control access to files and folders on the Windows OS. We'll do this in the GUI and CLI.

Let's start in the GUI by opening up the File Explorer. 

Navigate to the ```Documents``` folder by selecting it from the left-hand quick access sidebar.

<img width="618" alt="Documents with lab folder" src="https://github.com/user-attachments/assets/ae45605f-6c7a-4cef-94ae-ec7745dbb215">

I created a folder called ```Lab Folder``` to demonstrate the next steps. 

Right-click on it to bring up a context menu. And from the available options, select "Properties," then the "Security" tab at the top.

<img width="617" alt="Lab folder properties" src="https://github.com/user-attachments/assets/94654d15-3c4b-434f-b304-f287751f814d">

We'll see a list of users or groups under "Group or user names." 

These are groups or users that have permissions set for this folder. If we select one of them, we'll see the specific permissions for the folder in the box below.

<img width="618" alt="3  Permissions for Colton" src="https://github.com/user-attachments/assets/921e3d77-2e3b-48ff-9757-1003e1fac73a">

We can modify permissions by clicking the "Edit" button under the list of users or groups. 

This opens up a new window where we can select a specific user or group. Then we can choose to "Allow" or "Deny" specific permissions—such as reading, writing, or full control of the folder.

<img width="618" alt="4  Edit permissions gui" src="https://github.com/user-attachments/assets/222f9bbe-fcb1-4313-8a0b-10b9c805ee02">

We can also grant permissions for a new group or user.

Click the "Add" button in the permissions editing window. In a new window and in the field labeled "Enter the object names to select," type "Guest".

The ```Guest``` user is a common account that is left on by default.

<img width="618" alt="5  Add a new user for permissions" src="https://github.com/user-attachments/assets/58f81a13-c15a-4769-be0d-aca97a6d97fd">

After entering the name, click the "Check Names" button to verify that the entered name corresponds to a recognized user or group. 

It'll get underlined if it's valid. Click "OK."

<img width="619" alt="6  Check names for guest user" src="https://github.com/user-attachments/assets/3ffd061e-0fc6-43b6-b85b-bbca3fed5f2d">

Once that's done, click "Apply" and "OK" to grant permissions to the ```Guest``` user.

There are also advanced settings we can configure for permissions. 

Click on the "Advanced" button located at the bottom-right of the security tab.

<img width="618" alt="7  Advanced permissions settings" src="https://github.com/user-attachments/assets/7882d1e8-78e7-4265-8e92-17b9a65a58e4">

Here we can manage inheritance settings.

<img width="619" alt="8  Advanced security settings for lab folder" src="https://github.com/user-attachments/assets/78f21b4d-2e30-49cc-842d-a13ef558a149">

Inheritance means that all sub-folders and files will follow the security permissions of its parent folder. 

So for our example, when inheritance is enabled for our ```Documents``` folder, every sub-folder and file nested within it will have the same permissions. 

Let's illustrate this by creating a new folder within our parent ```Lab Folder```folder and display the security permissions.

<img width="617" alt="Inherited Permissions Folder with guest permissions inherited" src="https://github.com/user-attachments/assets/e50fafd0-db5e-44cc-a041-54fd08ee9a9c">

Notice how the new folder inherited the same permissions from its parent folder.

Inheritance can save us a lot of time. However, if the parent folder's permissions are misconfigured, this can cause a lot of issues. We can also "Disable Inheritance" by clicking the button to make sure the parent folder's permissions doesn't influence our existing folder.

Let's do that with our initial ```Lab Folder``` folder.

<img width="617" alt="10  Disable inheritance" src="https://github.com/user-attachments/assets/a6c6a982-4614-433a-8d57-4ce5f7939e96">

Now let's clean our environment by closing out the windows and removing the Guest user from having permissions.

Select the appropriate account and click "Remove."

<img width="614" alt="Remove guest user" src="https://github.com/user-attachments/assets/26956b3c-901b-49db-a8ad-a3bd431c00ea">

We'll finish this section on the command line. Hop over into the "Command Prompt" terminal, also referred to as the ```CMD``` utility. We could technically use Powershell. But the ```CMD``` terminal allows us to use simple and quick commands for basic administrative tasks. 

Type in "CMD" in the search box and select it.

<img width="750" alt="12  Open Command prompt" src="https://github.com/user-attachments/assets/b0994c41-a0b4-40ad-9217-a8d2e07084e1">

First we need to navigate to the ```Documents``` folder. This is where our ```Lab Folder``` folder is located. 

We'll do this by using a command called ```cd``` to "change directories." 

```
cd Documents
```

<img width="406" alt="13  Change directories" src="https://github.com/user-attachments/assets/8f37db40-21cf-4b1a-bc55-89200736a7ab">

Notice that we've changed our existing directory to the ```Documents``` folder. Now we can run commands to this specific location on disk.

Next we'll run a command called ```icacls```.

It stands for "integrity control access control list. It allows us to manage access control lists and modify permissions.

Let's give the ```Guest``` user "read" permissions to the ```Lab Folder``` folder:

```
icacls ".\Lab Folder" /grant Guest:(R)
```

<img width="800" alt="14  Grant Guest read access via cmd" src="https://github.com/user-attachments/assets/1acf97f4-67fe-4f33-be3a-c5c1bc732864">

Quick command breakdown:

- ```icacls```: This command allows us to manage and modify permissions. 
- ```".\{foldername}"```: This specifies which folder we want to modify permissions for. The ```.\``` means the "current directory."
- ```/grant```: This flag indicates we want to "grant" permissions to this folder.
- ```Guest:(R)```: The ```Guest``` value specifies which user or group will be granted access to our ```folder``` folder. And the ```:(R)``` value means we want the ```Guest``` user to have "read" permissions.

Observe how when we open up the security permissions in the GUI for our ```Lab Folder```folder, we'll see that the ```Guest``` account has been granted "read" access.

We can also deny access on the command line. 

We'll use the same command—except this time, we'll use the ```/deny``` flag:

```
icacls ".\Lab Folder" /deny Guest:(R)
```

<img width="958" alt="15  Deny guest permissions" src="https://github.com/user-attachments/assets/31dfede5-b34b-43b1-b3ac-942e4441016a">

If we go back to our security permissions in the GUI, we'll see that the ```Guest``` user no longer has "read" access.

We can also completely remove the ```Guest``` user from having access to the folder. 

We'll use the same command with a different flag:

```
icacls ".\Lab Folder" /remove Guest
```
<img width="800" alt="16  Remove Guest permissions" src="https://github.com/user-attachments/assets/1292eddd-e76b-46f8-a150-ff3dcec7cebc">

Now our ```Guest``` user has been completely removed from having access to our ```Lab Folder``` folder.
