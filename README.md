## Welcome to Hacktoberfest @ Parity

[![Gitter](https://img.shields.io/gitter/room/substrate-developer-hub/community)](https://gitter.im/substrate-developer-hub/community)

_WORK IN PROGRESS_

Join us for Hacktoberfest 2019. Hack on parity and related technologies, solve issues or take on a bigger challenge pushing the boundaries of the technology that will run the next generation of the internet. Oh, and get exclusive swag on top of that!

## Participate in 3 easy steps

 1. Either: Pick _four_ [hacktoberfest-tagged issue from any parity](https://github.com/search?q=user%3Aparitytech+label%3Ahacktoberfest+state%3Aopen&type=Issues) repository or [rust-libp2p](https://github.com/libp2p/rust-libp2p/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Ahacktoberfest)
    Or: pick any _one_ [larger project](https://github.com/substrate-developer-hub/hacktoberfest/issues)
 2. Hack on them, submit a PR, get it reviewed and merged
 3. Claim your reward (see [FAQ](faq/#reward) to learn how)


<div markdown="1" style="text-align: center">

## Chat with us

[![Substrate Dev Hub Community on Gitter](assets/gitter-button.png)](https://gitter.im/substrate-developer-hub/community) or [![Substrate Technical on Matrix](assets/matrix-button.png)](https://riot.im/app/#/room/#substrate-technical:matrix.org)

</div>

## or join us for an event near you (or remotely)

- **Oct 1st** 15:00 CEST Substrate Starters Workshop, Berlin Community Space
- **Oct 1st** 18:30 CEST Substrate'n'Chill Hacktoberfest Kick Off, Berlin Community Space
- **Oct 7th** 18:00 CEST Substrate Collaborative Learning Hacktoberfest edition (2 hours, https://zoom.us/j/440029011)
- **Oct 8th**-11th [Devcon](https://devcon.org/), Osaka, Japan
- **Oct 8th** 18:30 CEST Substrate'n'Chill Hacktoberfest-Edition, Berlin Community Space
- **Oct 11th** 14:00 CEST Substrate Collaborative Learning Hacktoberfest edition (2 hours, [via Matrix](https://matrix.to/#/!trdlqNGrCsZpYUZoXa:matrix.parity.io?via=matrix.parity.io&via=matrix.org)) with Ben & Kaichao
- **Oct 14th** 18:00 CEST Substrate Collaborative Learning Hacktoberfest edition (2 hours, https://zoom.us/j/440029011)
- **Oct 15th** 18:30 CEST Substrate'n'Chill Hacktoberfest-Edition, Berlin Community Space
- **Oct 18th** 14:00 CEST Substrate Collaborative Learning Hacktoberfest edition (2 hours, [via Matrix](https://matrix.to/#/!trdlqNGrCsZpYUZoXa:matrix.parity.io?via=matrix.parity.io&via=matrix.org)) with Ben & Kaichao
- **Oct 18th**-19th [Rust BeltRust](https://www.rust-belt-rust.com/), Dayton, Ohio
- **Oct 19th**-20th Workshop and Mentoring at [Diffusion Hackathon](https://diffusion.events/), Factory Berlin
- **Oct 21st** 18:00 CEST Substrate Collaborative Learning Hacktoberfest edition (2 hours, https://zoom.us/j/440029011)
- **Oct 22th** 18:30 CEST Substrate'n'Chill Hacktoberfest-Edition, Berlin Community Space
- **Oct 29th** 18:30 CEST Substrate'n'Chill Hacktoberfest-Edition, Berlin Community Space
- **Oct 28th**-31st [SF Blockchain week](https://sfblockchainweek.io/), San Francisco



For further questions regarding the process, how to claim the reward and also other ways and places to get help, **please [consult the FAQs](faq/)** and don't hesitate to post your questions on our chat!

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
{% for hackor in mentors  %}
    <li>
        <a href=".{{ hackor.url }}" title="{{hackor.name}}">{{hackor.name}}</a>
    </li>
{% endfor %}
</ul>
