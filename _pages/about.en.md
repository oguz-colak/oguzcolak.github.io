---
permalink: /
title: "Welcome"
lang: en
author_profile: true
---

<p>I am Oğuz /oˈɣuz/, a librarian at Istanbul Rami Library. My academic and professional work focuses on the technological transformation of knowledge and information management, the sustainability of digital data, and the discoverability of information.</p>

<h2>Research Interests</h2>

<p>The core areas that define my professional and academic work:</p>

<style>
  .accordion-item {
    border: 1px solid #e0e0e0;
    margin-bottom: 10px;
    border-radius: 5px;
    overflow: hidden;
    transition: border-color 0.2s;
  }
  .accordion-header {
    cursor: pointer;
    margin: 0;
    padding: 15px;
    background: #f9f9f9;
    color: #333333;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 1.1em;
    transition: background 0.2s, color 0.2s;
  }
  .accordion-header:hover {
    background: #f1f1f1;
  }
  .accordion-content {
    padding: 15px;
    margin: 0;
    color: #555555;
    line-height: 1.6;
    background: #ffffff;
    transition: background-color 0.2s, color 0.2s;
  }
  html[data-theme="dark"] .accordion-item {
    border-color: #555555;
  }
  html[data-theme="dark"] .accordion-header {
    background: #333333;
    color: #ffffff;
  }
  html[data-theme="dark"] .accordion-header:hover {
    background: #444444;
  }
  html[data-theme="dark"] .accordion-content {
    background: #252525;
    color: #dddddd;
  }
</style>

<div x-data="{ active: null }" class="accordion" style="margin-bottom: 2em; margin-top: 1.5em;">
  <div class="accordion-item">
    <h3 x-on:click="active = active === 1 ? null : 1" class="accordion-header">
      Library Discovery Systems and Interfaces
      <span x-show="active !== 1" style="font-weight: bold; color: #5fa9ee;">+</span>
      <span x-show="active === 1" style="font-weight: bold; color: #5fa9ee;">-</span>
    </h3>
    <div x-show="active === 1" x-collapse>
      <p class="accordion-content">How effectively users can discover digitized information is one of the most critical areas in librarianship. I work on the user interface design of discovery tools, optimization of search algorithms, and the ability to query heterogeneous data sources through a single interface — focusing not just on storing information, but on enabling its meaningful discovery.</p>
    </div>
  </div>

  <div class="accordion-item">
    <h3 x-on:click="active = active === 2 ? null : 2" class="accordion-header">
      Electronic Resource Management
      <span x-show="active !== 2" style="font-weight: bold; color: #5fa9ee;">+</span>
      <span x-show="active === 2" style="font-weight: bold; color: #5fa9ee;">-</span>
    </h3>
    <div x-show="active === 2" x-collapse>
      <p class="accordion-content">I professionally manage the lifecycle of databases, e-books and e-journals that constitute a large share of modern library budgets and usage. I develop collection strategies through e-resource licensing processes, access protocols (proxy, Shibboleth, etc.) and usage statistics analysis.</p>
    </div>
  </div>

  <div class="accordion-item">
    <h3 x-on:click="active = active === 3 ? null : 3" class="accordion-header">
      Scholarly Communication and Open Science Infrastructure
      <span x-show="active !== 3" style="font-weight: bold; color: #5fa9ee;">+</span>
      <span x-show="active === 3" style="font-weight: bold; color: #5fa9ee;">-</span>
    </h3>
    <div x-show="active === 3" x-collapse>
      <p class="accordion-content">I believe scientific outputs should be seen not merely as publications but as reusable datasets. I develop projects around building the Open Science ecosystem, managing institutional academic repositories, and standardizing research data in accordance with FAIR (Findable, Accessible, Interoperable, Reusable) principles. Removing barriers to information and democratizing scholarly communication are among my core interests.</p>
    </div>
  </div>

  <div class="accordion-item">
    <h3 x-on:click="active = active === 4 ? null : 4" class="accordion-header">
      Linked Data and Bibliographic Standards
      <span x-show="active !== 4" style="font-weight: bold; color: #5fa9ee;">+</span>
      <span x-show="active === 4" style="font-weight: bold; color: #5fa9ee;">-</span>
    </h3>
    <div x-show="active === 4" x-collapse>
      <p class="accordion-content">I closely follow Linked Data technologies to ensure library data becomes part of the web rather than being confined to library catalogs. I conduct technical work on converting bibliographic records (MARC, RDA) to semantic web standards (Bibframe, Schema.org) and making library metadata interpretable by search engines like Google.</p>
    </div>
  </div>
</div>

<p>My goal is to contribute to the future of knowledge by combining library science traditions with the modern tools of data science.</p>
