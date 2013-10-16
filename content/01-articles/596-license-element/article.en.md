Title: license element
----
Date: 2011-12-06 07:08:11
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

<h2>Description</h2>

<p>The <code>&lt;license&gt;</code> element mentions the software license. The following attributes are associated with it.</p>

<ul>
    <li><code><a href="http://www.w3.org/TR/widgets/#the-href-attribute/">href</a></code>: Specifies a URL for accessing the software license</li>
</ul>

<h2>Example</h2>

<p>The following is an example of licensing an extension under version 2 of the Apache license.</p>

<pre><code>&lt;?xml version=&quot;1.0&quot; encoding=&quot;utf-8&quot;?&gt;
&lt;widget xmlns=&quot;http://www.w3.org/ns/widgets&quot; id=&quot;http://example.com/myExtension&quot; version=&quot;1.0&quot;&gt;
  ...
  &lt;license href=&quot;http://www.apache.org/licenses/LICENSE-2.0&quot;&gt;
    Copyright 2011 Erik the Viking

    Licensed under the Apache License, Version 2.0 (the &quot;License&quot;);
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an &quot;AS IS&quot; BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
  &lt;/license&gt;
  ...
&lt;/widget&gt;</code></pre>