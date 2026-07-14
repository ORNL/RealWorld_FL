<h1 align="center">Trustworthy Privacy-Preserved Federated Learning for Science</h1>

<p align="center">
  <b>Birds-of-a-Feather</b> · Trillion Parameter Consortium 2026 (TPC26)<br>
  Baltimore, Maryland · Tuesday, June 2, 2026
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/federation-dark.svg">
    <img src="docs/federation-light.svg" alt="Eight institutional nodes surround a central aggregator. Model updates flow inward along each spoke while the local datasets stay pinned at their institution." width="360">
  </picture>
</p>

<p align="center"><i>The models travel between institutions. The sensitive data never does.</i></p>

<p align="center">
  <b>Session website → <a href="https://ornl.github.io/RealWorld_FL/">ornl.github.io/RealWorld_FL</a></b>
</p>

---

|            |                                                  |
| ---------- | ------------------------------------------------ |
| **When**   | Tuesday, June 2, 2026 at 14:00                    |
| **Where**  | Annapolis & Columbia, Baltimore, Maryland         |
| **Format** | Birds-of-a-Feather — 8 lightning talks + discussion |
| **Track**  | Infrastructure to Enable Shared Data & Computing  |

## The session

Federated learning offers a promising approach for enabling collaborative scientific discovery while
preserving the privacy of sensitive data across institutions. This BOF brought together researchers and
practitioners to discuss trustworthy, privacy-preserving federated learning frameworks tailored for
scientific workloads.

The discussion focused on challenges such as secure model aggregation, data confidentiality, system
scalability, and integration with distributed research infrastructures. Our objectives were to identify
common requirements, share emerging techniques, and foster collaborations within the TPC community —
work that continues past the session itself.

The session speaks to anyone in TPC working on distributed computing, secure data sharing, and scalable
AI methods that support cross-institutional scientific research.

## What we discussed

- **Secure model aggregation** — combining updates from many institutions without any single party,
  including the aggregator, learning more than it should.
- **Data confidentiality** — differential privacy, ownership protection, and the guarantees a data
  steward actually needs before agreeing to participate.
- **System scalability** — what breaks when a federation spans supercomputers, and what it takes to
  train a foundation model across facilities.
- **Integration with research infrastructure** — fitting federated workflows into the authentication,
  allocation, and data-governance realities of national labs and hospitals.

## Session leads

| Organizer | Affiliation |
| --------- | ----------- |
| **Olivera Kotevska** (lead) | Oak Ridge National Laboratory |
| **Kibaek Kim** | Argonne National Laboratory |
| **Ravi Madduri** | Argonne National Laboratory |

## Lightning talks

Slides are posted where the speaker has shared them.

| # | Talk | Speaker | Affiliation | Slides |
| -: | ---- | ------- | ----------- | ------ |
| 1 | NeuroFL: OBI's Intelligence Network for Brain Health | Francis Jeanson | Ontario Brain Institute | **[PDF](docs/slides/jeanson-neurofl-federated-data-network-for-brain-health.pdf)** |
| 2 | The Next Frontier: Federated AI with Flower | William Lindskog-Munzing | Flower Labs | **[PDF](docs/slides/lindskog-munzing-next-frontier-federated-ai-with-flower.pdf)** |
| 3 | Socio-Technical Infrastructure: Operationalizing FL Systems | Mohammed Manzari | Deloitte | — |
| 4 | Are You Ready for Production Federated Learning? | Holger Roth | NVIDIA | **[PDF](docs/slides/roth-are-you-ready-for-production-federated-learning.pdf)** |
| 5 | Federated LLM Training Across NNSA Labs | Max Carlson | Sandia National Laboratories | **[PDF](docs/slides/carlson-federated-llm-training-across-nnsa-labs.pdf)** |
| 6 | Scalable Cross-Facility Federated Learning for Scientific Foundation Models on Multiple Supercomputers | Yijiang Li | Argonne National Laboratory | **[PDF](docs/slides/li-scalable-cross-facility-federated-learning.pdf)** |
| 7 | OmniFed: Towards Configurable Cross-Silo Federated Learning | Sahil Tyagi | Oak Ridge National Laboratory | **[PDF](docs/slides/tyagi-omnifed-configurable-cross-silo-federated-learning.pdf)** |
| 8 | Differentially Private Federated Averaging with James–Stein Estimator | Minseok Ryu | Arizona State University | — |

Speakers: to add your deck here, send it to [kotevskao@ornl.gov](mailto:kotevskao@ornl.gov?subject=TPC26%20BOF%20slides).

## Get involved

The conversation didn't end in Baltimore. We are continuing to build a community around trustworthy,
privacy-preserving federated learning for science — shared requirements, common benchmarks, and
cross-institutional pilots. If you work in this space, or want to bring your facility's data into a
federation without giving it up, get in touch.

**Contact:** [kotevskao@ornl.gov](mailto:kotevskao@ornl.gov?subject=TPC26%20BOF%3A%20Trustworthy%20Privacy-Preserved%20Federated%20Learning)

---

<sub>The session website above is published with [GitHub Pages](https://docs.github.com/en/pages) from
[`docs/`](docs/) on `main` — a single self-contained page, [`docs/index.html`](docs/index.html), with
no build step, plus the speaker slides in [`docs/slides/`](docs/slides/). Edit, push to `main`, and the
site redeploys on its own. See also the
[full TPC26 session listing](https://tpc26.org/tpc26-sessions/).</sub>
