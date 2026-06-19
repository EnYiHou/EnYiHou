# En Yi Hou

**Machine learning & reinforcement learning researcher-builder**  
McGill CS graduate · incoming graduate student in Advanced Computing at Tsinghua University

I work on model-based AI: world models, planning, reinforcement learning, and robot learning. I like systems that learn an internal model of their environment, use it to reason about consequences, and know when an action is worth its cost.

[Portfolio](https://portfolio.enyihou.me) · [CV](https://portfolio.enyihou.me/cv/en-yi-hou-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/enyi-hou/) · [Email](mailto:enyi.hou@gmail.com)

---

## Current Direction

`model-based RL` · `world models` · `planning` · `robot learning` · `cost-aware intervention` · `reproducible ML`

Right now I am focused on embodied decision-making and intervention policies: how agents can learn from teachers, when a teacher should step in, and how to make that tradeoff measurable instead of implicit.

I am also interested in the engineering layer around research: clean benchmarks, runnable pipelines, readable experiment code, and tools that make real workflows less annoying.

## Featured Work

### [Cost-Aware Teacher-Side Intervention in RoboPianist](https://github.com/EnYiHou/robopianist-cost-aware-intervention)

<sub>Research artifact · Python · PyTorch · JAX/Flax · MuJoCo · RoboPianist</sub>

A reproducible pipeline for studying when teacher intervention is worth paying for in a high-dimensional robot-control task.

- Built a 14,464-row Human-Like Proxy Error benchmark from curated RoboPianist checkpoints.
- Compared learned intervention models with budgeted and cost-aware baselines.
- Packaged the work with paper source/PDF, figures, scripts, and an end-to-end run path.

[Paper](https://github.com/EnYiHou/robopianist-cost-aware-intervention/blob/main/report.pdf) · [Code](https://github.com/EnYiHou/robopianist-cost-aware-intervention) · [Figures](https://github.com/EnYiHou/robopianist-cost-aware-intervention/tree/main/figures)

### [McLecture](https://github.com/EnYiHou/mclecture)

<sub>Shipped tool · TypeScript · React · Vite · Chrome MV3 · FFmpeg/WASM</sub>

A Chrome Web Store extension that helps McGill students save myCourses lecture recordings locally as MP4 files.

- Built recording discovery, multi-select download queues, quality choices, and browser-local state.
- Uses bundled FFmpeg assets for local remuxing and avoids remote analytics or third-party course-data services.
- Maintained with TypeScript, ESLint/Prettier, Vitest, Vite, and Playwright screenshot automation.

[Chrome Web Store](https://chromewebstore.google.com/detail/mclecture/ipnhkfogmlokecmpgjhdkkibomgbjmlb) · [Code](https://github.com/EnYiHou/mclecture)

## Working Stack

**Research:** `Python` · `PyTorch` · `JAX/Flax` · `MuJoCo` · `RoboPianist` · `pandas` · `scikit-learn`  
**Engineering:** `TypeScript` · `React` · `Vite` · `Chrome Extensions` · `Vitest` · `Playwright` · `SQL`  
**Interests:** `model-based AI` · `planning` · `embodied agents` · `applied NLP` · `open-source research tooling`

## Open-Source Direction

I am trying to make more of my work usable outside my own machine: research repos with clear entrypoints, small tools that solve specific friction, and writeups that expose the assumptions behind the result.

## Elsewhere

For papers, figures, case studies, CV, and the fuller portfolio:  
**[portfolio.enyihou.me](https://portfolio.enyihou.me)**