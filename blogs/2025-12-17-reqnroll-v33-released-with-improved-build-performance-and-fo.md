---
title: "Reqnroll v3.3 released with improved build performance and formatter enhancements"
url: "https://reqnroll.net/news/2025/12/reqnroll-v3-3-released/"
date: "2025-12-17T00:00:00+00:00"
author: "Gaspar Nagy"
feed_url: "https://reqnroll.net/feed.xml"
---
<p>Reqnroll v3.3 has been released, bringing improved build performance, enhanced formatter configuration options, and support for linked feature files.</p>

<!--more-->

<p>This release focuses on build optimization, better file handling flexibility, and improved compatibility with the latest testing frameworks.</p>

<h2 id="whats-new-in-v33">What’s new in v3.3</h2>

<h3 id="improvements">Improvements</h3>

<ul>
  <li><strong>Improved build performance:</strong> Up-to-date checking for feature files has been improved, resulting in faster builds. Code-behind files are now deleted on clean or rebuild for better incremental build support.</li>
  <li><strong>Intermediate output folder support:</strong> Feature code-behind files can now be stored in the intermediate output folder (obj folder) by setting the <code class="language-plaintext highlighter-rouge">ReqnrollUseIntermediateOutputPathForCodeBehind</code> MSBuild property to <code class="language-plaintext highlighter-rouge">true</code>.</li>
  <li><strong>Linked feature files support:</strong> Reqnroll now supports linked feature files (files used from outside of the project folder). The <code class="language-plaintext highlighter-rouge">ReqnrollUseIntermediateOutputPathForCodeBehind</code> flag must be enabled to use this feature.</li>
  <li><strong>Formatter variable substitution:</strong> Formatters’ configured OutputFilePath can now contain variable substitution parameters for build metadata, timestamp, and environment variables. See the <a href="https://docs.reqnroll.net/latest/installation/formatter-configuration.html#available-substitution-variables">formatter configuration documentation</a> for details.</li>
  <li><strong>Updated testing framework support:</strong> NUnit dependencies are updated to v4.4.0 in templates, and TUnit integration now supports TUnit v1.3.25 and .NET 10 SDK compatibility.</li>
  <li><strong>Updated Cucumber integrations:</strong> Cucumber.HtmlFormatter updated to version 22 to support HTML reports on non-https URLs, and Cucumber.Messages updated to version 30.</li>
  <li><strong>Improved packaging:</strong> Reqnroll NuGet packages have been improved for better quality and compatibility.</li>
  <li><strong>Updated behavior:</strong> NotImplementedException thrown by tests is no longer treated as a “pending” outcome, reverting to v2 behavior.</li>
</ul>

<h3 id="bug-fixes">Bug Fixes</h3>

<p>This release also includes several bug fixes related to stability and error handling.</p>

<h2 id="full-changelog">Full changelog</h2>

<p>For a complete list of all changes, please see the <a href="https://github.com/reqnroll/Reqnroll/releases/tag/v3.3.0">v3.3.0 changelog on GitHub</a>.</p>

<p>If you encounter any issues, please report them on <a href="https://github.com/reqnroll/Reqnroll/issues">GitHub</a>.</p>

<p>Thank you to all contributors for this release! 🙏</p>

<center>🎅 <b>Happy Holidays from the Reqnroll team!</b>🎄</center>

<figure class="document-figure aligncenter">
  <img alt="Reqnroll Logo with Santa Hat (generated with AI)" src="https://reqnroll.net/assets/images/2025/reqnroll-icon-xmas-small.webp" style="width: 200px; height: auto;" /></figure>
