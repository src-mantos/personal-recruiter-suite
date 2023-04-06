# Personal Recruiter End of Life

As with any long running, organically grown, technical project, there are many ways to improve and refine through iteration, but to make components more independently successful, refactoring would be the more cost effective strategy. 

### Recommendations

- **Data Modeling**: More post data could be captured for redundancy and accuracy of any interpolation done by the system. There would also be a desire to synergise with the style of our data access layer.
- **Collecting Data & Concurrency**: This kind of scraper can be useful in routine automation, but the current implementation is too entangled to be useful in any other context.
- **User Experience**: While a standard react user interface is fun to experiment in, there is no reason not to have focused and deticated "Data Ingest" interface as well as a more direct query-able interface.