## This patching guide for the Intel UHD 620 GPU not only gives you better Graphics Acceleration but it improves the docking audio and video compatibility as well.

Required Tools: [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/?doing_wp_cron=1741176165.9179310798645019531250).

1. Open [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/?doing_wp_cron=1741176165.9179310798645019531250), mount your EFI partition and open your Config.Plist file.
2. Go to ```DeviceProperties``` and in the section that says ```Devices``` select the middle option as that is where all of the juicy iGPU information is stored.
3. Look for the key known as ```AAPL,ig-platform-id```, select the code that is right next to it and change that from the default value to ```0000C087```.
4. Save the ```Config.Plist``` file in [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/?doing_wp_cron=1741176165.9179310798645019531250) and restart your ThinkPad.
5. Congratulations, you've successfully patched the iGPU in your ThinkPad! Now you have improved performance and improved video and audio output support! 🥳
</details>
