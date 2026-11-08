# AI engineering and data science roadmap

**November 2026 → May 2027** · A working plan, not a list of completed skills.

The outcome is a small portfolio of reproducible work in Python and C++, with a clear path from data analysis to evaluated AI applications. Dates are targets; published results and review matter more than a streak.

| Period | Focus | Evidence to publish |
| --- | --- | --- |
| Nov–Dec 2026 | Python data workflow, Git, statistics, SQL basics; C++ standard library, algorithms, and tests. | One dataset analysis with provenance, cleaning steps, descriptive statistics, tests, and a short limitations section. One C++ algorithm study with correctness tests and runtime measurements. |
| Jan 2027 | Classical machine learning and experimental design. | A baseline and at least two models on one well-defined problem; a train/validation/test protocol, appropriate metrics, error analysis, and a reproducible run command. |
| Feb 2027 | Better data and evaluation practice. | Improve the January project with leakage checks, ablations, confidence or uncertainty analysis where appropriate, and a concise technical report. |
| Mar 2027 | Deep learning foundations. | A small, reproducible training experiment with a documented architecture, seed, data split, learning curves, baseline comparison, and failure cases. |
| Apr 2027 | AI application engineering and C++ performance. | An AI application prototype with scoped inputs, evaluation cases, cost and latency measurements, and safety limits; a C++ benchmark with a documented build and comparison method. |
| May 2027 | Portfolio polish and external review. | Two or three finished projects with readable READMEs, tests, reproducible setup, honest results, and limitations; at least one meaningful external review or open-source contribution. |

## Skill sequence

| Layer | Learn and demonstrate | Why it matters |
| --- | --- | --- |
| Mathematics | Descriptive statistics, probability, linear algebra, derivatives, and optimization basics. | Explains what a model measures, learns, and gets wrong. |
| Python data work | Virtual environments, NumPy, pandas, visualization, SQL, and tests. | Makes the path from raw data to an inspectable result repeatable. |
| Machine learning | scikit-learn, baselines, cross-validation, leakage prevention, metrics, and error analysis. | Separates a useful model from a convincing-looking notebook. |
| Deep learning | PyTorch fundamentals, training loops, checkpoints, experiment tracking, and reproducibility. | Builds the ability to test model ideas rather than only call an API. |
| AI applications | Retrieval and tool use where justified, evaluation sets, permission boundaries, latency, cost, and monitoring. | Turns a model into a controlled, measurable system. |
| C++ systems | Modern C++, data structures, CMake, tests, profiling, and benchmarks. | Supports efficient components and a sound understanding of inference costs. |
| Professional practice | Git, code review, CI, readable documentation, data licensing, and secret hygiene. | Lets others verify and safely build on the work. |

These are learning targets. A tool belongs in the profile as demonstrated experience only after a public project shows its use.

## First four weeks

1. **Week 1 — reproducible setup:** choose a public, licensed dataset; document the question, source, environment, and a run command. Add one Python test and one simple C++ test.
2. **Week 2 — data audit:** check missing values, duplicates, types, and potential leakage. Publish a short data dictionary and descriptive figures.
3. **Week 3 — baseline:** define a naive prediction or decision rule and a metric. Use a fixed split and record the result before trying a complex model.
4. **Week 4 — review:** rerun from a fresh checkout, correct weak assumptions, document failure cases, and request feedback on the result.

## Weekly operating rhythm

1. **Choose one question.** Write the expected outcome and how it will be checked.
2. **Work in small slices.** Spend 20–40 minutes on code, reading, testing, or analysis most days. A reading day can produce notes or an experiment plan; it does not need a commit.
3. **Commit real changes.** Commit after a useful result: a tested function, corrected analysis, reproducible experiment, or improved documentation. Use a descriptive message and a verified account email.
4. **Review on weekends.** Record what worked, what failed, and the next question. Make one small project or experiment reviewable each week.

## Project acceptance checklist

- Problem and intended user are stated plainly.
- Data source, license, and preparation steps are documented; private data and credentials are excluded.
- Setup and run instructions work from a fresh checkout.
- Tests cover the key behavior; results can be reproduced or their variability is explained.
- A simple baseline and the chosen evaluation metric are included.
- Failure cases, limitations, and the next experiment are visible.

GitHub's contribution graph is a record of qualifying activity, not a measure of skill. Scheduled workflows and empty commits are not substitutes for meaningful work. This plan supports a steady daily habit through May 2027 without promising a green square every day.
