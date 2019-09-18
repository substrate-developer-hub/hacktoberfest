## Welcome to Hacktoberfest @ Parity

_WORK IN PROGRESS_

Join us for Hacktoberfest 2019. Hack on parity and related technologies, solve issues or take on a bigger challenge pushing the boundaries of the technology that will run the next generation of the internet. Oh, and get exclusive swag on top of that!

## Participate in 3 easy steps

 1. Pick four hacktoberfest-tagged issue from any parity repository or rust-libp2p
    OR pick any one bigger project
 2. Hack on them, submit a PR, get it reviewed and merged
 3. Claim your award (see below)

## Getting help

There are multiple ways to in which we offer to help you working on the projects and issues:
 - mentors mentioned in ticket/issue
   - just asking questions on the ticket itself
 - Meat-World Events
 - link to gitter & matrix
 - link to reddit, forum, other places

## Associated Events

 - events listed here.

## Particpants
_Submit a PR filling in [this template]() to be listed here_

{% assign mentors = site.hackers | where: "role", "mentor"  %}
{% assign participants = site.hackers | where: "role", "participant"  %}

<ul>
{% for hackor in participants  %}
    <li>
        <a href="https://github.com/{{hackor.github}}" title="{{hackor.github}}"><img src="https://github.com/{{hackor.github}}.png" width="100" alt="{{hackor.github}}"/>
        </a>
    </li>
{% endfor %}
</ul>

**Mentors**
<ul>
</ul>