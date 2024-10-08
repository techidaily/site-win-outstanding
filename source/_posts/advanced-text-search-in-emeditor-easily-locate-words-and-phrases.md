---
title: Advanced Text Search in EmEditor - Easily Locate Words and Phrases
date: 2024-10-05T17:12:11.384Z
updated: 2024-10-08T17:43:54.594Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/c10f5fc3a26c6243fb8c4940c266b426236bd87cd21bd2e8e71da4c4f75545bc.jpg
---

## Advanced Text Search in EmEditor - Easily Locate Words and Phrases

October 12, 2008 at 4:54 am [#6387](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")

Keymaster

> iisisrael wrote:  
> I altered it a little to (almost) match what we want to accomplish:
> 
> s = document.selection.Text;  
> if (!s) { document.selection.FindRepeat(eeFindRepeatNext); }  
> else {  
> document.selection.Find(s, eeFindNext | eeFindReplaceRegExp);  
> }
> 
> However, the “document.selection.Find” doesn’t replace the string used by “document.selection.FindRepeat”! This means, when I select text and run this macro, then click to erase the selected found text, and run the macro again, it doesn’t repeat the find on the recently selected text find, but finds the text from the last “Find”. How do I replace the last “Find” value?
> 
> Also, if the currently selected text is selected as a result of the find, I don’t want that to become the new find string, I want to continue with the original find string. how do I check to make a distinction between a manually selected string and a string selected by a find? (i.e. I want to repeat my search for the regex, not the next resulting found string from the regex)
> 
> Thanks!

 I don’t think there is a good way to replace the last Find value.

 You might want to claer “Use Word at Cursor in Find/Replace Dialog Box” in the Search tab of the Customize dialog box so the Find string will always become the last searched string.

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
<li><a href="https://instagram-clips.techidaily.com/new-instagram-fraud-busters-efficient-and-economical-methods-for-2024/"><u>[New] Instagram Fraud Busters Efficient & Economical Methods for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-achieve-unprecedented-image-quality-via-av1-on-youtube/"><u>2024 Approved Achieve Unprecedented Image Quality via AV1 on YouTube</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/discover-the-best-online-utilities-for-quick-and-easy-digital-imaging-snipping/"><u>Discover the Best Online Utilities for Quick and Easy Digital Imaging Snipping</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/easy-techniques-for-successfully-transferring-mp3-files-onto-your-ipad/"><u>Easy Techniques for Successfully Transferring MP3 Files Onto Your iPad</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/essential-applications-for-seamless-live-video-broadcasting-on-mac-devices/"><u>Essential Applications for Seamless Live Video Broadcasting on Mac Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Realme GT Neo 5? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-custom-commands-in-chatgpt-the-best-practices/"><u>Mastering Custom Commands in ChatGPT: The Best Practices</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/navigating-apowersoft-pdf-shrinker-tutorial-a-comprehensive-guide-for-efficient-file-management/"><u>Navigating Apowersoft PDF Shrinker Tutorial: A Comprehensive Guide for Efficient File Management</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-itel-a05s-by-fonelab-android-recover-data/"><u>Recover lost data from Itel A05s</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-the-issue-of-full-disk-space-on-your-windows-10-pc/"><u>Solving the Issue of Full Disk Space on Your Windows 10 PC</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/ultimate-guide-mastering-animal-crossing-pocket-camp-on-your-computer/"><u>Ultimate Guide: Mastering Animal Crossing: Pocket Camp on Your Computer</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

