<h1 align="center">En Yi Hou</h1>

<p align="center">
  <strong>McGill CS graduate · upcoming Tsinghua graduate student</strong><br>
  Thinking about ML stuffs: world models, RL, etc.
  But occasionally making browsers thinggies :3
</p>

<p align="center">
  <a href="https://portfolio.enyihou.me">Portfolio</a>
  ·
  <a href="https://portfolio.enyihou.me/cv/en-yi-hou-cv.pdf">CV</a>
  ·
  <a href="https://www.linkedin.com/in/enyi-hou/">LinkedIn</a>
  ·
  <a href="mailto:enyi.hou@gmail.com">Email</a>
</p>

<p align="center">
  <code>world models</code>
  <code>model-based RL</code>
  <code>Representation</code>
</p>

---

I like agents that learn an internal model of the world, reason with it, and know when an action is worth its cost. Most of my work lives around model-based AI, embodied decision-making, and research code that other people can actually run.

```mermaid
flowchart LR
  W["world model"] --> P["planning"]
  P --> A["action"]
  A --> E["environment"]
  E --> W
  T["teacher / signal"] -.->|when is help worth it?| P

  style W fill:#0f172a,stroke:#38bdf8,color:#ffffff
  style P fill:#134e4a,stroke:#2dd4bf,color:#ffffff
  style A fill:#4c1d95,stroke:#a78bfa,color:#ffffff
  style E fill:#1f2937,stroke:#94a3b8,color:#ffffff
  style T fill:#7c2d12,stroke:#fb923c,color:#ffffff
```

## Selected Work

<table>
  <tr>
    <td width="52%">
      <a href="https://github.com/EnYiHou/robopianist-cost-aware-intervention">
        <img src="https://raw.githubusercontent.com/EnYiHou/robopianist-cost-aware-intervention/main/figures/cost_adjusted_evaluation.png" alt="Cost-adjusted evaluation summary for RoboPianist intervention models">
      </a>
    </td>
    <td width="48%">
      <h3>
        <a href="https://github.com/EnYiHou/robopianist-cost-aware-intervention">Cost-Aware Teacher-Side Intervention in RoboPianist</a>
      </h3>
      <p><sub>Research artifact · Python · PyTorch · JAX/Flax · MuJoCo · RoboPianist</sub></p>
      <p>A reproducible pipeline for asking a practical question: when is teacher intervention actually worth paying for?</p>
      <ul>
        <li>Built a 14,464-row Human-Like Proxy Error benchmark from curated RoboPianist checkpoints.</li>
        <li>Compared learned intervention models against budgeted and cost-aware baselines.</li>
        <li>Packaged paper, figures, scripts, and an end-to-end run path.</li>
      </ul>
      <p>
        <a href="https://github.com/EnYiHou/robopianist-cost-aware-intervention/blob/main/report.pdf">Paper</a>
        ·
        <a href="https://github.com/EnYiHou/robopianist-cost-aware-intervention">Code</a>
        ·
        <a href="https://github.com/EnYiHou/robopianist-cost-aware-intervention/tree/main/figures">Figures</a>
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="48%">
      <h3>
        <a href="https://github.com/EnYiHou/mclecture">McLecture</a>
      </h3>
      <p><sub>Shipped tool · TypeScript · React · Vite · Chrome MV3 · FFmpeg/WASM</sub></p>
      <p>A Chrome extension that helps McGill students save myCourses lecture recordings locally as MP4 files.</p>
      <ul>
        <li>Built recording discovery, quality selection, multi-download queues, and browser-local state.</li>
        <li>Uses bundled FFmpeg assets for local remuxing; no remote analytics or course-data services.</li>
        <li>Maintained with TypeScript, Vitest, Vite, and Playwright screenshot automation.</li>
      </ul>
      <p>
        <a href="https://chromewebstore.google.com/detail/mclecture/ipnhkfogmlokecmpgjhdkkibomgbjmlb">Chrome Web Store</a>
        ·
        <a href="https://github.com/EnYiHou/mclecture">Code</a>
      </p>
    </td>
    <td width="52%">
      <a href="https://github.com/EnYiHou/mclecture">
        <img src="https://raw.githubusercontent.com/EnYiHou/mclecture/main/screenshots/popup.png" width="49%" alt="McLecture course recording selection view">
      </a>
      <a href="https://github.com/EnYiHou/mclecture">
        <img src="https://raw.githubusercontent.com/EnYiHou/mclecture/main/screenshots/downloading.png" width="49%" alt="McLecture download queue view">
      </a>
    </td>
  </tr>
</table>

## Working Stack

| Research | Engineering | Current interests |
| --- | --- | --- |
| Python · PyTorch · JAX/Flax · MuJoCo · RoboPianist | TypeScript · React · Vite · Chrome Extensions · Vitest · Playwright | model-based AI · planning · embodied agents · applied NLP · open-source research tooling |

## Open Source Direction

Small, runnable things with clear entrypoints. Research repos with enough structure to survive outside my laptop. Tools that remove one annoying step from a real workflow.

## Elsewhere

For papers, figures, case studies, CV, and the fuller portfolio: **[portfolio.enyihou.me](https://portfolio.enyihou.me)**.
