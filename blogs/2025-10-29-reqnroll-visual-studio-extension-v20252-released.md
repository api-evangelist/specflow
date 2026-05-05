---
title: "Reqnroll Visual Studio Extension v2025.2 released"
url: "https://reqnroll.net/news/2025/10/reqnroll-visual-studio-extension-v2025-2-released/"
date: "2025-10-29T00:00:00+00:00"
author: "Gaspar Nagy"
feed_url: "https://reqnroll.net/feed.xml"
---
<p><strong>Reqnroll Visual Studio Extension v2025.2 has been released with improvements to the ‘New Project’ wizard, table formatting enhancements, and bug fixes.</strong></p>

<!--more-->

<p>A new version of the Reqnroll Visual Studio 2022 extension has been released: v2025.2.359 (<a href="https://github.com/reqnroll/Reqnroll.VisualStudio/releases/tag/v2025.2.359">Release notes</a>).</p>

<p>If you have installed an earlier version of the Reqnroll Visual Studio extension, it will by default automatically update to the latest version. You can also install the extension by searching for “Reqnroll” in the Visual Studio “Manage Extensions…” dialog. Please find the detailed instructions in <a href="https://go.reqnroll.net/doc-setup-vs">Visual Studio 2022 setup guide</a>.</p>

<h2 id="whats-new">What’s new</h2>

<h3 id="improvements">Improvements</h3>

<p>The release includes several useful improvements:</p>

<ul>
  <li><strong>Updated ‘New Project’ wizard</strong>: The wizard now uses the latest versions of supported test frameworks and .NET frameworks, including .NET 10 support.</li>
  <li><strong>xUnit v3 support</strong>: You can now select xUnit v3 as a test framework when creating new projects.</li>
  <li><strong>Enhanced table formatting</strong>: The ‘Format Document’ command now right-aligns numeric values in tables by default, improving readability. If you prefer left alignment, you can override this by setting <code class="language-plaintext highlighter-rouge">gherkin_table_cell_right_align_numeric_content = false</code> in your <code class="language-plaintext highlighter-rouge">.editorconfig</code> file within a <code class="language-plaintext highlighter-rouge">[*.feature]</code> section.</li>
</ul>

<h3 id="bug-fixes">Bug fixes</h3>

<p>The release also addresses several issues:</p>

<ul>
  <li>Fixed ambiguous steps being reported when a definition matches via more than one tag</li>
  <li>Fixed incorrect binding language detection in the Visual Studio extension</li>
  <li>Fixed the ‘New Project’ wizard to prevent specifying project names that result in invalid namespaces for generated code-behind files</li>
</ul>

<h2 id="visual-studio-2026-insiders-support">Visual Studio 2026 Insiders support</h2>

<p>The Reqnroll Visual Studio extension also supports the new <a href="https://visualstudio.microsoft.com/insiders/"><strong>Visual Studio 2026 Insiders</strong></a> version, which is a preview version of Visual Studio 2026. This ensures you can use the latest Reqnroll features even if you’re testing the upcoming Visual Studio release.</p>

<h2 id="feedback">Feedback</h2>

<p>Reqnroll is free, but we provide dedicated support through our <a href="https://reqnroll.net/support/">paid subscription packages</a>. Purchasing them will also support the <a href="https://go.reqnroll.net/sustainability">sustainability of the open-source project</a>.</p>

<p>If you find any issues or have ideas, please use our <a href="https://go.reqnroll.net/community-support">community support channels</a> to report them.</p>

<p>📢 Please take a few minutes and help others by rating ⭐ the extension on the <a href="https://go.reqnroll.net/vs2022-extension">Visual Studio Marketplace</a>.</p>
