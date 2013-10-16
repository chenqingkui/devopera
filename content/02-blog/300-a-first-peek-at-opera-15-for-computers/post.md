Title: A first peek at Opera 15 for Computers
----
Date: 2013-05-28 06:00:00
----
Author: 
----
Text:

<p>Hurrah! Hot on the heels of the release of <a href="http://my.opera.com/ODIN/blog/opera-14-for-android-is-out">Opera 14 for Android</a> (based on Chromium 26), here&#39;s a first peek at our all new Opera for Computers. It&#39;s called <a href="http://www.opera.com/next/">Opera Next 15</a> and it&#39;s based on Chromium 28 — which means that it comes with <a href="http://www.chromium.org/blink">Blink</a> on board — but as it&#39;s an evergreen browser with a <a href="http://my.opera.com/desktopteam/blog/opera-features-and-release-cycle" target="_blank">fast release cycle</a>, we don&#39;t recommend reading too much into the digits — it&#39;s what&#39;s in it that counts!</p>

<p>This is a stable build — we&#39;ve been using it as our main browser for a while now —, but it isn&#39;t the final release - you can expect rapid updates in the weeks to come. Note that this Next build is available for Windows and Mac. A Linux version is coming later, but we wanted as many people to have a peek as soon as possible.</p>

<h2>So what&#39;s new?</h2>
<p>First, you&#39;ll notice a radically simpler UI that is nicely integrated with the platform. We want your Opera to feel native to your operating system — after all, it&#39;s probably the program you use the most apart from your OS.</p>

<p>Just like on Opera 14 for Android, we&#39;ve merged bookmarks into Speed Dial, which give you a visual overview of your favorite pages. You can now group Speed Dials together into folders, just by dragging one on top of the other — if you want, you can name the folder via a simple right-click.</p>
<p>To add a page or extension to Speed Dial, simply click on the big plus sign. You can also do this while you&#39;re browsing, of course: just click the &quot;Add to Speed Dial&quot; icon in the top right  corner of the address bar, and the page in question will be added to Speed Dial.</p>

<p>If you have a lot of Speed Dial items, you can click the search icon in the top right corner. Start typing in the field that appears, and your bookmarked sites will be filtered in real-time.</p>

<span class='imgcenter'><img alt='' src='http://files.myopera.com/brucelawson/blog/add-to-speed-dial.png' /></span> 

<h3>Stash</h3>

<p>Do you sometimes find yourself browsing the web, and coming across pages you want to save for later — e.g. a list of favorite gadgets on Amazon, or a selection of hotels on a booking site? This always posed a problem in the past, and many were using their tab bar to hold tabs for later use. With Opera 15, you can <strong>Stash</strong> a page, and return to it when you have time.</p>
<p>Simply hit the heart icon when you&#39;re on a page you like and whenever you want to return to it, open your Stash from the start page (open a new tab or click the Start Page icon to the left of the address field). When a page has already been added to your Stash, the address field icon will be highlighted to reflect that. You can click the highlighted icon to remove the page from your Stash.</p><span class='imgcenter'><img alt='' src='http://files.myopera.com/brucelawson/blog/stash.png' /></span>

<p>To adjust the size of your stashed items, use the slider to the right. If you have a lot of stashed items, you can click the search icon in the top right corner of the Stash page, and just like with Speed Dial, filter your stashed sites in real-time.</p>

<h3>Discover</h3>

<p>Discover is another new feature to Opera 14 for Android and Opera 15 for Computers, which helps you find interesting content to jump straight into browsing. Click the cog to change settings - select your language and location, and select subjects depending on your interests. For launch there are 13 categories in 32 languages.</p><span class='imgcenter'><img alt='' src='http://files.myopera.com/brucelawson/blog/discover.png' /></span> 

<h3>Combined address and search field</h3>

<p>Opera 15 for Computers has a combined address and search bar, showing suggestions (that can be turned off via Settings &gt; Privacy and Security) and multiple search providers.</p><span class='imgcenter'><img alt='' src='http://files.myopera.com/brucelawson/blog/smartbox.png' /></span>  

<h3>Off-road mode</h3>

