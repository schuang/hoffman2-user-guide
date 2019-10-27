Using Putty
================


**Step 1**. Start PuTTY by double-clicking the PuTTY shortcut icon on your desktop, or double-clicking putty.exe in your PuTTY installation directory. The PuTTY Configuration window will open.


**Step 2**. Enter the host name::

  hoffman2.idre.ucla.edu

in the appropriate text entry box and under the Protocol: heading select SSH. Enter Hoffman2 in the Saved Sessions text box.


**Step 3**. On the left side of the window there is a panel labeled Category:. If you see a plus sign (+) next to the word Connection, click on it. It will turn to a minus sign (-) and additional entries will appear under Connection. One of them will be SSH. If you see a plus sign (+) next to the word SSH, click on it. It will turn to a minus sign (-) and additional entries will appear under SSH. Click on SSH in order to modify the SSH connection options.


**Step 4**. Select the 2 radio button under the Preferred SSH Protocol Version: heading.


**Step 5**. If you are going to use PuTTY in conjunction with an X-server:
Enter the xterm command, as follows, in the Remote command: text box::

  /usr/bin/xterm -ls -sb -sl 1000

Enable X11 forwarding by clicking on Tunnels in the Category panel at the left. Then make sure Enable X11 forwarding is checked.

**Step 6**.  Click Session in the Category panel at the left. Click the Save button to the right of the Saved Sessions list to save your configuration options.


**Step 7**. Click the Open button at the bottom of the PuTTY Configuration window. The first time you access the cluster, you will see a Security Alert window. You can check the fingerprint shown against Login Node Fingerprints. Click the Yes button.


**Step 8**. A PuTTY login window will appear. Enter your Hoffman2 login ID and password.


**Step 9**. Fix your PuTTY desktop shortcut by right clicking your PuTTY shortcut icon. Select the Properties menu item. Select theShortcut tab. Add @Hoffman2 as the target where Hoffman2 is the name that you entered in the Saved Sessions text box in step 2. Click the OK button. For example:
Target: "C:\Program Files\PuTTY0.52\putty.exe" @Hoffman2
