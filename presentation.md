---
title: Presentation
permalink: /presentation/
---

### Upcoming lab meetings

Every Thursday, we get together (mix of virtual and in person) for lab presentations (with food! sometimes).
On a rotating basis, each member of the lab speaks and teaches about something they know or shares their work. 
Anything, really. Relevant and interesting topics, good skills to know, nice Python packages,
 princples, new findings and literature reviews... anything!

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Spring Semester 2026</title>
</head>
<body>
  <div id="diagram"></div>
  <script type="module">
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
    mermaid.initialize({
      startOnLoad: false,
      theme: 'base',
      themeVariables: {
        cScale0: '#e0e0e0',
        cScale1: '#d0d0d0',
        cScale2: '#e0e0e0',
        cScale3: '#d0d0d0',
        cScale4: '#e0e0e0',
        cScale5: '#d0d0d0',
        cScale6: '#e0e0e0',
        cScale7: '#d0d0d0',
        cScaleLabel0: '#333333',
        cScaleLabel1: '#333333',
        cScaleLabel2: '#333333',
        cScaleLabel3: '#333333',
        cScaleLabel4: '#333333',
        cScaleLabel5: '#333333',
        cScaleLabel6: '#333333',
        cScaleLabel7: '#333333',
        cScalePeer0: '#f5f5f5',
        cScalePeer1: '#ebebeb',
        cScalePeer2: '#f5f5f5',
        cScalePeer3: '#ebebeb',
        cScalePeer4: '#f5f5f5',
        cScalePeer5: '#ebebeb',
        cScalePeer6: '#f5f5f5',
        cScalePeer7: '#ebebeb',
        titleColor: '#333333',
        textColor: '#333333',
        sectionBkgColor: '#f5f5f5',
        altSectionBkgColor: '#ebebeb',
        lineColor: '#999999',
      }
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
</body>
</html>

</body>
</html>
### Fall 2024
{% raw %}
| Date       | Name   | Topic |
|------------|--------|-------|
| Sept 30    | Joey Rudoler | "How to explain LLMs" / general-audience science talks | 
| Oct 28     | None    | Lab 1:1 meetings   |
| Nov 4      | Melanie Segado    | Foundation models for movement (or similar) |
| Nov 11     | Joey Rudoler | Structured outputs for LLMs  |
| Nov 18     | Ansh Soni  | Conclusions about neural network to brain alignment are profoundly impacted by the similarity measure   |
| Nov 25     | Georgios Mentzelopoulos | Neural decoding from stereotactic EEG: accounting for electrode variability across subjects  |
| Dec 2      | Yihao Li  | LLM's as reasoners   |
| Dec 9      | Riley DeHaan  | Deconfounding experimental effects on neural activity |
| Dec 16     | TBD    | TBD   |

{% endraw %}


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
{% endfor %}

