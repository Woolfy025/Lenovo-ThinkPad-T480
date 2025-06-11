## Generating the System Information (aka SMBIOS) allows for all iServices (Find My, Handoff, iMessage, Facetime, etc.) to work flawlessly.


1. Run the following script in Terminal:

```git clone https://github.com/corpnewt/GenSMBIOS && cd GenSMBIOS && chmod +x GenSMBIOS.command && ./GenSMBIOS.command```

2. Mount your EFI partition using [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/?doing_wp_cron=1741176165.9179310798645019531250).
3. Go to your EFI partition, enter the EFI folder, then the OC folder and then look for the file known as ```Config.plist```.
4. Go back to ```GenSMBIOS``` , type 2 and hit ENTER to then drag your ```Config.Plist``` file into the command line, press ENTER when finished.
5. Type 3 to Generate SMBIOS, then press ENTER. Type ```MacbookPro15,2``` then press ENTER. Leave this Terminal window open.
6. Type 4 to Generate UUID and press ENTER.
7. Type 5 to Generate ROM and press ENTER.
8. Type Q to Quit and press ENTER.
9. Restart your ThinkPad and enjoy!
