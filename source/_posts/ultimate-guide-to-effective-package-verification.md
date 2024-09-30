---
title: Ultimate Guide to Effective Package Verification
date: 2024-09-24T04:34:09.789Z
updated: 2024-09-30T02:55:22.567Z
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

### Enable ICE validation for Merge Module packages

Run selected ICE evaluation file at the Merge Module package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

### Enable Advanced Installer best practice rules

Run the [Advanced Installer Best Practice](https://tools.techidaily.com/advancedinstaller/products/) evaluators at build time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable App-V 5 resource compatibility check

By enabling this option you will get an "Issue List" with resources that don't meet the App-V 5 standards. The compatibility check will be performed at build time and it will include [Drivers](https://tools.techidaily.com/advancedinstaller/products/), [Scheduled tasks](https://tools.techidaily.com/advancedinstaller/products/) and [Firewall settings](https://tools.techidaily.com/advancedinstaller/products/).

### Enable UWP resource compatibility check

Verifies that the package resources and settings are attuned to Universal Windows Platform best practices. The check is performed at build time and all detected compatibility issues are shown in the "Issue List" pane.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable UWP manifest validation

Run the UWP manifest validation at build time.

### Enable validation using WACK

Uses appcert.exe from the [Windows App Certification Kit](https://learn.microsoft.com/en-us/windows/uwp/debug-test-perf/windows-app-certification-kit) to validate an MSI or UWP AppX build. If you build your project via command line, you have to be aware that by enabling WACK, the uninstall process will not be silent. The validation will provide an output log as well as a more user-friendly HTML log. 

To run these validation tests requires you to install Windows SDK.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Define Rules

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959773/19272" target="_top" id="1959773">
  <img src="//a.impactradius-go.com/display-ad/19272-1959773" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959773/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-hints.techidaily.com/new-capture-calls-on-iphone-2024/"><u>[New] Capture Calls on iPhone 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-explore-all-content-jointly-shared-photos-and-vids/"><u>2024 Approved Explore All Content Jointly Shared Photos & Vids</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-realme-gt-neo-5-se-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Realme GT Neo 5 SE Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-invisible-mouse-icon-on-windows-11-without-breaking-a-sweat/"><u>Fix Your Invisible Mouse Icon on Windows 11 Without Breaking a Sweat!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/gooview-chromes-in-os-screen-recorder-for-2024/"><u>GooView Chrome's In-OS Screen Recorder for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-11-drfone-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-precision-techniques-to-record-your-facetime-chats/"><u>In 2024, Precision Techniques to Record Your FaceTime Chats</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-twitch-content-integration-boosting-engagement-with-fb-sharing/"><u>In 2024, Twitch Content Integration Boosting Engagement with FB Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-win11-wi-fi-accessibility-with-9-steps/"><u>Securing Win11 Wi-Fi Accessibility with 9 Steps</u></a></li>
<li><a href="https://fox-where.techidaily.com/step-by-step-tutorial-on-creating-durable-hardcovers-for-your-personal-flipbooks-at-home-flipmastery-with-flipbuildercom/"><u>Step-by-Step Tutorial on Creating Durable Hardcovers for Your Personal FlipBooks at Home [FlipMastery with FlipBuilder.com]</u></a></li>
<li><a href="https://fox-where.techidaily.com/step-by-step-tutorial-how-to-conduct-personnel-queries-within-flipbuilders-digital-books/"><u>Step-by-Step Tutorial: How to Conduct Personnel Queries Within Flipbuilder's Digital Books</u></a></li>
<li><a href="https://fox-where.techidaily.com/switching-page-layout-in-books-is-it-possible-to-change-orientation-with-flipbuilder/"><u>Switching Page Layout in Books: Is It Possible To Change Orientation With FlipBuilder?</u></a></li>
<li><a href="https://fox-where.techidaily.com/the-step-by-step-guide-to-acquiring-your-flipbuilder-license-afterplacing-an-order/"><u>The Step-by-Step Guide to Acquiring Your FlipBuilder License Afterplacing an Order</u></a></li>
<li><a href="https://fox-where.techidaily.com/transform-pdf-documents-to-stylish-ebooks-easy-conversion-and-storage-with-flipbuilder-services/"><u>Transform PDF Documents to Stylish eBooks: Easy Conversion and Storage with FlipBuilder Services</u></a></li>
<li><a href="https://fox-where.techidaily.com/transform-your-photo-collection-into-engaging-ebooks-featuring-page-turn-animation-with-flipbuilders-easy-tutorial/"><u>Transform Your Photo Collection Into Engaging eBooks Featuring Page Turn Animation with FlipBuilder's Easy Tutorial</u></a></li>
<li><a href="https://fox-where.techidaily.com/understanding-flipbuilders-share-buttons-a-comprehensive-guide/"><u>Understanding FlipBuilder's Share Buttons – A Comprehensive Guide</u></a></li>
<li><a href="https://fox-where.techidaily.com/understanding-the-process-when-will-you-receive-your-flipbuilder-license-key-post-order/"><u>Understanding the Process: When Will You Receive Your FlipBuilder License Key Post-Order?</u></a></li>
</ul></div>

