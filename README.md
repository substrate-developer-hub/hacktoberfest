## Welcome to Hacktoberfest @ Parity

[![Gitter](https://img.shields.io/gitter/room/substrate-developer-hub/community)]

_WORK IN PROGRESS_

Join us for Hacktoberfest 2019. Hack on parity and related technologies, solve issues or take on a bigger challenge pushing the boundaries of the technology that will run the next generation of the internet. Oh, and get exclusive swag on top of that!

## Participate in 3 easy steps

 1. Pick _four_ [hacktoberfest-tagged issue from any parity](https://github.com/search?q=user%3Aparitytech+label%3Ahacktoberfest+state%3Aopen&type=Issues) repository or [rust-libp2p](https://github.com/libp2p/rust-libp2p/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Ahacktoberfest)
    OR pick any _one_ [larger project](https://github.com/substrate-developer-hub/hacktoberfest/issues)
 2. Hack on them, submit a PR, get it reviewed and merged
 3. Claim your reward (see [FAQ](/faq.html) to learn how)


<div markdown="1" style="text-align: center">

## Chat with us

[![Substrate Dev Hub Community on Gitter](assets/gitter-button.png)](https://gitter.im/substrate-developer-hub/community) [![Substrate Technical on Matrix](assets/matrix-button.png)](https://riot.im/app/#/room/#substrate-technical:matrix.org)

</div>


## Getting help

There are multiple ways to in which we offer to help you working on the projects and issues:
 - mentors mentioned in ticket/issue
   - just asking questions on the ticket itself
 - Meat-World Events
 - link to gitter & matrix
 - link to reddit, forum, other places

## Associated Events

 - events listed here.

## Hackers
_Submit a PR filling in [this template](https://github.com/substrate-developer-hub/hacktoberfest/blob/master/_hackers/_template.md) to be listed here_

{% assign mentors = site.hackers | where: "role", "mentor"  %}
{% assign participants = site.hackers | where: "role", "participant"  %}

<style>
ul.unstyled {
    list-style: none;
    padding: 0;
    margin: 0;
}

ul.unstyled li {
    display: inline-block;
}

ul.unstyled li img {
    width: 100px;
    display: inline-block;
}

</style>

<ul class="unstyled">
{% for hackor in participants  %}
    <li>
        <a href="https://github.com/{{hackor.github}}" title="{{hackor.name}}"><img src="https://github.com/{{hackor.github}}.png" alt="{{hackor.name}}"/>
        </a>
    </li>
{% endfor %}
</ul>

**Mentors**
<ul>
{% for hackor in participants  %}
    <li>
        <a href="https://github.com/{{hackor.github}}" title="{{hackor.github}}">{{hackor.name}}
        </a>
        {% if hackor.matrix %}<a title="matrix: {{hackor.matrix}}" href="https://riot.im/{{hackor.matrix}}">m</a>{% endif %}
        {% if hackor.twitter %}<a title="twitter: {{hackor.twitter}}"  href="https://twitter.com/{{hackor.twitter}}">t</a>{% endif %}
    </li>
{% endfor %}
</ul>