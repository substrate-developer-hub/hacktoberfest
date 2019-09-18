## Welcome to Hacktoberfest @ Parity

_There will be more info here soon! Currently mostly notes for fillers_

## How to participate

 - Outline general rules
 - hacktoberfest-tags-URL to parity-search
 - Bigger modules and rules about that
 - sign up form for swag

## Getting help

 - Meat-World Events
 - link to gitter & matrix
 - link to reddit, forum, other places

## Associtated Events

 - events listed here.

## Particpants
_Submit a PR filling in [this template]() to be listed here_

<ul>
{% for hackor in site.hackers | where: "role", "participant"  %}
    <li>
        <a href="https://github.com/{{hackor.github}}" title="{{hackor.github}}"><img src="https://github.com/{{hackor.github}}.png" width="100" alt="{{hackor.github}}"/>
        </a>
    </li
{% endfor %}
</ul>

**Mentors**
<ul>
{% for hackor in site.hackers | where: "role", "mentor"  %}
    <li>
        <a href="https://github.com/{{hackor.github}}">{{hackor.name}}</a>
    </li>
    <!-- ADD MATRIX AND OTHER WAYS TO CONTACT -->
{% endfor %}
</ul>