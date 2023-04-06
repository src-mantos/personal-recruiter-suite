
# Requirements
| lib.   | ver. |
|--------|-------------------|
|Node.js | v16.13.0 or later |
|Yarn    | v16.13.0 or later |
|Docker  | 20.10.22 or later |
|        | *mongo:4.4.6* |
|        | *mongo-express:latest* |
|        |*mcr.microsoft.com/playwright:v1.18.0-focal*|
|        | *node:16-alpine* |
## Pull the Suite
[GIT Submodule Reference](https://git-scm.com/book/en/v2/Git-Tools-Submodules). To pull down all submodules in the initial clone.
```
$ git clone --recurse-submodules https://github.com/src-mantos/personal-recruiter-suite.git
```
If we forget the clone flag 
```
$ git submodule init
$ git submodule update
```

### Adding Submodules

```
$ git submodule add <repo>
$ git diff --cached --submodule
```

# Docker Runtime Restriction
due to certain configuration choices, the scrape process requires an X Server to be accessable and is unfortuantely not cost effective to resolve for this initial effort

# References
- [docker command line example](https://docs.docker.com/engine/reference/commandline/create/#examples)
