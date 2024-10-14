---
title: Unveiling the Macro Snippet Bug - A Closer Look at Text Editing Flaws in EmEditor
date: 2024-10-13T10:13:48.831Z
updated: 2024-10-13T23:10:11.565Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/cce90de001854095939cd22c7e555d9393bc0bdf8a9fe07be68597eb9b7713ab.jpg
---

## Unveiling the Macro Snippet Bug - A Closer Look at Text Editing Flaws in EmEditor

Viewing 3 posts - 1 through 3 (of 3 total)

* Author  
Posts
* December 11, 2009 at 4:32 pm [#7946](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/d3ca70adb85b5cf4d6a52ff39472d478?s=80&d=identicon&r=g)orzy09](https://www.emeditor.com/forums/users/orzy09/ "View orzy09's profile")  
Member  
I want to create the following snippet that insert clipboard data (a filepath copied in the clipboard). I used the syntax provided in the help file. The line with the macro is this:  
\`# Interface.write(clipboardData.getData(“”));\`  
 I copied a path (c:test) in the clipboard and executed the snipped. It worked fine. Then I copied another path (d:test) and now the text was appended so I got:  
c:testd:test  
 executing the snippet again without another copy before added the clipboard data again:  
c:testd:testd:test  
 after some testing I found out that the following line sents combined all what I had inserted with the above macro before.  
\`#\`  
 So this line would also get the result:  
c:testd:testd:test  
 I this a bug or do I something wrong?  
 Thanks and all the best  
December 11, 2009 at 7:20 pm [#7949](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> orzy09 wrote:  
> I want to create the following snippet that insert clipboard data (a filepath copied in the clipboard). I used the syntax provided in the help file. The line with the macro is this:  
>  
> \`# Interface.write(clipboardData.getData(“”));\`  
>  
> I copied a path (c:test) in the clipboard and executed the snipped. It worked fine. Then I copied another path (d:test) and now the text was appended so I got:  
>  
> c:testd:test  
>  
> executing the snippet again without another copy before added the clipboard data again:  
>  
> c:testd:testd:test  
>  
> after some testing I found out that the following line sents combined all what I had inserted with the above macro before.  
>  
> \`#\`  
>  
> So this line would also get the result:  
>  
> c:testd:testd:test  
>  
> I this a bug or do I something wrong?  
>  
> Thanks and all the best  
 This is a bug. I will fix this in the next version. Thanks!  
December 20, 2009 at 6:35 pm [#7977](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/d3ca70adb85b5cf4d6a52ff39472d478?s=80&d=identicon&r=g)orzy09](https://www.emeditor.com/forums/users/orzy09/ "View orzy09's profile")  
Member  
Hello Mr. Emura,  
 it works now. Thank you for the quick fix and for a marvellous editor! :-D  
 All the best.  
 orzy09
* Author  
Posts

Viewing 3 posts - 1 through 3 (of 3 total)

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
<li><a href="https://video-screen-grab.techidaily.com/new-preserving-your-virtual-sessions-gotomeeting-tips/"><u>[New] Preserving Your Virtual Sessions GoToMeeting Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-apples-podcast-potential-an-instructional-guide/"><u>[New] Unlocking Apple's Podcast Potential An Instructional Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-zombie-mayhem-showdown-selecting-the-finest-games-for-2024/"><u>[New] Zombie Mayhem Showdown Selecting the Finest Games for 2024</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/advanced-text-search-in-emeditor-easily-locate-words-and-phrases/"><u>Advanced Text Search in EmEditor - Easily Locate Words and Phrases</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/beta-version-14-unveiled-new-features-in-emeditor-pro-text-editor/"><u>Beta Version 14 Unveiled: New Features in EmEditor Pro Text Editor!</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-guide-to-diagnose-and-solve-dev-error-5573-in-fortnites-warzone-for-both-desktop-and-gaming-systems/"><u>Comprehensive Guide to Diagnose and Solve Dev Error 5573 in Fortnite's Warzone - For Both Desktop & Gaming Systems</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/efficient-text-editing-with-emeditor-the-ultimate-code-and-notepad-tool/"><u>Efficient Text Editing with EmEditor - The Ultimate Code and Notepad Tool</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/how-to-fix-projectsdll-crash-in-emeditor-an-in-depth-guide/"><u>How to Fix Projects.dll Crash in EmEditor: An In-Depth Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-setting-up-video-live-wallpapers-on-your-android-device/"><u>Step-by-Step Guide: Setting Up Video Live Wallpapers on Your Android Device</u></a></li>
<li><a href="https://driver-download.techidaily.com/the-anterior-tibial-artery-supplies-the-anterior-compartment-of-the-leg-whereas-the-posterior-tibial-artery-serves-the-posterior-and-plantar-aspects/"><u>The Anterior Tibial Artery Supplies the Anterior Compartment of the Leg, Whereas the Posterior Tibial Artery Serves the Posterior and Plantar Aspects</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-http-status-code-401-step-by-step-tips/"><u>Troubleshooting HTTP Status Code 401 – Step-by-Step Tips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unparalleled-dramatic-audio-experiences-for-2024/"><u>Unparalleled Dramatic Audio Experiences for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

