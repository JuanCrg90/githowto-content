---
view: page
title: "1. Preparación"
---

<h3>Metas</h3>

<ul><li>Estar plenamente preparado para trabajar con Git.</li></ul>

<h2><em>01</em> Establecer nombre y dirección de correo electrónico</h2>

<p>Si tu nunca haz usado git antes, primero tú necesitas establecer tú nombre y correo electrónico. Ejecuta las siguientes instrucciones para que git sepa tú nombre y tú dirección de correo electrónico. Si git ya está instalado, vaya hasta el final de la linea.</p>

<h4 class="h4-pre">Ejecute:</h4>

<pre class="instructions">git config --global user.name "Tú Nombre"
git config --global user.email "tu_correo@loquesea.com"</pre>

<h2><em>02</em> Opciones de instalación finales de linea</h2>

<p>Para usuarios de Unix/Mac:</p>

<h4 class="h4-pre">Ejecute:</h4>

<pre class="instructions">git config --global core.autocrlf input
git config --global core.safecrlf true</pre>

<p>Para usuarios de Windows:</p>

<h4 class="h4-pre">Ejecute:</h4>

<pre class="instructions">git config --global core.autocrlf true
git config --global core.safecrlf true</pre>
