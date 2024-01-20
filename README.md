# zoomcamp-2024-data-engineer
Repository to work on tasks and homework of the Data engineer Zoomcamp 2024 https://github.com/DataTalksClub.

Question 1. 

By running `Docker run --help` which tag has the following text? - Automatically remove the container when it exits.

Command:
```
    -> docker run --help | grep -i  "automatically"
```

Solution: `--rm`

Question 2. 

Checking package wheel version in docker image python:3.9

Command:
```
    -> docker run -it --entrypoint=/bin/bash python:3.9 -c "pip list"
```

Solution: `0.42.0`