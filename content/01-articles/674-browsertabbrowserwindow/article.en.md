Title: BrowserTab.browserWindow
----
Date: 2012-04-25 06:09:07
----
Lang: en
----
Author: 
----
License: Creative Commons Attribution 3.0 Unported
----
License_url: http://creativecommons.org/licenses/by/3.0/
----
Text:

<h2>Description:</h2>

<p>The readonly <code>browserWindow</code> attribute exposes the context window. On getting, the browserWindow attribute returns a BrowserWindow object representing the context window.</p>

<p class="note">This attribute is named <code>browserWindow</code> and not <code>window</code> to avoid confusion with the global <code>window</code> object.</p>

<h2>Syntax:</h2>

<p><code>readonly BrowserWindow browserWindow</code></p>

<h2>Example:</h2>

<p>The following example creates a button on the browser toolbar. When the button is clicked, the current tab&#39;s parent window is detected. If the window is not private, a new private window is opened with the URL of the current tab.</p>

<pre><code>//
// The background process (e.g. index.html) 
//

// Specify the properties of the button before creating it.
var UIItemProperties = {
  disabled: false,
  title: &quot;Example extension&quot;,
  icon: &quot;images/icon_18.png&quot;,
  onclick: function() {
    // Get the currently selected tab
    var thisTab = opera.extension.tabs.getSelected();
    
    // Get the tab&#39;s browser window
    var thisWin = thisTab.browserWindow;
    
    // If the window is not private, open a new private window with the tab&#39;s URL
    if (thisWin.private === false) {
      opera.extension.windows.create([{url: thisTab.url}], {private: true});
    }
    
  }
};

// Create the button and add it to the toolbar.
var button = opera.contexts.toolbar.createItem( UIItemProperties );  
opera.contexts.toolbar.addItem(button);</code></pre>
