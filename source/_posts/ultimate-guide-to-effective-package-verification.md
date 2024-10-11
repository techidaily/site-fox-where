---
title: Ultimate Guide to Effective Package Verification
date: 2024-10-08T19:32:52.285Z
updated: 2024-10-10T16:21:59.472Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043661/7443" target="_top" id="2043661">
  <img src="//a.impactradius-go.com/display-ad/7443-2043661" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043661/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable ICE validation for Msi packages

Run selected ICE evaluation file at the MSI package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable ICE validation for Merge Module packages

Run selected ICE evaluation file at the Merge Module package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable Advanced Installer best practice rules

Run the [Advanced Installer Best Practice](https://tools.techidaily.com/advancedinstaller/products/) evaluators at build time.

### Enable App-V 5 resource compatibility check

By enabling this option you will get an "Issue List" with resources that don't meet the App-V 5 standards. The compatibility check will be performed at build time and it will include [Drivers](https://tools.techidaily.com/advancedinstaller/products/), [Scheduled tasks](https://tools.techidaily.com/advancedinstaller/products/) and [Firewall settings](https://tools.techidaily.com/advancedinstaller/products/).

### Enable UWP resource compatibility check

Verifies that the package resources and settings are attuned to Universal Windows Platform best practices. The check is performed at build time and all detected compatibility issues are shown in the "Issue List" pane.

### Enable UWP manifest validation

Run the UWP manifest validation at build time.

### Enable validation using WACK

Uses appcert.exe from the [Windows App Certification Kit](https://learn.microsoft.com/en-us/windows/uwp/debug-test-perf/windows-app-certification-kit) to validate an MSI or UWP AppX build. If you build your project via command line, you have to be aware that by enabling WACK, the uninstall process will not be silent. The validation will provide an output log as well as a more user-friendly HTML log. 

To run these validation tests requires you to install Windows SDK.

## Define Rules

### Suppress Warning messages.

No validation warnings will be displayed to the user.

### Suppress specific ICEs.

The ICEs you specify separated by ";" character will not run.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The validation result is displayed as information in the build log and will not affect the build result. After the build operation is finished the validation result is displayed in the **Issue Pane** list allowing user to locate the problem in Advanced Installer UI (if possible).

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-glue.techidaily.com/updated-discover-the-new-era-of-photography-with-toolwiz-comprehensive-2023-reviews-for-2024/"><u>[Updated] Discover the New Era of Photography with Toolwiz Comprehensive 2023 Reviews for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-chromatic-wonders-bridging-color-knowledge/"><u>2024 Approved Chromatic Wonders Bridging Color Knowledge</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-zeo-startup-showcase/"><u>2024 Approved The Ultimate Zeo-Startup Showcase</u></a></li>
<li><a href="https://youtube-web.techidaily.com/nce-engagement-and-its-impact-on-youtube-performance-for-2024/"><u>Audience Engagement and Its Impact on YouTube Performance for 2024</u></a></li>
<li><a href="https://fox-where.techidaily.com/customize-style-rules-in-the-advanced-formatting-tools/"><u>Customize Style Rules in the Advanced Formatting Tools</u></a></li>
<li><a href="https://fox-where.techidaily.com/effective-techniques-for-capturing-audio-from-clubhouse-sessions/"><u>Effective Techniques for Capturing Audio From Clubhouse Sessions</u></a></li>
<li><a href="https://win-amazing.techidaily.com/essential-updates-for-windows-fingerprint-drivers-fast-and-reliable-download-options-here/"><u>Essential Updates for Windows Fingerprint Drivers - Fast & Reliable Download Options Here</u></a></li>
<li><a href="https://fox-where.techidaily.com/how-to-achieve-a-fully-transparent-logo-with-optimal-techniques-and-applications/"><u>How to Achieve a Fully-Transparent Logo with Optimal Techniques and Applications</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Motorola Moto G Stylus (2023)? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>How to Watch Hulu Outside US On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/kostenloze-online-mpg-conversie-naar-wav-professioneel-door-movavi/"><u>Kostenloze Online Mpg-Conversie Naar Wav - Professioneel Door Movavi</u></a></li>
<li><a href="https://fox-where.techidaily.com/navigate-through-our-expert-guide-of-2020s-best-mac-compatible-mind-mapping-applications-that-offer-seamless-organization-and-creativity-enhancement-feature4/"><u>Navigate Through Our Expert Guide of 2020'S Best Mac Compatible Mind Mapping Applications that Offer Seamless Organization and Creativity Enhancement Features.</u></a></li>
<li><a href="https://fox-where.techidaily.com/purchasing-a-malwarebytes-lifetime-subscription-legitimately-expert-guide/"><u>Purchasing a Malwarebytes Lifetime Subscription Legitimately - Expert Guide</u></a></li>
<li><a href="https://fox-where.techidaily.com/step-by-step-guide-to-restoring-accidentally-erased-images-on-your-iphone-7/"><u>Step-by-Step Guide to Restoring Accidentally Erased Images on Your iPhone 7</u></a></li>
<li><a href="https://fox-where.techidaily.com/top-10-free-android-apps-for-outstanding-video-editing-unleash-your-creativity/"><u>Top 10 Free Android Apps for Outstanding Video Editing: Unleash Your Creativity</u></a></li>
<li><a href="https://media-tips.techidaily.com/ultimate-picks-the-leading-windowsmac-gif-creation-tools-online/"><u>Ultimate Picks: The Leading Windows/Mac GIF Creation Tools Online</u></a></li>
<li><a href="https://fox-where.techidaily.com/versatile-methods-transforming-your-myspace-music-into-mp3-format/"><u>Versatile Methods: Transforming Your MySpace Music Into MP3 Format</u></a></li>
</ul></div>

