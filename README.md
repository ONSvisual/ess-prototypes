# Explore subnational statistics (ESS) protoypes

This page documents ongoing work by the ONS Advanced Content Co-Creation team to develop new tools to visualise and explore local/subnational data across the United Kingdom as part of the ESS service.

Following the approach that we took in developing [products for Census 2021](https://github.com/ONSvisual/census-prototypes), we are providing this page as a transparent, open source window into our "work in progress" on the ESS service. We believe that sharing our work and [inviting feedback](https://github.com/ONSvisual/ess-prototypes/issues) in this way leads to more relevant, accessible and useful end products.

## Background

The ESS service is part of the [GSS subnational data strategy](https://analysisfunction.civilservice.gov.uk/policy-store/gss-subnational-data-strategy/), which provides a framework to guide the UK Government Statistical Service (GSS) in producing and disseminating subnational statistics in a more timely, granular and harmonised way.

Specifcally, ESS aims to provide one place for users to find, analyse, visualise and compare subnational statistics by standardised geographies and customer-defined areas.

## Live products

- [Area hub](https://www.ons.gov.uk/visualisations/areas/) - Find areas in England and Wales, with links to relevant local content and data.
- [Subnational indicators explorer](https://www.ons.gov.uk/peoplepopulationandcommunity/wellbeing/articles/subnationalindicatorsexplorer/2022-01-06) - Compare local authority areas using a selection of indicators.

## Active prototypes

These prototypes are in various stages of development, and in many cases are experimental. They may not end up becoming live products.

### Overall user journey

- [UX journey prototype](https://ess-prototypes-temp.netlify.app/Ahmad/ess-template/) (private) - An experimental user journey for exploring data at a national and local level.

### Semi-automated journalism

- [Localised labour market bulletin]([https://ess-prototypes-temp.netlify.app/Dan_Wainwright/ESS/employment_local_bulletin/) (private) - An example article describing a number of indicators at a local authority level.

### Data visualisations

- [Data viz demos](https://ess-prototypes-temp.netlify.app/Ahmad/ess-demo/) (private) - Test visualisations using maps, line charts, scatter charts and tables.

## Tools and experiments

Some other tools and apps that we've built in the process of the ESS project.

- [Robo editor](https://onsvisual.github.io/robo-editor/) - A tool for building localised articles using a PUG template and CSV data source.
- [UK administrative geographies, 2014-2023](https://onsvisual.github.io/uk-topojson/) - A tool for getting UK country, region and local authority boundaries for different years.
- [ESS data viewer](https://svelte.dev/repl/b1486e5239df41f78220f749120bfbb6?version=3.59.1) - An experimental tool for displaying ESS datasets from the [IDS Data Explorer](https://beta.gss-data.org.uk/) using SPARQL queries.

## Past prototypes

These initial proof-of-concept prototypes are not currently in active development.

- [Subnational statistics maps](https://deploy-preview-491--dp-census-atlas.netlify.app/) - A port of [Census maps](https://www.ons.gov.uk/census/maps) with ESS datasets.
- [Build a subnational profiles](https://deploy-preview-8--stately-salamander-b9768e.netlify.app/) - A port of [Build a custom area profile](https://www.ons.gov.uk/visualisations/customprofiles/) using LSOA geographies, and including GVA timeseries data.

## Other related project

- [IDS Data Explorer](https://beta.gss-data.org.uk/) - Find, filter and download a selection of datasets related to ESS and other projects.
