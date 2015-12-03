---
layout: "v2_fluid/docs_base"
version: "nightly"
versionHref: "/docs/v2/nightly"
path: ""
category: api
id: "{{Segment | slugify}}"
title: "Segment"
header_sub_title: "Class in module "
doc: "Segment"
docType: "class"
---



<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic2/tree/master/ionic/components/segment/segment.ts#L3'>
    View Source
  </a>
  &nbsp;
  <a href='http://github.com/driftyco/ionic2/edit/master/ionic/components/segment/segment.ts#L3'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  Segment



</h1>





<p>A Segment is a group of buttons, sometimes known as Segmented Controls, that allow the user to interact with a compact group of a number of controls.</p>
<p>Segments provide functionality similar to tabs, selecting one will unselect all others. You should use a tab bar instead of a segmented control when you want to let the user move back and forth between distinct pages in your app.</p>





<pre><code class="lang-html">&lt;ion-segment [(ng-model)]=&quot;relationship&quot; danger&gt;
  &lt;ion-segment-button value=&quot;friends&quot;&gt;
    Friends
  &lt;/ion-segment-button&gt;
  &lt;ion-segment-button value=&quot;enemies&quot;&gt;
    Enemies
  &lt;/ion-segment-button&gt;
&lt;/ion-segment&gt;


&lt;form [ng-form-model]=&quot;myForm&quot;&gt;
  &lt;ion-segment ng-control=&quot;mapStyle&quot; danger&gt;
    &lt;ion-segment-button value=&quot;standard&quot;&gt;
      Standard
    &lt;/ion-segment-button&gt;
    &lt;ion-segment-button value=&quot;hybrid&quot;&gt;
      Hybrid
    &lt;/ion-segment-button&gt;
    &lt;ion-segment-button value=&quot;sat&quot;&gt;
      Satellite
    &lt;/ion-segment-button&gt;
  &lt;/ion-segment&gt;
&lt;/form&gt;
</code></pre>




<h1 class="class export">Segment <span class="type">class</span></h1>
<p class="module">exported from <a href='undefined'>ionic/ionic</a><br/>
defined in <a href="https://github.com/driftyco/ionic2/tree/master/ionic/components/segment/segment.ts#L4-L125">ionic/components/segment/segment.ts (line 4)</a>
</p>
<h2>Directive</h2>
  <span>selector: ion-segment</span>




