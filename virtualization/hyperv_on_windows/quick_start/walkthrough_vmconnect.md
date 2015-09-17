#Step 5: Connect to the virtual machine and finish the installation

In order to finish building your virtual machine, you need to start the VM and walk through the operating system installation.

##Connect to the VM

1.  In **Hyper-V Manager**, double-click on the virtual machine.
    This will launch the VMConnect tool.
2.  In VMConnect, click on the green **Start** button !(media/start.png).
    This is like hitting the power button on a physical computer.
3.  The VM will boot into setup and you can walk through the installation like you would on a physical computer.

> **Note:** Unless you're running a volume licensed version of Windows 10, you do need a seperate license for Windows running inside a virtual machine.
> The virtual machine's operating system is completely independent of the host operating system.
> 

##Other stuff you can do in VMConnect

Here are all of the buttons and shortcut keys, mapped to what they do.

| **To do this…**| Click this...| **Or, do this…**| |
| ----- | ----- | ----- | ----- |
| Start the virtual machine| !(media/start.png)| CTRL+S| |
| Turn off the VM| !(media/turnoff.png)| | |
| Shut down a VM| !(media/shutdown.png)| | |
| Save| !(media/save.png)| | |
| Pause| !(media/pause.png)| | |
| Reset| !(media/reset.png)| | |
| Mouse release| !(media/ctrlaltdel.png)| CTRL+ALT+LEFT arrow| |
| Send CTRL+ALT+DELETE to the virtual machine| | CTRL+ALT+END| |
| Switch from full-screen mode back to windowed mode| | CTRL+ALT+BREAK| |
| Use enhanced session mode| !(media/basic.png)| | |
| Open the settings for the virtual machine| | CTRL+O| |
| Create a checkpoint| !(media/checkpoint.png)| CTRL+N or select **Action** > **Checkpoint**| |
| Revert to a checkpoint| !(media/revert.png)| CTRL+E| |
| Do a screen capture| | CTRL+C| |
| Return mouse clicks or keyboard input to the physical computer| | Press CTRL+ALT+LEFT arrow and then move the mouse pointer outside of the virtual machine window.This is the **mouse release key combination** and it can be changed in the **Hyper-V settings** in **Hyper-V Manager**.| |
| Send mouse clicks or keyboard input to the virtual machine| | Click anywhere in the virtual machine window.The mouse pointer may appear as a small dot when you connect to a running virtual machine.| |
| Change the settings of the virtual machine| | Select **File** > **Settings**.| |
| Connect to a DVD image (.iso file) or a virtual floppy disk (.vfd file)| | Click **Media** on the menu.Virtual floppy disks are not supported for generation 2 virtual machines.| |

##Next Step:

[Step 6: Experiment with checkpoints](walkthrough_checkpoints.md)


 with checkpoints](walkthrough_checkpoints.md)
