# Personal Recruiter Suite
A consolidated workspace and "runnable" environment for the suite of infrastructure to interact with job post data.

### Related Reading
- [Process Doc's](./docs/process_doc.md)
- [Developer Info](./docs/dev_info.md)


## Getting Started
Docker & [Docker](https://docs.docker.com/compose/) Compose is required to run, at minimum the database, if not the full suite.

### Quick Commands
- Full Suite [\*limited](./docs/dev_info.md#docker-runtime-restriction)
    - `docker-compose -f devFull.yml up`
- Data Interface
    - `docker-compose -f dataOnly.yml up`

### Quick Links
- [Personal Recurter UI:8080](http://localhost:8080)
- [Personal Recurter API:3000/v1/docs](http://localhost:3000/v1/docs/)
- [Mongo Express:8081](http://localhost:8081/)
