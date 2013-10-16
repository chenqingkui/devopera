Title: Opera's WebKit patches
----
Date: 2013-03-22 13:26:17
----
Author: 
----
Text:

<p>About five weeks ago, we <a href="http://my.opera.com/ODIN/blog/300-million-users-and-move-to-webkit" target="_blank">announced</a> that Opera&#39;s products would transition to using WebKit. We said &quot;Opera will contribute to the WebKit and Chromium projects. Our work on web standards to advance the web continues.&quot;</p>

<p>Obviously, replacing a rendering engine is a huge engineering change, so we&#39;ve been working flat out, hooking up the new rendering engine, rewriting the UI, integrating new features and testing everything so that you can actually see products. (Have you tried <a href="http://my.opera.com/ODIN/blog/2013/03/05/opera-14-beta-for-android-is-out" target="_blank">Opera 14 beta for Android 2.3</a> and above yet?)</p>

<p>But we haven&#39;t forgotten our commitment to contributing back. Here are the patches we&#39;ve submitted to enhance any WebKit-based browser so that they better support CSS:</p>

<ul>
<li><a href="https://bugs.webkit.org/show_bug.cgi?id=15553">Bug 15553 - WebKit ignores column-rules wider than column-gap</a> - This patches a bug reported in 2007, and brings WebKit&#39;s multi-column support closer to the level of Presto that&#39;s in shipping versions of Opera</li>
<li><a href="https://bugs.webkit.org/show_bug.cgi?id=112986">Bug 112986 - Incorrect error handling for Media Queries</a> - WebKit fails to do correct error recovery for media queries a lot of cases. Not able to balance parentheses and brackets, not able to see valid media queries after an invalid one, and does not return &#39;not all&#39; for invalid queries</li>
<li><a href="https://bugs.webkit.org/show_bug.cgi?id=112549">Bug 112549 - monochrome media feature does not accept integer values</a> - The monochrome media feature should accept non-negative integers as specified in the Media Queries spec.</li>
</ul>

<p>There are also a number of house-keeping patches submitted by Morten to tidy up some WebKit code: <a href="https://bugs.webkit.org/show_bug.cgi?id=112442">Bug 112442</a>, <a href="https://bugs.webkit.org/show_bug.cgi?id=110123">110123</a>, and <a href="https://bugs.webkit.org/show_bug.cgi?id=110121">110121</a>.</p>
<p>Morten&#39;s currently looking at <a href="https://bugs.webkit.org/show_bug.cgi?id=52040">implementing CSS <code>object-fit</code></a> and <a href="https://bugs.webkit.org/show_bug.cgi?id=103597">further CSS multi-column improvements</a>. So don&#39;t disturb him until those patches land!</p>

<p>As products start to ship, we&#39;ll bring you more news of enhancements we&#39;re offering back.</p>
