<script>
document.getElementById( "aboutsmall").style.backgroundColor="#EFAB00";
document.getElementById( "abouttext").style.color="#000000";
document.getElementById( "about").className="menu2active";
</script>
<span class="sc">Lympha</span> is a programming language for formulating and handling medical protocols. The finished interpreters and compilers are thought to work as a <a class="sc" href="https://en.wikipedia.org/wiki/Clinical_decision_support_system">cdss</a>. The programs will consolidate different protocols and compare them with data from the patient. In this way new, more complex protocols and scenarios are built by the program. This differs from most other programming languages used for medical algorithms (e.g. <a href="https://en.wikipedia.org/wiki/CLIPS" class="sc">clips</a>). In those languages each possible scenario should be described by the programmer.<br>
<br>
The aim of the <span class="sc">lympha</span>-project is to create operating principles for the language, upon which interpreters and compilers are built. <span class="sc">Lympha</span> is open source (licensed under  <a href="http://opensource.org/licenses/BSD-2-Clause"><span class="sc">bsd 2</span></a>).<br><br>
<br>
<a name="progress" style="font-weight:bold;"></a>
<span style="font-style:italic">Progress</span><br>
Tasks in making version 1.0:
<p class="box">
<ul class="box">
<li><span class="checked">✔</span><a style="position:relative; z-index:1;" href="https://github.com/RickardHultgren/lympha/blob/master/LYMPHA_syntax.0.9.pdf">Syntax description in REGEX</a>; The syntax is completed.</li>
<li><span class="checked">&nbsp;</span>Make algorithms in:</li>
<ul>
<li><span class="checked">✔</span><a style="position:relative; z-index:1;" href="https://github.com/RickardHultgren/lympha/blob/master/LYMPHA_algorithm.0.9.pdf">Pseudocode</a>; The algorithms are completed.</li>
<li><span class="checked">&nbsp;</span><a style="position:relative; z-index:1;" href="https://github.com/RickardHultgren/lympha/tree/python">Python</a> module; A framework for a python library is prepared. The next step is to translate the pseudocode  into python.</li>
</ul></ul></p>
Future plans after version 1.0:
<ul>
<li>Make a <span class="sc">lympha</span>-script client app in <a href="https://kivy.org/">Kivy</a>. This would make <span class="sc">lympha</span> very useful.</li>
<li>Make scripts for the client in the field of mental health. Anxiety and depression could both be monitored as well as treated in some gegree through <span class="sc">madrs</span> script and <span class="sc">rebt</span>. This would be a very usefull tool for first line self-help.</li>
<li>Make a <a href="https://www.gnu.org/software/gforth/">GForth</a> branch of the <span class="sc">lympha</span> project. This would enable <span class="sc">lympha</span> to be used in more smaller devices.</li>
</ul>
<br><br><br>
<a name="use" style="font-weight:bold;"></a>
<span style="font-style:italic">Use</span><br>
The finished version is thought to consolidate different protocols and compare them with data from the patient. In this way, it would enable compters to propose what further diagnostics and treatments can be prescribed. In other words, it will be a <a href="https://en.m.wikipedia.org/wiki/Clinical_decision_support_system " class="sc">cdss</a> and a programming language for medical protocols. The python version should be command based program:
<pre class="dragscroll">
$> lympha script.lympha steps=5 start="airways"
</pre>
