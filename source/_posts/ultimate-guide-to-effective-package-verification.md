---
title: Ultimate Guide to Effective Package Verification
date: 2024-10-24T23:59:21.695Z
updated: 2024-10-28T22:48:34.245Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Ultimate Guide to Effective Package Verification
thumbnail: https://thmb.techidaily.com/a270605ef2ab426a6767629ae263537bc25fdbd249dd83c4ff219886bfce5bc1.jpg
---

## Ultimate Guide to Effective Package Verification

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Start Page](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Save As Template Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Project Options Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
         * [External Tools](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Validation](https://tools.techidaily.com/advancedinstaller/products/)  
         * [SCCM Configurations](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Auto Import](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Edit Solution Options](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Package Validation

The validation tool checks your project for compliance with each of the internal consistency evaluators (ICEs). The files containing these ICEs are those installed with the MsiVal2.msi tool (part of the Microsoft Windows Installer Platform SDK) to validate the installation and merge module packages for Windows logo compliance. Advanced Installer will not install those files by default, it will automatically detect them if they are installed. However if the MsiVal2.msi tool is not installed but present on your computer Advanced Installer will automatically prompt you to install it. If this tool is not present on your computer you need to manually browse for the ICE files. The predefined Microsoft ICE evaluation files detected by Advanced Installer are:

* **Full MSI Validation Suite** \- Runs darice.cub, it performs up to 99 checks to ensure that the installation databases are internally consistent.
* **Merge Module Validation Suite** \- Runs mergemod.cub, used to test the internal consistency of merge modules.
* **Windows XP Logo Program Suite** \- Runs XPlogo.cub, which is part of Microsoft Windows XP logo verification program. The tests in XPlogo.cub are a subset of the tests in darice.cub.
* **Windows Vista Logo Program Suite** \- Runs Vstalogo.cub, which is part of Microsoft Windows Vista logo verification program. The tests in Vstalogo.cub are a subset of the tests in darice.cub.

![Tools Dialog](https://cdn.advancedinstaller.com/img/dialog/package-validation.png "Tools Dialog")  

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)To benefit from the newly internal consistency evaluators it is recommended to have installed the newest MsiVal2.msi tool.

## Build Settings

### Enable ICE validation for Msi packages

Run selected ICE evaluation file at the MSI package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable ICE validation for Merge Module packages

Run selected ICE evaluation file at the Merge Module package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

### Enable Advanced Installer best practice rules

Run the [Advanced Installer Best Practice](https://tools.techidaily.com/advancedinstaller/products/) evaluators at build time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable App-V 5 resource compatibility check

By enabling this option you will get an "Issue List" with resources that don't meet the App-V 5 standards. The compatibility check will be performed at build time and it will include [Drivers](https://tools.techidaily.com/advancedinstaller/products/), [Scheduled tasks](https://tools.techidaily.com/advancedinstaller/products/) and [Firewall settings](https://tools.techidaily.com/advancedinstaller/products/).

### Enable UWP resource compatibility check

Verifies that the package resources and settings are attuned to Universal Windows Platform best practices. The check is performed at build time and all detected compatibility issues are shown in the "Issue List" pane.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable UWP manifest validation

Run the UWP manifest validation at build time.

### Enable validation using WACK

Uses appcert.exe from the [Windows App Certification Kit](https://learn.microsoft.com/en-us/windows/uwp/debug-test-perf/windows-app-certification-kit) to validate an MSI or UWP AppX build. If you build your project via command line, you have to be aware that by enabling WACK, the uninstall process will not be silent. The validation will provide an output log as well as a more user-friendly HTML log. 

To run these validation tests requires you to install Windows SDK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Define Rules

### Suppress Warning messages.

No validation warnings will be displayed to the user.

### Suppress specific ICEs.

The ICEs you specify separated by ";" character will not run.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The validation result is displayed as information in the build log and will not affect the build result. After the build operation is finished the validation result is displayed in the **Issue Pane** list allowing user to locate the problem in Advanced Installer UI (if possible).

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-liberate-your-files-top-picks-for-20-free-cloud-storage-options-up-to-1tb/"><u>[New] Liberate Your Files Top Picks for 20 FREE Cloud Storage Options (Up To 1TB)</u></a></li>
<li><a href="https://fox-where.techidaily.com/1-2024windows-1011/"><u>1. 2024年最新解決方法：Windows 10和11上簡單逆向修復資料</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-anonymous-sharing-simplified-blurring-techniques-for-videos/"><u>2024 Approved Anonymous Sharing Simplified Blurring Techniques for Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-ultimate-guide-to-video-cuts-windows-edition-made-simple/"><u>2024 Approved The Ultimate Guide to Video Cuts Windows Edition, Made Simple</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y56-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y56 5G</u></a></li>
<li><a href="https://fox-where.techidaily.com/erleichterung-beim-datentransfer-funf-effektive-schritte-um-dateien-von-ihrem-altmodischen-pc-zu-einem-neuartigen-gerat-zu-bewegen/"><u>Erleichterung Beim Datentransfer: Fünf Effektive Schritte, Um Dateien Von Ihrem Altmodischen PC Zu Einem Neuartigen Gerät Zu Bewegen</u></a></li>
<li><a href="https://fox-where.techidaily.com/expert-guide-choosing-and-setting-up-the-ideal-motherboard-in-labs-2-5/"><u>Expert Guide: Choosing & Setting Up the Ideal Motherboard in Labs 2-5</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-media-player-app-when-it-stops-working-on-windows-11/"><u>How to Fix the Media Player App When It Stops Working on Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-samsung-galaxy-f15-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-lava-yuva-2-pro-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Lava Yuva 2 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-present-state-of-drones-and-their-future-expansion/"><u>In 2024, The Present State of Drones and Their Future Expansion</u></a></li>
<li><a href="https://fox-where.techidaily.com/schritt-fur-schritt-guide-zum-kopieren-von-linux-startfestplatten/"><u>Schritt-Für-Schritt-Guide Zum Kopieren Von Linux Startfestplatten</u></a></li>
<li><a href="https://fox-where.techidaily.com/top-organizers-einfach-und-schnell-zwei-ordnere-in-windows-10-synchronisieren/"><u>Top Organizers: Einfach Und Schnell Zwei Ordnere in Windows 10 Synchronisieren</u></a></li>
<li><a href="https://fox-where.techidaily.com/ultimate-guide-mastering-the-password-free-restoration-of-lenovo-thinkpads-with-windows-11/"><u>Ultimate Guide: Mastering the Password-Free Restoration of Lenovo ThinkPads with Windows 11</u></a></li>
</ul></div>

