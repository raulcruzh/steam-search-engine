# Steam Game Search Engine

Information Retrieval university project.

## Project goal

The goal of this project is to build a video game search engine using data
crawled from the English Steam Store and later enriched with data from the
English Wikipedia dump.

The search engine should allow users to find games using information such as:

- title
- developer
- publisher
- tags
- features
- descriptions
- gameplay characteristics
- setting
- story

## Data sources

- Steam Store
- English Wikipedia

## Project stages

1. Web crawling
2. Data extraction
3. Custom indexing and ranking
4. Distributed processing with Apache Spark
5. Steam-Wikipedia data integration
6. PyLucene indexing and search
7. Evaluation

## Environment

The project is developed using Docker and Docker Compose.

Main environment:

- Python 3.12
- Java 17
- Linux container

## Repository structure

- `crawler/` - Steam crawling
- `extraction/` - data extraction
- `indexing/` - custom index and ranking
- `search/` - search interface
- `spark/` - distributed processing
- `lucene/` - PyLucene implementation
- `evaluation/` - evaluation scripts and queries
- `tests/` - tests
- `scripts/` - utility scripts
- `stats/` - project statistics
- `docs/` - documentation and diagrams
- `data/` - local datasets and generated indexes