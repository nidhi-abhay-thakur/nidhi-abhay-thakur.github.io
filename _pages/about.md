---
layout: about
title: about
permalink: /
subtitle: Integrated MSc. Life Sciences at <a href='https://www.niser.ac.in/'>NISER Bhubaneswar</a> · Neuroscience

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p><strong>Nidhi A. Thakur</strong></p>
    <p>School of Biological Sciences</p>
    <p>NISER Bhubaneswar, Odisha</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* Scoped to the landing page. Colors come from the theme's own custom
     properties, so everything follows light/dark mode automatically. */
  .nt-lede {
    font-size: 1.18rem;
    line-height: 1.75;
    max-width: 62ch;
  }
  .nt-lede strong {
    font-weight: 600;
    color: var(--global-theme-color);
  }
  .nt-trace {
    display: block;
    width: 100%;
    max-width: 460px;
    height: auto;
    margin: 2.6rem 0 2.2rem;
    overflow: visible;
  }
  .nt-trace .nt-wave {
    fill: none;
    stroke: var(--global-theme-color);
    stroke-width: 1.6;
    stroke-linecap: round;
    stroke-linejoin: round;
    opacity: 0.9;
  }
  .nt-trace .nt-baseline {
    stroke: var(--global-divider-color);
    stroke-width: 1;
    stroke-dasharray: 3 4;
  }
  .nt-trace .nt-caption {
    fill: var(--global-text-color-light);
    font-size: 8.5px;
    font-style: italic;
    letter-spacing: 0.01em;
  }
  /* The trace draws itself once on load: one deliberate moment, not a
     per-section effect. Respects reduced-motion. */
  @media (prefers-reduced-motion: no-preference) {
    .nt-trace .nt-wave {
      stroke-dasharray: 620;
      stroke-dashoffset: 620;
      animation: nt-draw 2.1s cubic-bezier(0.32, 0.72, 0.35, 1) 0.25s forwards;
    }
  }
  @keyframes nt-draw {
    to {
      stroke-dashoffset: 0;
    }
  }
  .nt-where dt {
    font-weight: 600;
    color: var(--global-text-color);
    margin-top: 1.05rem;
    font-size: 0.99rem;
  }
  .nt-where dd {
    margin: 0.12rem 0 0;
    color: var(--global-text-color-light);
    font-size: 0.94rem;
    line-height: 1.6;
  }
  .nt-where dd .nt-place {
    color: var(--global-theme-color);
  }
  .nt-closing {
    margin-top: 2.4rem;
    padding-left: 1.1rem;
    border-left: 2px solid var(--global-theme-color);
    font-size: 1.03rem;
    line-height: 1.7;
    max-width: 60ch;
  }
</style>

<p class="nt-lede" markdown="1">
I am a fourth-year **Integrated MSc.** student in Life Sciences at [NISER Bhubaneswar](https://www.niser.ac.in/), supported by a **DST-INSPIRE Fellowship**. I work on the electrophysiology of memory and its disorders — recording from brain slices to ask a fairly stubborn question: *when memory fails, where exactly does the synapse give way?*
</p>

<svg class="nt-trace" viewBox="0 0 460 96" role="img" aria-label="A stylised field excitatory post-synaptic potential recording: a sharp stimulus artifact, a downward synaptic slope, and a slow return to baseline.">
  <line class="nt-baseline" x1="0" y1="46" x2="460" y2="46" />
  <path
    class="nt-wave"
    d="M0,46 L96,46 L104,15 L110,64 L118,46 L132,49 L150,72 L176,80 L206,74 L246,62 L296,52 L352,47 L410,46 L460,46"
  />
  <text class="nt-caption" x="0" y="93">fEPSP — stimulus artifact, synaptic slope, recovery</text>
</svg>

## where I have worked

<dl class="nt-where">
  <dt>Temporal lobe epilepsy, and the hormones that modulate it</dt>
  <dd><span class="nt-place">Epilepsy Neurobiology Lab, AIIMS Delhi.</span> Patch clamp on resected human brain tissue, asking how the estrogen/progesterone ratio shapes seizure susceptibility.</dd>

  <dt>Synaptic plasticity in Alzheimer's disease models</dt>
  <dd><span class="nt-place">Synaptic Plasticity and Memory Lab, NUS.</span> Recording fEPSPs in rodent hippocampal slices — the signal in the drawing above.</dd>

  <dt>What traumatic brain injury leaves behind</dt>
  <dd><span class="nt-place">DRDO-INMAS, Delhi.</span> Neurobehavioural paradigms paired with histopathology, as an <strong>IASc-INSA-NASI Summer Research Fellow</strong>.</dd>

  <dt>Polyamines and GnRH alternative splicing</dt>
  <dd><span class="nt-place">BITS Pilani, Goa.</span> Molecular neuroendocrinology in the hypothalamic GT1-7 cell line; presented at NCURB, IISER Tirupati.</dd>
</dl>

<div class="nt-closing" markdown="1">
Away from the rig, I run **[The NeuroReach Initiative]({{ '/outreach/' | relative_url }})** — brain science carried to dementia care centres, hospital wards, and classrooms, sometimes on canvas. I am also President of **Brain Matters**, NISER's neuroscience club.

Always glad to talk about hippocampal recordings, stubborn baselines, or science outreach.

</div>
