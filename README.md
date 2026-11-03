# enGAUGE – engagement as a function of availability and experience

**Interaction layer.** An engagement gauge built on demand vs. supply.

For up to four team members, enter **number of projects** (demand: workload and therefore availability) and **years of experience** (supply: skill). Each member is plotted on a gauge image with experience along one axis and workload along the other, so the team can see at a glance who has capacity and who is stretched, and what AAPE level of engagement the team can expect from its current configuration.

Single-page jQuery.

## Try it

Open `index.html` in a browser, or visit the GitHub Pages build at https://lmedlock.github.io/enGAUGE/ (served from the `gh-pages` branch).

## Part of the eMoC prototype suite

This repository is one of a set of small web prototypes built at the Stanford [PBL Lab](http://pbl.stanford.edu/) for the research paper **"A Journey from Island of Knowledge to Mutual Understanding in Global Business Meetings"** (Renate Fruchter and Leonard Medlock, Stanford University, PBL Lab). The paper proposes a Mutual Understanding Metric (MUM) and an **engagement Matrix of Choices (eMoC)** to help globally distributed, cross-disciplinary teams make explicit choices about their work environment and reach higher levels of engagement.

eMoC is organized around the lab's **Bricks–Bits–Interaction (BBI)** framework, and each prototype covers one slice of it:

| Layer | Tool | Repo |
|---|---|---|
| Hub | eMoC landing page (BBI map linking to every tool) | [moc](https://github.com/lmedlock/moc) |
| Bricks (place) | coFlex – team control vs. flexibility as a function of location mix | [coflex](https://github.com/lmedlock/coflex) |
| Bricks (place) | locAAPE – engagement as a function of the kind of place each member works from | [locAAPE](https://github.com/lmedlock/locAAPE) |
| Bits (ICT) | ccKit – networks (ccNetw), devices (ccDev) and tools (ccTools) available to each member | [ccKit](https://github.com/lmedlock/ccKit) |
| Interaction | vSpeed – workload adjusted for virtuality | [vspeed](https://github.com/lmedlock/vspeed) |
| Interaction | [360°]eSkill – self-reported vs. team-perceived skill | [es360](https://github.com/lmedlock/es360) |
| Interaction | enGAUGE – engagement as a function of availability and experience | [enGAUGE](https://github.com/lmedlock/enGAUGE) |

Two vocabularies from the paper show up throughout the tools:

- **RAAAS** – whether ICT is Reliable, Available, Accessible, Affordable and Standard in a given situation.
- **AAPE** – four degrees of engagement: Awareness (hear each other), Attention (hear and see), Participation (plus co-control shared content), Engagement (plus co-create the space, content and products).

## Status

Rapid-prototyping artifact from early 2012, kept as-is for the record. Each tool is a single static `index.html` with inline jQuery; there is no build step and no backend. Some external assets (CDN-hosted jQuery/HTML5 shiv and icons once hosted at `ldt.stanford.edu`) may no longer resolve, so parts of the UI can appear unstyled or without images.

## Credits

Research: Renate Fruchter and Leonard Medlock, PBL Lab, Stanford University. Seed funding from MediaX and Konica Minolta. Page template adapted from [Tutorialzine](http://tutorialzine.com/2010/02/html5-css3-website-template/).
