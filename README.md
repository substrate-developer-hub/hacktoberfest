## Welcome to Hacktoberfest @ Parity

[![Gitter](https://img.shields.io/gitter/room/substrate-developer-hub/community)](https://gitter.im/substrate-developer-hub/community)

Join us for Hacktoberfest 2019. Hack on parity and related technologies, solve issues or take on a bigger challenge pushing the boundaries of the technology that will run the next generation of the internet. Oh, and get exclusive swag on top of that!

## Participate in 3 easy steps

### ✍️ 1. Sign up
[Fill in and submit the signup form](https://docs.google.com/forms/d/e/1FAIpQLSfQFLveEHTF5MECDNT2eP74SM3aSG_jxfufjyXQohKcc0sUyw/viewform) to let us know you are taking part. You can also optionally raise a PR against this repo to include your profile down below - [just fill in this template](https://github.com/substrate-developer-hub/hacktoberfest/blob/master/_hackers/_template.md). We recommend you also join us on chat either on [gitter](https://gitter.im/substrate-developer-hub/community) or [matrix](https://matrix.to/#/room/#substrate-technical:matrix.org).

### 💡 2. Select

Pick any _four_ [hacktoberfest-tagged issue from any parity](https://github.com/search?q=user%3Aparitytech+label%3Ahacktoberfest+state%3Aopen&type=Issues) or the [rust-libp2p](https://github.com/libp2p/rust-libp2p/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Ahacktoberfest) repository, or choose _one_ [larger project](https://github.com/substrate-developer-hub/hacktoberfest/issues), we have preprepared for you. Post a comment to let the mentors know you intend to work on it.

You can also suggest your own, see the [FAQ](faq/#reward)s, how.

### ⛏️ 3. Work it
Hack on the issue. You can do that by yourself, with the mentor (if available) or join us for any of the [real world and remote events](#events) we are hosting for hacktoberfest. Once your work is ready, submit the PR and engage with the reviewers to get it merged.

With your work and the form submitted before Nov 1st, all you have to do is wait for us to confirm your contribution and await your sweet, sweet reward 🎉!

More in the [FAQ](faq/#reward)s.


<div markdown="1" style="text-align: center; margin-top:15px">

## Chat with us

[![Substrate Dev Hub Community on Gitter](assets/gitter-button.png)](https://gitter.im/substrate-developer-hub/community) or [![Substrate Technical on Matrix](assets/matrix-button.png)](https://matrix.to/#/room/#substrate-technical:matrix.org)

</div>

<span id="events" style="display:block; padding-top: 10px"></span>
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
<ul class="unstyled">
{% for hackor in mentors  %}
    <li>
      <a href=".{{ hackor.url }}" title="{{hackor.name}}"><img src="https://github.com/{{hackor.github}}.png" alt="{{hackor.name}}"/></a>
    </li>
{% endfor %}
</ul>
