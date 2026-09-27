---
title: "Contact"
permalink: /pcontact/
author_profile: false
---

<style>
  #pcontact-wrap {
    background-color: #FFFFFF;
    color: #004E6F;
    padding: 2.5em 1.5em;
    border-radius: 12px;
    max-width: 480px;
    margin: 0 auto;
    text-align: center;
    border: 1px solid #E5E5E5;
  }
  #pcontact-wrap h1 {
    color: #004E6F;
    margin-bottom: 0.2em;
  }
  #pcontact-wrap p.tagline {
    color: #0A0A0A;
    margin-top: 0;
    margin-bottom: 1.5em;
  }
  .pcontact-btn {
    display: block;
    background-color: #007CB0;
    color: #FFFFFF !important;
    padding: 0.9em 1em;
    margin: 0.6em 0;
    border-radius: 8px;
    text-decoration: none !important;
    font-weight: 600;
  }
  .pcontact-btn:hover {
    opacity: 0.9;
  }
  .pcontact-card {
    background-color: #F5FAFC;
    border-radius: 8px;
    padding: 1em;
    margin-top: 1.5em;
    text-align: left;
    font-size: 0.95em;
    line-height: 1.5;
  }
  .pcontact-link-btn {
    background-color: #FFFFFF;
    color: #007CB0;
    border: 1px solid #007CB0;
    border-radius: 6px;
    padding: 0.4em 0.8em;
    font-weight: 600;
    cursor: pointer;
    margin: 0.3em 0;
  }
  .pcontact-link-btn:hover {
    background-color: #F5FAFC;
  }
</style>

<div id="pcontact-wrap" markdown="0">
  <img src="/images/Abilities-First-logo.png" alt="Abilities First logo" style="max-width:220px; margin-bottom:1em;">
  <h1>SMART SOLUTIONS</h1>
  <p class="tagline">Technology that supports independence at Abilities First.</p>

  <a class="pcontact-btn" href="https://www.abilitiesfirstny.org/" target="_blank" rel="noopener">Visit Abilities First</a>

  <div class="pcontact-card">
    <strong>Crystal Jones-Howe</strong><br>
    Smart Solutions Administrator<br>
    Abilities First, Inc.<br><br>
    <button type="button" id="ss-call-btn" class="pcontact-link-btn">Call (voice)</button><br>
    <button type="button" id="ss-fax-btn" class="pcontact-link-btn">Fax number</button><br>
    Email: <a href="mailto:crystaljoneshowe@abilitiesfirstny.org">crystaljoneshowe@abilitiesfirstny.org</a><br>
    70 Overocker Road, Poughkeepsie, NY 12603
  </div>

  <a class="pcontact-btn" href="/files/crystal-jones-howe-work.vcf">Save My Contact Card</a>
  <a class="pcontact-btn" href="https://www.linkedin.com/in/cjoneshowe/">LinkedIn</a>
  <a class="pcontact-btn" href="mailto:crystaljoneshowe@abilitiesfirstny.org">Email Me</a>
</div>

<script>
  document.getElementById('ss-call-btn').addEventListener('click', function () {
    var parts = ['9803', '485', '845'];
    window.location.href = 'tel:+1' + parts.reverse().join('') + ',,1292';
  });
  document.getElementById('ss-fax-btn').addEventListener('click', function () {
    var parts = ['2047', '320', '845'];
    alert('Fax: (' + parts[2] + ') ' + parts[1] + '-' + parts[0]);
  });
</script>