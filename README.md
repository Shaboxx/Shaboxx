# Shawn Vazin

I build data pipelines, evaluate machine-learning models, and turn analytical work into software people can inspect and use. My interests are early-career data, AI, and software engineering roles where careful experimentation and practical product decisions matter.

These projects show how I work: define a bounded problem, make the data and assumptions explicit, compare against a baseline, and ship a reproducible example. Each repository starts with a quick start and separates measured results from limitations.

### Selected projects

| Project | What I built | What to inspect |
| --- | --- | --- |
| **[Budgeted Discovery](https://github.com/Shaboxx/budgeted-discovery)** | A reproducible platform for comparing data-acquisition strategies when requests, information, and feedback are limited. | Cost accounting, data-quality checks, five-strategy experiments, and a small runnable simulation. Historical main grid: **1,500 completed simulations** in a synthetic experimental setting. |
| **[Basketball Player Evaluation](https://github.com/Shaboxx/basketball-player-evaluation)** | A PyTorch model that separates offensive and defensive contributions, with transformations, explicit data contracts, and baseline evaluation. | A synthetic public example and an honest account of historical evaluation gates. Full development corpus: **1,396,353 possessions across 7,230 games**; individual training and evaluation splits are smaller. |
| **[AI-Assisted Video Editing](https://github.com/Shaboxx/ai-assisted-video-editing)** | A bounded editing workflow that turns local media into a proposed edit, requires review, and renders an inspectable output. | Deterministic pause removal, normalized source records, deduplication, and a synthetic media demonstration. The released editor uses rules; it does not claim a deployed learned editing model. |

### From analysis to an application

The separate **[Basketball Application](https://github.com/Shaboxx/basketball-app)** connects player and team exploration with basketball decision tools. Its project history explains the user needs behind the implementation and distinguishes original development from the public release.

### How I approach the work

- **Data engineering:** explicit contracts, source tracking, quality checks, and repeatable transformations.
- **AI and experimentation:** useful baselines, clear split boundaries, inspectable metrics, and visible failure cases.
- **Software and product judgment:** a working demonstration, understandable outputs, human review where it matters, and straightforward setup.

The basic project demonstrations use local fixtures and do not require external credentials. Historical measurements and newly reproduced outputs are labeled separately in each repository.
