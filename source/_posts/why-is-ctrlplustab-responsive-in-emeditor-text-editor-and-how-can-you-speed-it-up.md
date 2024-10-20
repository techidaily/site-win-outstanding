---
title: Why Is Ctrl+Tab Responsive in EmEditor Text Editor, and How Can You Speed It Up?
date: 2024-10-13T06:04:34.003Z
updated: 2024-10-13T22:15:53.380Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/f1a263c48a30403473697d2181558146e92bb208f913d3a258e1502b44a08c19.jpg
---

## Why Is Ctrl+Tab Responsive in EmEditor Text Editor, and How Can You Speed It Up?

Viewing 10 posts - 1 through 10 (of 10 total)

* Author  
Posts
* February 22, 2009 at 5:28 pm [#6955](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/947e2ea01babc4f0c3bc8133631a68c7?s=80&d=identicon&r=g)urlwolf](https://www.emeditor.com/forums/users/urlwolf/ "View urlwolf's profile")  
Member  
I’m finding that, even for tiny text files that do not have syntax highlighting, ctrl+tab is very slow, about 1sec on a 2GHz machine. Why? Is there anything I can do to improve this? It kills my flow since I ctrl+tab all the time.  
 Thanks  
February 22, 2009 at 5:39 pm [#6957](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> urlwolf wrote:  
> I’m finding that, even for tiny text files that do not have syntax highlighting, ctrl+tab is very slow, about 1sec on a 2GHz machine. Why? Is there anything I can do to improve this? It kills my flow since I ctrl+tab all the time.  
>  
> Thanks  
 Are you using the Registry or INI files (portable option)? If you are using INI files, try the Registry please.  
February 22, 2009 at 5:58 pm [#6959](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/947e2ea01babc4f0c3bc8133631a68c7?s=80&d=identicon&r=g)urlwolf](https://www.emeditor.com/forums/users/urlwolf/ "View urlwolf's profile")  
Member  
I disabled all plugins but project, and now switching is fast.  
 Nevermind. I only need project right now anyway.  
February 22, 2009 at 6:00 pm [#6960](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> urlwolf wrote:  
> I disabled all plugins but project, and now switching is fast.  
> Nevermind. I only need project right now anyway.  
 Thanks for letting us know. It might be nice if you could find which plug-in was causing the problem.  
February 22, 2009 at 6:37 pm [#6962](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/947e2ea01babc4f0c3bc8133631a68c7?s=80&d=identicon&r=g)urlwolf](https://www.emeditor.com/forums/users/urlwolf/ "View urlwolf's profile")  
Member  
Yes, I’m using the INI file.  
 The slowness is back (still using INI file); I added autocomplete plugin.  
 It only happens when switching from one language to another (I’m using a custom syntax file for ahk, based on the one distributed in the main application).  
 I actually want to have a portable version of EmEditor. Can one go back and forth between INI and registry? How?  
 Thanks  
February 22, 2009 at 9:48 pm [#6964](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/947e2ea01babc4f0c3bc8133631a68c7?s=80&d=identicon&r=g)urlwolf](https://www.emeditor.com/forums/users/urlwolf/ "View urlwolf's profile")  
Member  
it is wordcomplete. It makes tab switching extraordinary slow (about one second).  
 It might be only if the syntax file has a few thousand entries.  
 I cannot try the registry method.  
 I installed the standard 8.02 on top of the portable one, but it is still very slow when changing configurations etc, so I suspect it is reading INI files.  
 Import/export does not offer an option to export to registry, only the other way around (registry to INI).  
 Is this possible?  
February 23, 2009 at 2:25 am [#6965](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> urlwolf wrote:  
> it is wordcomplete. It makes tab switching extraordinary slow (about one second).  
> It might be only if the syntax file has a few thousand entries.  
>  
> I cannot try the registry method.  
> I installed the standard 8.02 on top of the portable one, but it is still very slow when changing configurations etc, so I suspect it is reading INI files.  
>  
> Import/export does not offer an option to export to registry, only the other way around (registry to INI).  
>  
> Is this possible?  
 It is possible. Import/Export offers an option to export INI files to the Registry. Please make sure you use the latest version of EmEditor — currently v8.02.  
February 23, 2009 at 9:52 am [#6972](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/947e2ea01babc4f0c3bc8133631a68c7?s=80&d=identicon&r=g)urlwolf](https://www.emeditor.com/forums/users/urlwolf/ "View urlwolf's profile")  
Member  
Not on my copy. It might be that if you install portable, then you don’t get that option? Also, I installed standard on the same directory as portable, and I still don’t get that option (I think it still uses the INI files, so there might be nothing in the registry for it to import).  
 My question is: how do I force it to move INI information to the registry now?  
 If I start from a clean install, I still have no access to the INI files, and I’ve lost all my cofiguration. Maybe I can dump them to text somehow?  
February 23, 2009 at 12:08 pm [#6974](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/947e2ea01babc4f0c3bc8133631a68c7?s=80&d=identicon&r=g)urlwolf](https://www.emeditor.com/forums/users/urlwolf/ "View urlwolf's profile")  
Member  
I’m still trying to find a solution.  
 I installed the non-portable version from scratch, and it does offer you to import from ini files. However, it’s a tiny one, that doesn’t carry much info: eeCommon.INI.  
 Importing that one only doesn’t help. There’s a big one 1.5mb, that is called eeConfig. That seems like carrying a lot of info, but I couldn’t import it.  
 So the standard emEditor had only the default settings. Not good.  
 Then I moved all the inis on top of it. At that point everything works with my settings, but it’s not reading from the registry so it’s dog slow.  
 This is a conundrum… I hope you can find a solution that makes emEditor fast AND portable at the same time.  
 On the other hand, the wordcompletion plugin is still making tab switching slow even when reading from the registry. I noticed that it’s more evident when tab switching from a syntax-highlighted file to a text file (plain).  
 Thanks!  
February 23, 2009 at 11:10 pm [#6978](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> urlwolf wrote:  
> Not on my copy. It might be that if you install portable, then you don’t get that option? Also, I installed standard on the same directory as portable, and I still don’t get that option (I think it still uses the INI files, so there might be nothing in the registry for it to import).  
>  
> My question is: how do I force it to move INI information to the registry now?  
>  
> If I start from a clean install, I still have no access to the INI files, and I’ve lost all my cofiguration. Maybe I can dump them to text somehow?  
 You are right. I am sorry for confusion.  
 You will first need to install EmEditor with the Registry. Then you can import the INI files into the Registry.
* Author  
Posts

Viewing 10 posts - 1 through 10 (of 10 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-proven-strategies-for-saving-your-digital-discussions-google-meets/"><u>[Updated] 2024 Approved Proven Strategies for Saving Your Digital Discussions (Google Meets)</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/1-new-update-issues-missing-transparency-feature-in-some-emeditor-toolbars/"><u>1. New Update Issues: Missing Transparency Feature in Some EmEditor Toolbars</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-inspiring-movies-to-ignite-your-inner-strength/"><u>2024 Approved Inspiring Movies to Ignite Your Inner Strength</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/beta-version-14-unveiled-new-features-in-emeditor-pro-text-editor/"><u>Beta Version 14 Unveiled: New Features in EmEditor Pro Text Editor!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-three-ai-bots-creativity-on-a-shared-writing-task-who-won/"><u>Comparing Three AI Bots' Creativity on a Shared Writing Task - Who Won?</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/emeditor-text-editor-issue-unmarked-matching-brackets-within-quotations/"><u>EmEditor Text Editor Issue: Unmarked Matching Brackets Within Quotations</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/enhance-your-editing-experience-update-internet-explorer-and-firefox-with-the-powerful-features-of-emeditor/"><u>Enhance Your Editing Experience: Update Internet Explorer & Firefox with the Powerful Features of EmEditor</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-finest-ai-dialogue-triggers-top-20-picks-from-github/"><u>Exploring the Finest AI Dialogue Triggers: Top 20 Picks From GitHub</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-share-on-apple-iphone-se-drfone-by-drfone-ios/"><u>In 2024, How to Screen Share on Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-no-fuss-full-fun-exploring-ifunnys-meme-treasure/"><u>In 2024, No Fuss, Full Fun Exploring iFunny's Meme Treasure</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-evga-graphics-card-driver-installation-instructions-for-windows-operating-system/"><u>Latest EVGA Graphics Card Driver Installation Instructions for Windows Operating System</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/new-features-unveiled-emeditor-v2430-update-brings-ai-integration-and-enhanced-regex-tools-the-ultimate-text-editor/"><u>New Features Unveiled: EmEditor v24.3.0 Update Brings AI Integration & Enhanced Regex Tools - The Ultimate Text Editor</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/preventing-unintentional-changes-managing-csvnormal-modes-in-emeditors-undo-feature/"><u>Preventing Unintentional Changes: Managing CSV/Normal Modes in EmEditors' Undo Feature</u></a></li>
<li><a href="https://extra-resources.techidaily.com/stand-out-in-the-crowd-ingenious-tips-for-top-tinder-bios/"><u>Stand Out in the Crowd - Ingenious Tips for Top Tinder Bios</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/unveiling-the-macro-snippet-bug-a-closer-look-at-text-editing-flaws-in-emeditor/"><u>Unveiling the Macro Snippet Bug - A Closer Look at Text Editing Flaws in EmEditor</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-realme-gt-5-pro-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Realme GT 5 Pro Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1828647/21290" target="_top" id="1828647">
  <img src="//a.impactradius-go.com/display-ad/21290-1828647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1828647/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

