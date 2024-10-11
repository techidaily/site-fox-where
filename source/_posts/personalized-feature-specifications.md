---
title: Personalized Feature Specifications
date: 2024-10-05T19:33:50.055Z
updated: 2024-10-10T17:26:59.429Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Personalized Feature Specifications
thumbnail: https://thmb.techidaily.com/4a7e35e05dbbab3383219ac491b7159c730c023be090a3ce22bfc91cc23bb5f7.jpg
---

## Personalized Feature Specifications

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Search](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Properties Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Custom Actions](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Custom Action Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Condition Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Custom Actions List](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Table Editor](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Custom Action Properties

See [Custom Actions List](https://tools.techidaily.com/advancedinstaller/products/) for a detailed description of each predefined custom action in Advanced Installer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Time

* _Immediately_ \- the action will be executed immediately when it is found in the action sequence.
* _When the system is being modified (deferred)_ \- the action will be executed in order as part of the script built out of all the non-immediate actions. Custom Actions before InstallInitialize (Preparing action group) and after InstallFinalize (Finish Execution action group) can not be deferred and they must be Immediate. Note that deferred custom actions do not have access to installer's public properties.
* _During installation rollback_ \- execute the action only if something failed after this action and the installation is being rolled back.
* _After the system has been successfully modified (commit)_ \- the action will be executed in the Commit phase, after everything got installed successfully.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)On Windows Vista or above the custom actions which affect the system or require Administrator privileges should run without impersonation. For this you can simply check the **Run under the LocalSystem account with full privileges (no impersonation)** option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Options

* _Run under the LocalSystem account with full privileges (no impersonation)_ \- the custom action will be executed under the LocalSystem account with full privileges. This option is not available for custom actions which are executed Immediately.
* _Wait for custom action to finish before proceeding_ \- determines if the main installation thread waits for the custom action to complete. Windows Installer always waits for custom actions executed during rollback.
* _Fail installation if custom action returns an error_ \- determines if the custom action return code is checked by Windows Installer. For more information about custom action return codes, please see the [Custom Actions Page](https://tools.techidaily.com/advancedinstaller/products/).
* _Wait for return code at the end of the sequence_ \- determines if the current stage (Wizard Dialogs Stage or Install Execution Stage) will wait for the custom action return code after all actions have been executed. The actual return code is ignored by the installation.
* _Action Text..._ \- specify a text that will be displayed in the progress dialog box or written in the log file, when the custom action is being run. Use the button. The [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed and will allow you to specify the text. Note that only deferred custom actions can set an Action Text.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Custom actions that are _executable_ files must return a value of 0 for success. The installer interprets any other return value as failure.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Condition

* _Install_ \- Enable this option if you want your custom action to execute during installation of the package.  
   * _First Time Install_ \- The custom action will execute during installation of the package if no older version was found on the target computer.  
   * _Upgrade_ \- The custom action will execute during installation of the package only if an older version was found on the target computer.
* _Uninstall_ \- Enable this option if you want your custom action to execute during removal of the package.  
   * _Regular uninstall_ \- The custom action will execute during a complete uninstall of the application, not during an upgrade. This option is available only during "Install Execution Stage".  
   * _Replaced by a new version_ \- The custom action will execute during removal of the application trigerred by the installation of a new version. This option is available only during "Install Execution Stage".
* _Maintenance_ \- Enable this option if you want your custom action to execute during a repair or customization of the package.
* _Condition_ \- a boolean expression which must be true for the Custom Action to be executed. Edit this field using [Smart Condition Edit Control](https://tools.techidaily.com/advancedinstaller/products/).

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The _First Time Install_, _Upgrade_,_Regular uninstall_ and _Replaced by a new version_ options may not displayed by default, you should use the _Show upgrade options_ link to display them.

* _Advanced execution scenarios_ \- this link displays the [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/).

### UI Triggering Events

A list with all the [events](https://tools.techidaily.com/advancedinstaller/products/) that trigger the custom action at install time. Each entry shows the name of the dialog on the first column, and on the second column, the name of the control from the dialog that triggers the event when the user interacts with it.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)This list is shown only for custom actions without sequence. If the list is empty then the custom action will never execute.

Select an event and click **Go to selected event dialog** link button to configure it in the [Dialog Editor Page](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Edit Action Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Specify a text which is displayed when a custom action runs.
* [Edit Condition Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
This dialog allows you to specify a conditional statement.
* [Advanced Execution Scenarios Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Use corner case execution options for your custom action.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-accelerate-artistic-edits-with-windows-11/"><u>[New] 2024 Approved Accelerate Artistic Edits with Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-mastering-the-skies-complete-review-of-dji-phantom-4/"><u>[Updated] 2024 Approved Mastering the Skies Complete Review of DJI Phantom 4</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-4k-clarity-comes-closer-with-asuss-innovative-mg28uq-display/"><u>[Updated] In 2024, 4K Clarity Comes Closer with ASUS's Innovative MG28UQ Display</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://fox-where.techidaily.com/advanced-image-targeting-techniques-with-ipatch/"><u>Advanced Image Targeting Techniques with IPatch</u></a></li>
<li><a href="https://fox-where.techidaily.com/detailed-overview-of-assembly-pages-structure-and-best-practices/"><u>Detailed Overview of Assembly Pages: Structure and Best Practices</u></a></li>
<li><a href="https://fox-where.techidaily.com/expanding-your-online-presence-strategies-for-growing-website-features-and-extensions/"><u>Expanding Your Online Presence: Strategies for Growing Website Features and Extensions</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-social-sync-how-to-add-friends-on-discord/"><u>In 2024, Social Sync How to Add Friends on Discord</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-the-art-of-mobile-based-interview-and-travel-podcasts/"><u>Mastering the Art of Mobile-Based Interview & Travel Podcasts</u></a></li>
<li><a href="https://fox-where.techidaily.com/quickinstall-tool-instant-software-update-wizard/"><u>QuickInstall Tool - Instant Software Update Wizard</u></a></li>
<li><a href="https://fox-where.techidaily.com/simplify-your-digital-space-the-iremovefiles-solution-for-quick-file-removal/"><u>Simplify Your Digital Space: The IRemoveFiles Solution for Quick File Removal</u></a></li>
<li><a href="https://fox-where.techidaily.com/ultimate-guide-to-effective-package-verification/"><u>Ultimate Guide to Effective Package Verification</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-avi-video-cutter-reviews-top-16-options-for-precise-trimming/"><u>Updated AVI Video Cutter Reviews Top 16 Options for Precise Trimming</u></a></li>
</ul></div>

