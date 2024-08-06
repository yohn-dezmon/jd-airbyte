# Overview

- open source data integration platform designed for consolidating data from many sources

Airbyte Cloud:

- hosted solution
- infrastructure is managed by Airbyte

Self Managed Airbyte:

- can be deployed locally or via infrastructure you've set up
- for enterprise, requires a license key
- community is free and can be deployed locally

airbyte does basic scheduling.  
airbyte typically isn't used for transformations, you just load the data into your data warehouse, then use dbt/spark for transformations.
