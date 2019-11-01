## Welcome to Hacktoberfest 2019 @ Parity

## Hackers
_[Submit a PR to be listed here](faq/#how-can-i-submit-my-profile-for-the-front-page)_

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
{% for hacker in participants  %}
    <li>
        <a href="https://github.com/{{hacker.github}}" title="{{hacker.name}}"><img src="https://github.com/{{hacker.github}}.png" alt="{{hacker.name}}"/>
        </a>
    </li>
{% endfor %}
</ul>

### Submissions

- [Substrate Naming Service](https://github.com/hskang9/substrate-naming-service/tree/master), [original issue](https://github.com/substrate-developer-hub/hacktoberfest/issues/20)

**Mentors**

{% for hacker in mentors  %}
- [{{hacker.name}} ({{hacker.github}})](.{{ hacker.url }})
{% endfor %}
