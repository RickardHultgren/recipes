<script>
document.getElementById("blogsmall").style.backgroundColor="#EFAB00";
document.getElementById("blogtext").style.color="#000000";
document.getElementById("blog").className="menu2active";
</script>
A sandbox for shaping ideas about how information technology can be employed in medical care.<br><br>
<span id="Rss" style="display:table;"> [<i class="material-icons" style="background-color:#EFAB00;color:#ffffff;font-size:1.5em;margin-top:.5em; margin-bottom:-.5em;display: table-cell;vertical-align: middle;">&#xE0E5;</i><span style="vertical-align: middle;display:table-cell;">&nbsp;atom feed </span> ](http://rickardhultgren.github.io/lympha/atom.xml)</span>
<br>
{% for post in site.posts %}
{{ post.date | date_to_string }} &raquo; <a href="/recipes{{post.url}}">{{ post.title }}</a>
{% endfor %}

