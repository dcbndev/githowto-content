---
view: page
title: "3. Crearea proiectului"
---

<h3>Obiective</h3>

<ul><li>Învață să creezi repozitorii git de la zero.</li></ul>

<h2><em>01</em> Crează o pagină “Hello, World!”</h2>

<p>Începe să lucrezi într-un director de lucru gol (de exemplu, work, dacă ai descărcat arhiva din pasul precedent) și creează un director nou cu numele “hello”, accesează acest director, după care creează un file <code>hello.html</code> cu următorul conținut.</p>

<h4 class="h4-pre">Rulează:</h4>

<pre class="instructions">mkdir hello
cd hello
touch hello.html</pre>

<h4 class="h4-pre">File: <em>hello.html</em></h4>

<pre class="file">Hello, World!</pre>

<h2><em>02</em> Creaeză un repozitoriu</h2>

<p>Acum ai un director care conține un file. Rulează comanda <code>git init</code> pentru a crea un repozitoriu git din acest director.</p>

<h4 class="h4-pre">Rulează:</h4>

<pre class="instructions">git init</pre>

<h4 class="h4-pre">Rezultat:</h4>

<pre class="sample">$ git init
Initialized empty Git repository in /Users/alex/Documents/Presentations/githowto/auto/hello/.git/
</pre>

<h2><em>03</em> Adaugă pagina în repozitoriu</h2>

<p>Haide să adăugăm pagina “Hello, World” în acest repozitoriu.</p>

<h4 class="h4-pre">Rulează:</h4>

<pre class="instructions">git add hello.html
git commit -m "First Commit"</pre>

<p>Vei vedea;</p>

<h4 class="h4-pre">Rezultat:</h4>

<pre class="sample">$ git add hello.html
$ git commit -m "First Commit"
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 hello.html</pre>
