# Robotics Berlin Meetup

*Next meetup:* <a href="#news-1">25th Mar 2019, 7 pm, at the PTScientists office</a>

The Berlin Robotics Meetup is an informal meeting of robotics professionals and enthusiast from academia and industry in Berlin. As Berlin is becoming a hub for AI and robotics, this event enables us to build a community of robotics in Berlin to network and share insights. 

We plan to hold it semi-regularly, roughly every two month at different locations announced here. We refrain from having formal talks, to lower the burden of preparation on the participants. It is more like a _Stammtisch_ than a traditional meetup. We want to chat about the latest findings in your field of expertise, your problems of implementing that crazy IROS paper, or simply making fun on how every robot keeps on breaking every other day.

New (groups of) people are encouraged to introduce themselves and what they work on related to robotics with a short talk not longer than 5 minutes. You're not allowed to bring presentations, but you can either draw on a white board/flip chart or *bring your robot*.

What this is not:

* a recruiting event of any of the participating companies
* a forum to give introductory talks on robotics topics
* your way into robotics if you just heard it's the next big thing.

Discussions regarding the meetup will be on a good old <a href="https://groups.google.com/group/robotics-berlin">email group</a>.

---
## News
{% for post in site.posts %}
  <article>
    <h3 id="news-{{ forloop.index }}">
       {{ post.title }}
    </h3>
    <p>
    <small>posted at <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time> &middot; by {{ post.user }}</small>
    </p>
    {{ post.content }}
  </article>
{% endfor %}
