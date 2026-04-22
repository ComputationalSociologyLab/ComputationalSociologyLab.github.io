---
title: Presentation
permalink: /presentation/
---
### Upcoming lab meetings
Every Thursday, we get together (mix of virtual and in person) for lab presentations (with food! sometimes).
On a rotating basis, each member of the lab speaks and teaches about something they know or shares their work. 
Anything, really. Relevant and interesting topics, good skills to know, nice Python packages, CSS trends, new findings and literature reviews... anything!

<div id="diagram"></div>
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
  mermaid.initialize({
    startOnLoad: false,
    theme: 'neutral'
  });
  const { svg } = await mermaid.render('timeline-svg', `timeline
      title Spring Semester, 2026
          03/05 : Presenter - Maida : location - N4 1412-2 : Time - 13:00 ~
          03/19 : Presenter - MK : location - N4 1412-2 : Time - 13:00 ~
          04/02 : Presenter - ER : location - N4 1412-2 : Time - 13:00 ~
          04/16 : Presenter - HJ : location - N4 1412-2 : Time - 12:00 ~
          04/30 : Presenter - JH : location - N4 1412-2 : Time - 13:00 ~
          05/14 : Party : Time - 11:30 ~
          05/28 : Presenter - Maida : location - N4 1412-2 : Time - 13:00 ~
          06/11 : Presenter - KJ : location - N4 1412-2 : Time - 13:00 ~`);
  document.getElementById('diagram').innerHTML = svg;
</script>

### Spring 2024
{% raw %}
| Date | Name | Topic |
|------|------|-------|
| Jan 16 [Tues] | Konrad K | TBD |
| Jan 26 [Fri] | K-lab retreat | N/A |
| Feb 2 | Lab business | Discussion |
| Feb 9 |Joey R. | Conformal Prediction |
| Feb 16 | Alessandro Lamacchia | Servers! |
| Feb 23 | Reading club | Episodic Memory |
| Mar 1 | Lab 1-1s | do 'em |
| Mar 8 | Lab 1-1s | do 'em |
| Mar 15 | ... | ... |
| Mar 22 | Tony | "Modern" Causal Inference |
| Mar 29 | ... | ... |
| Apr 5 |Felipe P | sts experiments, tracking |
| Apr 12 | Joey | How to program a brain |
| Apr 19 | 
| Apr 26 | ... | ... |
| May 3 | ... | ... |
| May 10 | Ilenna Jones | 
{% endraw %}

### **Presentation Materials**
<div class="content list">
  {% for post in site.posts %}
    {% if post.categories contains type %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">- {{ post.title }}</a>
      </p>
    </div>
</div>
<hr>
