# Board Game Analytics

Formed in the fall of 2022 by [Randy Nance](https://github.com/randynobx) and others in the Data Science and Full-Stack Web Development tracks at
[Bloom Institute of Technology](https://bloomtech.com), BoardGameAnalytics is a collaborative project to explore and analyize board game 
data from [BoardGameGeek.com](https://boardgamegeek.com/).

## Project Components
### [Backend Stack](https://github.com/boardgameanalytics/bga-backend)
Docker stack composed of:
- REST API for interacting with the database written with FastAPI.
- PostgreSQL Database
- ETL pipeline for extracting board game data from BoardGameGeek.com using the BGGXMLAPI2 and 
loading it into the database.

### [Notebooks](https://github.com/boardgameanalytics/bga-notebooks)
Exploratory python notebooks for visualizations and modeling of the data curated by the pipeline component.

### [Web Dashboard](https://github.com/boardgameanalytics/bga-web-dashboard)
A web dashboard for publication of notebooks and visual exploration of the data.
