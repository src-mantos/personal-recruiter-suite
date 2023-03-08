# Personal Recruiter

## Software Development Plan

### Primary Goals
- To gather job post data and store it for later review
- Build a React facade around an organically grown micro-service for user review and revision
- To gain some kind of useful insight(s) into the current job market
- To have this be a base around I can start integrating ML

### Overview
Here is `v0.5` design "sketch".  The contents are currently incorrect due to functionality that was changed or not implemented, but conceptually still acurate to help understand the functioning of the systems.
<a href="./Personal Recruiter - planning 0.5.png" style="display:inline-block" target="_blank">
<img src="./Personal Recruiter - planning 0.5.png" width="50%"/>
</a>

### Design Goals:
1) To create a reasonably modular system for the collection of Job Posting Data and being able to extract useful aggregate data out of it.
2) To not take on any individual piece of functionality that couldn't be completed in a week iteration

### Considerations & Assumptions
- 

## Framing Agile Task Breakdown

- *[global]* Setup a consolidated development environment
- *[data service]* Basic project setup with a test case driver
  - *[data service]* Define primary Data Transport Objects and scaffold the orchestration layer
    - *[POC]* Implement the first scrape-able data source
    - *[impl]* Implement the remaining data sources with "lessons learned"
  - *[impl]* Implement a Data Access Layer
  - *[data service]* Define OpenAPI specification
    - *[setup]* Generate API scaffolding
    - *[impl]* Implement custom endpoints
- *[database]* Stand up & document deployment procedures + data retention strategy
- *[web service]* Basic project setup
  - *[impl]* Build out basic ReactJS UI components
  - *[impl]* Implement a Data Access Layer, (application config as minimum)
  - *[impl]* Circuit break & Proxy to data service
  - *[impl]* Basic test case coverage
- *[global]* Setup a consolidated deployment environment