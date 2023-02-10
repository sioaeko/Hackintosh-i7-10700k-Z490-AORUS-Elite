# Opencore-EFI-AORUS-Z490-Elite-OC-0.8.8-

⚠ Notice!
> We update OC Version 0.8.8!!

You can use to upgrade MacOS Ventura 13.1

I wrote down the detailed description of this EFI in the notion
> https://alive-bayberry-ea1.notion.site/AORUS-Z490-Elite-10700K-UHD-630-OC-0-7-9-Perfect-4c4ff8c7dc3b42a8886d361a6bbde9c9

# Preview MacOS

<img src="https://user-images.githubusercontent.com/101755125/167288229-2b859719-504b-4aa3-ab8a-26d4e6aaaeee.png" width="47%"></img>
<img src="https://user-images.githubusercontent.com/101755125/177314848-eda8ae26-5d04-49b5-8ff5-b3951b0fce07.png" width="47%"></img>
<img width="980" alt="Screenshot 2023-02-08 at 2 58 53 PM" src="https://user-images.githubusercontent.com/101755125/217449151-9e4b5a61-dcdb-4bda-b66e-a44969a25ab1.png">



## Hardware spec
 
    - CPU : Intel Core(R) i7-10700K 8-Core 4.00Ghz(OC)
    - Memory : Teamforce Xtreem RGB DDR4 16GB 4000 MHz(OC)
    - Graphics : Intel UHD Graphics 630 ( Desktop ) - HDMI 1.4 ( Maximum QHD 72Hz )
        - RTX2070s disabled ( Because NVIDIA (Keppler/Pascal Architecture) Doesn’t support Web/Custom Driver after Mojave )
    - SSD : Micron MX250 sata3 256GB
        - PM981a disabled ( Samsung OEM SSD is Cause to Kernel Panic!! )
    - SMBIOS : iMac19,1 ( Retina 5K, 27-inch, 2019)

## Working Functions 

      -Internal Speaker,Headphones ( AppleALC )
      -Apple Genius Airport Card ( BCM_2070B0 ) - No need to use custom kext ( Always use Native kext)
      -Apple Communites Servies+ BT ( Handoff, icloud, instant hospot, airdrop, Universal Control, Sidecar all Supported )
      -USB 3.1 Supported ( USBMap Builded ) - Mac Sleep Mode Perfectly wake up
      -Realtek 2.5G Wire LAN Supported
      -Sleep and Wake Perfect
      - Intel SpeedStep + CPU Optimizing Power Management
#
<img src = "https://user-images.githubusercontent.com/101755125/167087027-20effeb7-f12f-4e29-aae3-ea8dad27f6ad.png" width="70%"></img>
<img width="246" alt="Screenshot 2023-02-08 at 3 08 41 PM" src="https://user-images.githubusercontent.com/101755125/217448996-96e7f635-0caf-4942-aea2-69cb04358c3d.png">
<img width="246" alt="Screenshot 2023-02-08 at 3 08 44 PM" src="https://user-images.githubusercontent.com/101755125/217449027-86a5ddab-8db1-4b12-9744-971a0b4c4a4e.png">


## Bios Setting

>  ⚠  Base for Aorus Z490 Elite / Master
    
    - IO Ports > Internal Graphics > ( Auto > Enabled )
    
    - IO Ports > Above 4G Decoding > ( Disabled > Enabled )
    
    - IO Ports > USB Configuration > XHCI Hand-off > ( Disabled > Enabled )
    
    - IO Ports > SATA And RST Configuration > SATA Mode Selection > ( Intel RST > AHCI )
    
    - IO Ports > Intel Platform Trust Technology ( PTT ) > ( Enabled > Disabled )
    
    - IO Ports > Software Guard Extensions ( SGX ) > ( Enabled > Disabled )
    
    - IO Ports > Trusted Computing > Security Device Support > ( Enabled > Disabled )
    
    - Boot > Boot Configuration > CFG Lock > ( Enabled > Disabled )
    
    - Boot > Boot Option Priorities > Fast Boot > Disabled Link
    
    - Boot > Boot Option Priorities > CSM Support > ( Enabled > Disabled )
    
    - Boot > Secure Boot > Secure Boot Enabled > ( Enabled > Disabled )
     
    - Keyboard F10 + Enter ( Save & Exit )


## USB Port Map
<img width="582" alt="Screenshot 2023-02-08 at 3 06 37 PM" src="https://user-images.githubusercontent.com/101755125/217448535-f0514add-a06a-4c03-8039-2aed6e3f817a.png">

## Intel Speed Step & Optimizing Power Management

>This EFI is perfect working speed step and Optimizing Power Management(PM)
>
>So you don't need to use another kext or ssdt ( ex:CPUFriend/CPUFriendFriend/SSDT-PLUG )

<img width="312" alt="Screenshot 2023-02-10 at 7 34 34 PM" src="https://user-images.githubusercontent.com/101755125/218071393-7b015e7e-3700-4c3f-93db-8b19eb8c7a66.png">
<img width="552" alt="Screenshot 2023-02-10 at 7 35 16 PM" src="https://user-images.githubusercontent.com/101755125/218071337-e8a71a66-22a8-4f22-8751-78a43c61a44b.png">
 <img width="552" alt="Screenshot 2023-02-10 at 7 36 17 PM" src="https://user-images.githubusercontent.com/101755125/218071381-e9f110df-e2da-4707-b772-82e3ac2ce4cf.png">


# Important!!

⚠ Notice!
> **If you want to use this efi normaly, Please input your New ROM / SystemUUID / SystemSerialNumber / MLB**

<img width="512" alt="Screenshot 2023-02-08 at 2 43 00 PM 1" src="https://user-images.githubusercontent.com/101755125/217446894-510dd79c-2274-491d-8599-8800ae61be68.png">


