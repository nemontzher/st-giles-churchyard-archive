# St. Giles Churchyard Digital Archive Project

## Project Purpose

This repository serves as a structured digital archive documenting the individuals buried in the historic St. Giles Churchyard. The project aims to preserve the memory of those interred there, capturing not only their names and dates but also the stories, epitaphs, and familial connections that reflect the community's history.

## Project Structure

The archive is organized using professional project management workflows on GitHub:

- **Issues**: Research tasks broken down by family plot or churchyard section
- **Branches**: Feature branches for isolated research and data entry
- **Pull Requests**: Formal proposals to merge findings into the master archive
- **Master Database**: A single `burial_register.csv` file containing all structured data
- **Analysis Files**: Markdown reports summarizing findings and insights

## Historical Context

St. Giles Churchyard is a historic burial ground with graves dating back several centuries. The churchyard contains unique architectural features, notable family monuments, and epitaphs that offer insights into local history, social structures, and commemorative practices.

## How to Use This Archive

1. Browse the `burial_register.csv` file for structured data on individuals
2. Review research issues to see ongoing and completed investigation tasks
3. Examine pull requests for detailed historical narratives and source references
4. Check the `community_summary.md` for analytical insights and summaries

## Contribution Workflow

This project follows a strict GitHub workflow:

1. Create an Issue for each research task
2. Create a feature branch from `main`
3. Conduct research and update the CSV file on the branch
4. Open a Pull Request with detailed historical findings
5. Merge after review to integrate data into the master archive

## Data Standards

The master database (`burial_register.csv`) uses the following columns:

- `RecordID`: Unique identifier for each burial record
- `LastName`: Family surname
- `FirstName`: Individual's first name(s)
- `BirthYear`: Year of birth (when known)
- `DeathYear`: Year of death
- `Epitaph`: Transcription of headstone inscription
- `FamilyPlot`: Name or identifier of the family plot/section
- `Notes`: Additional historical context, sources, or observations

## License

This archival data is made available for historical and educational purposes. Please respect the memory of those documented and cite appropriately when using this data.