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
    cScale0: '#fef9e7',
    cScale1: '#eafaf1',
    cScale2: '#fef9e7',
    cScale3: '#eafaf1',
    cScale4: '#fef9e7',
    cScale5: '#eafaf1',
    cScale6: '#fef9e7',
    cScale7: '#eafaf1',
    cScaleLabel0: '#5d4e37',
    cScaleLabel1: '#2e5e4e',
    cScaleLabel2: '#5d4e37',
    cScaleLabel3: '#2e5e4e',
    cScaleLabel4: '#5d4e37',
    cScaleLabel5: '#2e5e4e',
    cScaleLabel6: '#5d4e37',
    cScaleLabel7: '#2e5e4e',
    cScalePeer0: '#fffef5',
    cScalePeer1: '#f4fdf6',
    cScalePeer2: '#fffef5',
    cScalePeer3: '#f4fdf6',
    cScalePeer4: '#fffef5',
    cScalePeer5: '#f4fdf6',
    cScalePeer6: '#fffef5',
    cScalePeer7: '#f4fdf6',
    titleColor: '#3b3b3b',
    textColor: '#3b3b3b',
    lineColor: '#c5d6a0',
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
