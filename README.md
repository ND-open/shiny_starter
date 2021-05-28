Shiny app deployment
================

## Objectives

Explore some ways to deploy shiny apps.

## How to use this project

When this project is finished you can test this project using one the
following method :

-   Clone the repository and using docker commands

<!-- -->

    docker build -t shiny_test:v1 .
    docker run --name shiny_test -p 3838:3838 shiny_test:v1

-   \[To do\] Pull the image from docker hub then run it

<!-- -->

    # optionnal step if docker hub is used
    # docker pull <name_of_the_repository>/shiny_test:v1
    docker run --name shiny_test -p 3838:3838 <name_of_the_repository>/shiny_test:v1
