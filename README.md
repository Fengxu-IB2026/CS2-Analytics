# CS2 Professional Match Analytics

An independent data analytics project exploring player performance, team dynamics, and competitive outcomes in professional Counter-Strike 2.

## Project Overview

This project investigates how individual player performance contributes to overall team performance in professional CS2 matches.

Rather than relying solely on conventional player statistics, the project aims to develop team-level statistical measures that describe performance distribution, consistency, and dependence on individual players.

The project combines **Python-based data processing, relational data management, SQL analysis, and statistical exploration** to build a structured foundation for investigating these questions.

## Research Objectives

The project focuses on three main questions:

1. **Performance Distribution:** How unevenly is individual performance distributed among players within the same team?
2. **Individual Dependence:** To what extent does a team rely on its highest-performing players?
3. **Competitive Outcomes:** Are highly skewed performance distributions associated with differences in team success or long-term competitive consistency?

These are research questions under investigation, rather than established conclusions.

## Dataset

The dataset consists of professional Counter-Strike 2 player statistics collected from **HLTV**, with an initial focus on **Team Vitality and FURIA**.

The project includes approximately **3,000 player-level records** across hundreds of competitive maps.

Key variables include:

- Match, tournament, team, opponent, player, and map identifiers
- Terrorist-side (T) and Counter-Terrorist-side (CT) performance
- Player Rating
- Average Damage per Round (ADR)
- Performance Swing

Player statistics are organized by team, map, and side to support comparative analysis.

**Data source:** [HLTV](https://www.hltv.org/)

## Data Processing Pipeline

A Python-based data pipeline was developed to transform collected match statistics into structured datasets suitable for analysis.

The workflow includes:

1. Importing and organizing collected player statistics.
2. Cleaning and standardizing data fields.
3. Validating records and handling identified data inconsistencies.
4. Integrating relevant match metadata.
5. Preparing structured outputs for further analysis and database integration.

The pipeline has undergone multiple revisions, with its development history tracked through Git.

## Database and Analysis

Processed datasets are used in **MySQL** for structured querying and statistical exploration.

Current analytical directions include:

- Comparing player performance within individual teams and maps.
- Measuring differences between top performers and team averages or medians.
- Investigating performance variation across T and CT sides.
- Exploring relationships between team-level performance distributions and competitive outcomes.

Additional statistical analysis and validation are ongoing.

## Technologies

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Database | MySQL |
| Data Analysis | SQL, Python |
| Visualization | Matplotlib |
| Development | Jupyter Notebook |
| Version Control | Git, GitHub |

## Version Control and Reproducibility

Git is used to track the development of the data processing pipeline and changes to the master dataset.

Historical dataset snapshots are maintained through successive commits to the same tracked CSV file, allowing earlier data states to be inspected and compared.

This approach supports traceability and provides a record of how the project has evolved.

## Current Status

**Work completed or established:**

- Developed and revised a Python data processing pipeline.
- Organized professional CS2 statistics into structured datasets.
- Established a MySQL database for analytical queries.
- Began exploring team-level performance metrics.
- Introduced Git-based version control for the pipeline and master dataset.

**Ongoing work:**

- Refining measures of within-team performance distribution.
- Investigating possible relationships with competitive outcomes.
- Improving analytical validation and interpretation.
- Expanding project documentation and presentation of results.

## Limitations

- The dataset currently focuses on a limited selection of professional teams.
- Historical player statistics may be affected by changes in source definitions or rating methodologies.
- Observed statistical relationships should not be interpreted as causal without further investigation.
- Additional validation is required before drawing broader conclusions.

## Data Attribution

Professional match and player statistics were collected from [HLTV.org](https://www.hltv.org/).

This is an independent educational and analytical project and is not affiliated with or endorsed by HLTV.
