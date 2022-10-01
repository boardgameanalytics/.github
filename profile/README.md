# Board Game Analytics

Formed in the fall of 2022 by learners in the Data Science and Full-Stack Web Development tracks at [Bloom Institute of Technology](https://bloomtech.com), BoardGameAnalytics is a collaborative project to explore and analyize board game data from [BoardGameGeek.com](https://boardgamegeek.com/).

## Contributing Members
- [Randy Nance](https://github.com/randynobx) - *Project Lead/Data Engineer*
- [Chris Burrows](https://github.com/cbradiodrums) - *Data Scientist*
- [Nikolay Glushetskiy](https://github.com/nikolayglushetskiy) - *Data Scientist*
- [Jason Decker](https://github.com/jdecker117) - *Full-Stack Web Developer*
- [Greg Somers](https://github.com/somersgreg) - *Data Scientist*

## Project Components
### [Pipeline](https://github.com/boardgameanalytics/bga-pipeline)
Airflow orchestrated ETL pipeline for extracting board game data from BoardGameGeek.com using the BGAXMLAPI2 and 
loading it into a Postgres database.

### [Notebooks](https://github.com/boardgameanalytics/bga-notebooks)
Exploratory python notebooks for visualizations and modeling of the data curated by the pipeline component.

### [Web Dashboard](https://github.com/boardgameanalytics/bga-web-dashboard)
A web dashboard for publication of notebooks and visual exploration of the data.
