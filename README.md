# Memoire-MLAEXPERIMENT
# MLA oTree Experiment

This repository contains the oTree source code used for the experiment reported in the Master 2 thesis:

**“Why Do Investors Adopt Myopic Behavior Even When They Report a Long-Term Orientation? The Role of Feedback Frequency and the Salience of Losses.”**

The experiment uses a 2 × 2 between-subject design crossing:

- feedback frequency: aggregated vs. frequent;
- loss salience: absent vs. present.

Participants complete the CFC-14 questionnaire and then make 20 sequential investment decisions in a fictitious risky-asset task.

The repository contains the oTree implementation used for the experiment, including:

- participant consent and instructions;
- CFC-14 questionnaire;
- treatment assignment;
- investment decision pages;
- frequent and aggregated feedback;
- perceptual-salience display;
- economic-salience payoff structure;
- transition between the two salience blocks;
- final results page;
- CSS styling used in the participant interface.

## Main files

- `settings.py` — oTree project and session configuration;
- `requirements.txt` — Python dependencies;
- `mla_experiment/__init__.py` — main experimental logic;
- `mla_experiment/*.html` — participant-facing pages;
- `static/mla_experiment/style.css` — interface styling.

## Data

No participant-level data are included in this repository.

The repository contains only the experimental implementation used to generate the data analysed in the thesis.
