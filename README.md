# Opencore-EFI-AORUS-Z490-Elite-OC-0.8.8-


<img src="https://user-images.githubusercontent.com/101755125/218128864-415aa3e0-ebf5-47cb-8be0-7e41ba3820b3.jpeg" width="17%"></img>

⚠ Notice!
>https://github.com/59rice/Hackintosh-Intel-i7-10700k-AORUS-Z490-Elite-OpenCore-0.9.5

>We Made New EFI for compatibility MacOS Sonoma/Haeadless System
it works better than 0.8.8 bootloader efi

I wrote down the detail description of this EFI in the notion
> https://alive-bayberry-ea1.notion.site/AORUS-Z490-Elite-10700K-UHD-630-OC-0-7-9-Perfect-4c4ff8c7dc3b42a8886d361a6bbde9c9

# Preview MacOS

<img src="https://user-images.githubusercontent.com/101755125/167288229-2b859719-504b-4aa3-ab8a-26d4e6aaaeee.png" width="47%"></img>
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
<img width="1438" alt="Screenshot 2023-02-10 at 9 52 50 PM 2" src="https://user-images.githubusercontent.com/101755125/218097359-fe9371ef-6a8a-49b6-83d7-f812e9356e77.png">

        
      -Internal Speaker,Headphones ( AppleALC )
      ㄴ You can use backpanel,frontpanel headphone/microphone jack
      
      -Apple Genius Airport Card ( BCM_2070B0 ) - No need to use custom kext ( Always use Native kext)
      -Apple Genius Airport Card ( BCM_2070B0 ) - No need to use custom kext ( Always use Native kext)
      -Apple Communites Servies+ BT ( Handoff, icloud, instant hospot, airdrop, Universal Control, Sidecar all Supported )
      ㄴ Recommand to use Fenvi T1919 ( This Pcie wireless card based by genuine vendor BCM94360CD )
     
      -USB 3.1 Supported ( USBMap Builded ) - Mac Sleep Mode Perfectly wake up
      -Sleep and Wake Perfect
      ㄴ We already mapping usb map perfect, so sleep and wake is working
      
      -Realtek 2.5G Wire LAN Supported
      ㄴ Use LUCYRTL8125Ethernet.kext!
      
      -Intel SpeedStep + CPU Optimizing Power Management
      ㄴ Use to patch SSDT-PLUG
#
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
>So you don't need to use another kext or ssdt ( ex:CPUFriend/CPUFriendFriend)(SSDT-PLUG is already applied)

<img width="312" alt="Screenshot 2023-02-10 at 7 34 34 PM" src="https://user-images.githubusercontent.com/101755125/218071393-7b015e7e-3700-4c3f-93db-8b19eb8c7a66.png">
<img width="552" alt="Screenshot 2023-02-10 at 7 35 16 PM" src="https://user-images.githubusercontent.com/101755125/218071337-e8a71a66-22a8-4f22-8751-78a43c61a44b.png">
 <img width="552" alt="Screenshot 2023-02-10 at 7 36 17 PM" src="https://user-images.githubusercontent.com/101755125/218071381-e9f110df-e2da-4707-b772-82e3ac2ce4cf.png">


# Important!!

⚠ Notice!
> **If you want to use this efi normaly, Please input your New ROM / SystemUUID / SystemSerialNumber / MLB**

<img width="512" alt="Screenshot 2023-02-08 at 2 43 00 PM 1" src="https://user-images.githubusercontent.com/101755125/217446894-510dd79c-2274-491d-8599-8800ae61be68.png">


