<h1>Custom HYBRID Grid-Based Framework (Made With SASS!)</h1>

<h3>Introduction</h3>
<p>
    Recently, I gained a lot of interest in CSS preprocessors, mainly Sass.
    So, I decided it was time to venture and started learning said tool.
    This is the result of one study/practice session.
</p>

<h3>What's inside?</h3>
<p>
    This custom framework includes:
</p>
<ul>
    <li>
        Colors:
        <code>class="bg-alert text-success bg-warning text-info bg-transparent text-light bg-dark"</code>
    </li>
    <li>
        Font Weights:
        <code>class="thin reg bold extra"</code>
    </li>
    <li>
        Font Sizes (including breakpoints):
        <code>class="text-xs text-sm text-md text-lg text-xl"</code>
        Optional breakpoints: <code>class="text-lg md-text-sm sm-text-xs"</code>
        [sm-text-??] = max-width: 800px | [md-text-??] = max-width: 1200px 
    </li>
    <li>
        Padding:
        <code>class="x-padding-xs [up to] x-padding-xl"</code>
        <code>class="y-padding-xs [up to] y-padding-xl"</code>
    </li>
    <li>
        Margin:
        <code>class="x-margin-xs [up to] x-margin-xl"</code>
        <code>class="y-margin-xs [up to] y-margin-xl"</code>
    </li>
    <li>
        Custom Grid Sections
        <code>class="container-full container-half container-third"</code>
        [full] = 12 sections | [half] = 6 sections | [third] = 4 sections
    </li>
    <li>
        Span (including breakpoints):
        <code>class="span-1 [up to] span-12"</code>
        Optional breakpoints: <code>class="span-5 md-span-7 sm-span-12"</code>
        [sm-span-??] = max-width: 800px | [md-span-??] = max-width: 1200px 
    </li>
    <li>
        Start (including breakpoints):
        <code>class="start-1 [up to] start-12"</code>
        Optional breakpoints: <code>class="start-5 md-start-7 sm-start-12"</code>
        [sm-start-??] = max-width: 800px | [md-start-??] = max-width: 1200px 
    </li>
</ul>

<h3>Conclusion</h3>
<p>I learned a lot about using logic in Sass and how it can help speed up styles creation, I will definitely be using Sass as frequently as possible</p>