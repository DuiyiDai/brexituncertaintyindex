# Brexit Uncertainty Index

News-based measures of aggregate and topic-specific Brexit uncertainty, developed for empirical economic research.

[Project website](https://duiyidai.github.io/brexituncertaintyindex/) · [Data and methodology](https://duiyidai.github.io/brexituncertaintyindex/_pages/data.html) · [Paper and citation](https://duiyidai.github.io/brexituncertaintyindex/_pages/publication.html)

## Research

The project measures Brexit uncertainty using coverage from 11 leading UK newspapers. Aggregate indices track uncertainty-related news; topic-specific indices describe its composition across issues such as trade policy, immigration, employment and Northern Ireland.

The methodology combines textual analysis with Word2Vec-assisted term selection and latent Dirichlet allocation for topic modelling. See the project website and paper for definitions and estimation details.

## Data coverage

The website currently documents data through **December 2022**. Download links, sources and methodological notes are available on the [data page](https://duiyidai.github.io/brexituncertaintyindex/_pages/data.html).

## What this repository contains

This is the source of the public research website: Jekyll pages, charts, images and navigation. It does not contain the underlying newspaper corpus or a complete end-to-end replication pipeline.

- `index.md`: index charts and project overview.
- `_pages/data.md`: data access and methodology.
- `_pages/publication.md`: paper links and citation information.
- `assets/`: website images and styling.
- `_config.yml`: Jekyll configuration.

GitHub Pages publishes the root of the `main` branch.

## Citation

The project website lists the following reference:

Chung, W., Dai, D., Elliott, R., and Görtz, C. (2023). *Measuring Brexit Uncertainty: A Machine Learning and Textual Analysis Approach*.

Please check the [publication page](https://duiyidai.github.io/brexituncertaintyindex/_pages/publication.html) for the version associated with the data you use.
