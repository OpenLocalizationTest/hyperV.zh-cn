#Step 4: Create a Windows virtual machine from an .iso file

For this step, if you already have a .iso file for a supported 64-bit operating system, you can use that.
If not, you can download the .iso for [Windows 8.1 Enterprise](http://www.microsoft.com/en-us/evalcenter/evaluate-windows-8-1-enterprise) and choose the 64-bit edition.

1.  In Hyper-V Manager, click on the **Action** menu > **New** > **Virtual machine**.
2.  In the virtual machine wizard, make the following choices:
    
    <table>
      <tr>
        <th caps_internal_Id="0762a451-0cf5-4c37-97b8-3b1a636684ee">Page</th>
        <th caps_internal_Id="72f8e8cd-3734-4969-a07c-4fe8c6e77174">Entry</th>
      </tr>
      <tr>
        <td caps_internal_Id="1afea42a-08d9-4398-bcba-5642a8fce48a">Name:</td>
        <td>Type in <b caps_internal_Id="dbff3b5b-af08-43b4-8567-0eb913bcb75f">Windows Walkthrough VM</b></td>
      </tr>
      <tr>
        <td caps_internal_Id="00c9ed8d-8af0-44b9-af38-44d1cf55c80c">Generation:</td>
        <td>
          <b caps_internal_Id="68bc5e6e-2b89-4996-8cd0-e9bf6638c61f">Generation 2</b>
        </td>
      </tr>
      <tr>
        <td caps_internal_Id="28d37ddb-fbe1-40ba-bdb1-7b904b42dc59">Startup Memory:</td>
        <td>
          <b caps_internal_Id="c69af676-f63a-4d6d-b548-af8a6d9cc9d8">1024</b> and leave dynamic memory selected</td>
      </tr>
      <tr>
        <td caps_internal_Id="b6ade329-1e8b-40cf-8655-e5dc5afdeffe">Configure Networking:</td>
        <td>
          <b caps_internal_Id="c7d785fd-227f-4eea-8af3-6a3316c554d8">External</b> (this is the virtual switch you created in Step 3)</td>
      </tr>
      <tr>
        <td caps_internal_Id="331aaf2c-019d-4530-a6b1-32f55ebc7eba">Connect virtual hard disk:</td>
        <td>
          <b caps_internal_Id="16824248-225d-476d-a4f1-967092d7a3d4">Create a virtual hard disk</b> (keep the other default values) </td>
      </tr>
      <tr>
        <td caps_internal_Id="71310382-de2a-4526-86c8-12dbeaeb8183">Installation Options:</td>
        <td>
          <b caps_internal_Id="bc2b34e4-b29a-4021-a446-5964fbc43a41">Install an operating system from a bootable CD/DVD-ROM</b>. Under <b caps_internal_Id="094432e0-d65f-4336-85e3-5511b81cddba">Media</b>, select <b caps_internal_Id="47eeef94-2f0a-49d3-b495-97141325f4d5">Image file (iso)</b> and then click <b caps_internal_Id="2a35b2fc-123e-4ce5-9e02-64300dc9bc8d">Browse</b> to point to the .iso file.</td>
      </tr>
    </table>
3.  When everything looks right, click **Finish**.

> **Note:** If you only have 32-bit version of Windows, you need to choose Generation 1 in the **Generation** section of the wizard.
> Generation 2 VMs only support 64-bit operating systems.
> 

##Next Step:

[Step 5: Connect to the virtual machine and finish the installation](walkthrough_vmconnect.md)


