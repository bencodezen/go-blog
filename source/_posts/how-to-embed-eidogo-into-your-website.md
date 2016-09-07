---
title: How to Embed Eidogo into Your Website
tags:
  - blogger
  - eidogo
  - how to
  - nate
id: 90
categories:
  - Guides
date: 2010-10-03 11:26:00
---

## <span style="text-decoration: underline;">Blogger / Blogspot (Google)</span>

**<span style="color: #800000;">_WARNING: Contrary to my previous findings, it seems that Blogger may actually not be compatible period with Eidogo anymore. Let me know if you find otherwise._</span>**

### Part 1: Putting the program into your blog.

1.  Access the control panel for your blog.
2.  Click **Template**.
3.  Click **Edit** **HTML**.
4.  A popup will appear that warns you the implications of editing HTML. Nothing to fear. Click **Proceed**.
5.  Once your text editor appears, search for the tag **&lt;/head&gt;.**
6.  Move your text cursor to the beginning of the tag and press the **Enter**/**Return** key to create an empty line.
7.  Copy and paste the following code in the new line break you just created.

    *   &lt;script type="text/javascript" src="http://www.eidogo.com/player/js/all.compressed.js"&gt;&lt;/script&gt;

8.  Click **Save** **template**.
9.  Part 1 complete!

### Part 2: Preparing your kifu for embedding.

1.  Download your desired kifu (which should be an SGF file).
2.  Open the SGF file in a text editor (e.g., Notepad).
3.  At the very beginning of the document, paste the following code:

    *   &lt;div class="eidogo-player-auto"&gt;

4.  Go to the very end of the document, paste the following code:

    *   &lt;/div&gt;

5.  Select the entire text and copy it.
6.  Part 2 complete!

### Part 3: Inserting your kifu into the post.

1.  Edit the post that you want to embed the sgf file into.
2.  On the left side above the text area, you should see two option: Compose | HTML, make sure that **Compose** is selected (it should have a darker gray background that looks as if it is indented).
3.  Move your text cursor to the area in the post that you want to post the SGF file to.
4.  Type **PASTE SGF FILE**.
5.  Click on the **HTML** tab mentioned in Step #5.
6.  Find the text you typed in Step #4\. It should look something like this:

    *   &lt;div&gt;PASTE SGF FILE&lt;/div&gt;

7.  Highlight the entire code mentioned in Step #6.
8.  Paste copied text from Part 2.
9.  Click **Save** or **Publish**.
10.  Success!

#### Disclaimers:

*   The Eidogo Viewer will not appear in the preview nor will it appear in the compose section. It'll just look like a gigantic text version of your sgf file. Don't worry though! It works on the actual site.
*   In case anyone is using SmartGo2 to create/modify their SGF file, the code they produce will cause Eidogo to not see the proper handicap, the players and their respective colors, komi, along with any commentary made throughout the game. As a result, I recommend that you use [CGoban](http://www.gokgs.com/download.jsp) instead.

<span style="text-decoration: underline;">_Many thanks to Nate for helping me create this guide and Eidogo for creating an amazing viewer!!_</span>

**_Last updated October 29th, 2012._**