---
title: Presentation
permalink: /presentation/
---
### Upcoming lab meetings
Every Thursday, we get together (mix of virtual and in person) for lab presentations (with food! sometimes).
On a rotating basis, each member of the lab speaks and teaches about something they know or shares their work. 
Anything, really. Relevant and interesting topics, good skills to know, nice Python packages, CSS trends, new findings and literature reviews... anything!

<div id="diagram-spring2026"></div>
<div id="diagram-fall2025"></div>
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
  mermaid.initialize({
    startOnLoad: false,
    theme: 'base',
    themeVariables: {
      cScale0: '#f5f5f5',
      cScale1: '#e8e8e8',
      cScale2: '#f5f5f5',
      cScale3: '#e8e8e8',
      cScale4: '#f5f5f5',
      cScale5: '#e8e8e8',
      cScale6: '#f5f5f5',
      cScale7: '#e8e8e8',
      cScaleLabel0: '#1a1a1a',
      cScaleLabel1: '#1a1a1a',
      cScaleLabel2: '#1a1a1a',
      cScaleLabel3: '#1a1a1a',
      cScaleLabel4: '#1a1a1a',
      cScaleLabel5: '#1a1a1a',
      cScaleLabel6: '#1a1a1a',
      cScaleLabel7: '#1a1a1a',
      cScalePeer0: '#ffffff',
      cScalePeer1: '#f9f9f9',
      cScalePeer2: '#ffffff',
      cScalePeer3: '#f9f9f9',
      cScalePeer4: '#ffffff',
      cScalePeer5: '#f9f9f9',
      cScalePeer6: '#ffffff',
      cScalePeer7: '#f9f9f9',
      titleColor: '#1a1a1a',
      textColor: '#1a1a1a',
      lineColor: '#999999',
    }
  });

  const spring2026 = await mermaid.render('timeline-spring2026', `timeline
      title Spring Semester, 2026
          03/05 : Presenter - Maida : location - N4 1412-2 : Time - 13:00 ~
          03/19 : Presenter - MK : location - N4 1412-2 : Time - 13:00 ~
          04/02 : Presenter - ER : location - N4 1412-2 : Time - 13:00 ~
          04/16 : Presenter - HJ : location - N4 1412-2 : Time - 12:00 ~
          04/30 : Presenter - JH : location - N4 1412-2 : Time - 13:00 ~
          05/14 : Party : Time - 11:30 ~
          05/28 : Presenter - Maida : location - N4 1412-2 : Time - 13:00 ~
          06/11 : Presenter - KJ : location - N4 1412-2 : Time - 13:00 ~`);
  document.getElementById('diagram-spring2026').innerHTML = spring2026.svg;

  const fall2025 = await mermaid.render('timeline-fall2025', `timeline
      title Fall Semester, 2025
          9/08 : Presenter - YoungTeak : location - N4 1334 : Time - 14:00 ~
          9/18 : Presenter - Maida : location - N4 1334 : Time - 13:00 ~
          10/01 : Canceled
          10/16 : Presenter - KyungJong Kim : location - N4 1334 : Time - 13:00 ~
          10/30 : Presenter - HyeongJae Lee : location - N4 1334 : Time - 13:00 ~
          11/06 : Presenter - Jiyoon Beak : location - N4 1334 : Time - 13:00 ~
          11/20 : Presenter - Maida : location - N4 1334 : Time - 14:00 ~
          12/04 : Presenter - JiHyang Chun, EunRang Kwon : location - N4 1334 : Time - 13:00 ~`);
  document.getElementById('diagram-fall2025').innerHTML = fall2025.svg;
</script>

<hr>
