---
title: Plerd
repo: jmacdotorg/plerd
homepage: http://jmac.org/plerd/
language:
  - Perl
license:
  - MIT
templates:
  - TT2
description: Ultralight Dropbox-friendly Markdown-based blogging.
---

Plerd is a minimalist blogging platform for people who love writing with <a href="http://daringfireball.net/projects/markdown/">Markdown</a> using their favorite text editors, and who wish to host their own blogs as simple, attractive, static websites wholly under their own control.

<a href="https://github.com/jmacdotorg/plerd">Plerd is free and open-source software</a>, regularly used and actively maintained by its creator. All bloggers everywhere may use Plerd themselves at no cost, however they see fit.

<h2 id="aliveexample">A live example</h2>

Plerd&#8217;s creator, Jason McIntosh, publishes <a href="http://fogknife.com">his blog</a> entirely with Plerd. It&#8217;s just a static website. Every time Jason adds or edits a post, Plerd&#8217;s daemon processes modify the site&#8217;s files as needed.

<h2 id="features">Features</h2>

Plerd&#8217;s strength comes from its minimalism. It gives you the ability to turn a folder of Markdown files on your computer into a beautiful, easy-to-edit website, and leaves the rest up to you.

<ul>
<li>Support for exactly one user per blog. No authentication to worry about, nor multi-user complexities to set up.</li>
<li>Outputs completely static websites. No server-side scripting to tangle with.</li>
<li>No user interface at all, other than your favorite text editor and your own computer&#8217;s file system.

<ul>
<li>Create posts by adding Markdown files into a designated directory.</li>
<li>Edit posts by editing the files within that directory using any text editor you wish. Plerd will update your blog every time you save changes to your file.</li>
<li>Delete posts by moving files outside of that directory.</li>
<li><strong>Works great with Dropbox!</strong> If you keep your blog-source directory in Dropbox, then you can edit posts as local files on your laptop.</li>
</ul></li>
<li>Requires no extra database setup. Your one directory of directly-editable Markdown files represents the entirety of your blog&#8217;s data source.</li>
<li>Minimal metadata: no categories, no tags. Just your posts, their titles, and their timestamps.</li>
<li>Gives your blog an RSS feed and an archives page, both always kept up to date.</li>
<li>Your blog&#8217;s static HTML is generated by completely customizable <a href="http://template-toolkit.org">Template Toolkit</a> files.

<ul>
<li>The default templates are based on <a href="http://getbootstrap.com">Bootstrap</a>, capable of generating a beautiful, modern, responsive website out of the box.</li>
<li>The default templates also give your blog a search engine, via <a href="http://duckduckgo.com">DuckDuckGo</a>.</li>
<li>You can add external features like Disqus comments, Google Analytics, and Twitter widgets simply by pasting them into your templates.</li>
</ul></li>
</ul>

<h2 id="howplerdworks">How Plerd works</h2>

Plerd includes a daemon-style program called &#8220;plerdwatcher&#8221; which monitors a specific directory for changes. Every time it sees a change, it treats all the Markdown files inside at directory as blog posts, applying them to a set of templates. Within moments, it has generated a complete blog website, including an updated RSS feed.

That&#8217;s it.

<h2 id="installationanddocumentation">Installation and documentation</h2>

Installing Plerd involves downloading the software, running a single command-line invocation to get all its prerequisites into place, and then configuring it to taste.

For now, you may find all Plerd documentation on <a href="https://github.com/jmacdotorg/plerd#readme">the project&#8217;s GitHub page</a>. Installation assumes access to a Unix command line.

<h2 id="support">Support</h2>

You can file bugs or feature requests &#8211; or propose software patches &#8211; on <a href="https://github.com/jmacdotorg/plerd">Plerd&#8217;s GitHub page</a>.

<h2 id="authorcontact">Author contact</h2>

The Plerd project was created and is maintained by Jason McIntosh (<a href="&#x6d;&#x61;&#105;&#x6c;&#x74;&#111;&#58;&#x6a;&#x6d;&#x61;&#x63;&#64;&#106;&#109;&#x61;&#99;&#46;&#111;&#114;&#103;">&#106;&#109;&#x61;&#99;&#x40;&#106;&#x6d;&#97;&#x63;&#x2e;&#x6f;&#x72;&#x67;</a>), who always welcomes comments and feedback.