<p>Just because you have a computer rather than a mobile device doesn&#39;t mean that you&#39;re always on fast wifi; you might be on shared wifi at a coffee shop, or your network might be slow today. Activating Off-Road Mode from the Opera Menu sends pages through Opera&#39;s compression servers, reducing the page size significantly by using a smart mix of image compression, SPDY and more. Note that rendering happens on the client side, so JavaScript will work without a problem. Secure (https) pages don&#39;t get sent through our proxy.</p>

<h3>Mouse gestures</h3>

<p>One of Opera&#39;s classic features, <a href="http://www.opera.com/help/tutorials/gestures/">mouse gestures</a>, let you perform common browsing actions with small, quick mouse movements. Note that on Mac they are by default disabled, since Mac has native support for system touch gestures.</p>
<p>Advanced keyboard shortcuts are also available, but are off by default. To enable them, go to Settings &gt; Browser &gt; Enable advanced keyboard shortcuts. And while your at it, have a look at the other advanced settings on opera:settings.</p>

<h3>For developers</h3>

<p>Developer tools are available behind a setting (More Tools &gt; Enable developer tools). You&#39;ll find there Web Inspector (Opera Dragonfly is not included in this release), the classic View Source option, and a list of installed browser plugins.</p>

<h3 id="extensions">Extensions</h3>
<p>With Opera switching to Chromium and this complete UI remake, our <a href="http://dev.opera.com/articles/view/major-changes-in-operas-extensions-infrastructure/" target="_blank">extensions infrastructure has also undergone a major overhaul</a>: from Opera 15 onward, Opera 11 and 12&#39;s extension format is no longer supported (and we&#39;ve <a href="https://github.com/operasoftware/operaextensions.js/tree/master/docs">archived its documentation on GitHub</a>), and instead, <strong>we&#39;ve switched to Chromium’s extension model</strong>. At this point, Opera 15 supports a subset of the Chromium extension APIs — with more to come — as well as our own <a href="http://dev.opera.com/extension-docs/tut_sd_extensions.html">Speed Dial API</a>.</p>
<p>If you&#39;re a Chromium extensions developer, be sure to submit your extensions to <a href="http://addons.opera.com/extensions/">our extensions catalog</a>! Extension developers like Evernote, Feedly, Disconnect, LastPass, WOT, Ghostery, and the very cool cottonTracks have already done this, and you can find their extensions <a href="https://addons.opera.com/en/extensions/">in the catalog</a>.</p>
<p>If you&#39;re new to Chromium extension development, we&#39;ve prepared a <a href="http://dev.opera.com/extension-docs/">number of tutorials</a> and have included relevant API documentation as well. We&#39;ve also built a <a href="https://github.com/operasoftware/oex2nex" target="_blank">conversion utility </a>into the developer interface of <a href="http://addons.opera.com/extensions/">our extensions catalog</a> to make the transition from the old to the new format as smooth as possible.</p>

<h3>What is not (yet) in Opera 15 for Computers?</h3>

<p>Opera 15 doesn&#39;t include the M2 mail client. Not all current Opera customers use M2, so to simplify the UI even further and reduce the footprint of the program, we&#39;ve decided to split it out into a separate product, called Opera Mail. You can <a href="http://my.opera.com/desktopteam/blog/opera-next-15-0-released/">get a preview build on the Desktop Team blog</a>.</p>

<p>Other features missing from the first release of Opera based on Chromium will be evaluated and potentially re-instated in future releases.</p>

<p><code>getUserMedia</code> isn&#39;t hooked up yet in Opera 15 and will be come back in a future release. W3C Geolocation is similarly dropped for the time being. It&#39;s a feature most used with mobile browsers, hence it&#39;s included in Opera 14 for Android. It will of course return in a future release.</p>

<p>The Developer Flags page is also still missing, although <a href="http://www.chromium.org/developers/how-tos/run-chromium-with-flags">select command line flags are available</a>. We plan to bring this back as well in the near future.</p>

<h3>Made to discover</h3>

<p>There&#39;s a lot inside Opera Next 15, with a simple, friendly and attractive user interface. Take a look around; in the settings you can disable cookies, pop-ups, plugins etc on a site-by-site basis, send a Do Not Track header, disable various speed-optimizing enhancements should you choose so. We hope you&#39;ll enjoy discovering its features, and maybe build some extensions for it!</p>