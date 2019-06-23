---
view: page
title: "1. Pregătire"
---

<h3>Obiective</h3>

<ul><li>Pregătire avansată pentru a lucra cu Git.</li></ul>

<h2><em>01</em> Setarea numelui și adresei e-mail</h2>

<p>Dacă dvs niciodată nu ați utilizat git, mai întâi trebuie să setați numele și adresa e-mail. Rulați următoarele comenzi pentru ca git să cunoască numele si adresa dvs e-mail. Dacă git este instalat deja, puteți sări peste acest pas.</p>

<h4 class="h4-pre">Rulați:</h4>

<pre class="instructions">git config --global user.name "Numele dvs"
git config --global user.email "adresa@poștală.com"</pre>

<h2><em>02</em> Opțiunile de setare la sfârșitul liniei</h2>

<p>Deasemenea, pentru utilizatorii Unix/Mac:</p>

<h4 class="h4-pre">Rulați:</h4>

<pre class="instructions">git config --global core.autocrlf input
git config --global core.safecrlf true</pre>

<p>Pentru utilizatorii Windows:</p>

<h4 class="h4-pre">Rulați:</h4>

<pre class="instructions">git config --global core.autocrlf true
git config --global core.safecrlf true</pre>