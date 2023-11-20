# BrightSocial Test Development Flow

## Introduction
This is the document for a Test Development Flow, which includes Behavior-Driven Development (BDD), Acceptance Test-Driven Development (ATDD) and Test-Driven Development (TDD).

I will show the basic flow of the development process. After that is going to be the ste-by-step of each phase in the whole process.

## The flow of development process


```mermaid
flowchart TD
    A["`Gather requirements
    (ATDD)`"]
    B["`Write user stories with User Stories Test
    (BDD)`"]
    C["`Create Acceptance Test
    (ATDD)`"]
    D["`Develop with Unit Test
    (TDD)`"]
    E["`Confirm with User Stories Test & Acceptance Test
    (BDD & ATDD)`"]
    A --> B
    A --> C
    B --> D    
    C --> D
    D --> E

    style A stroke:yellow
    style B stroke:cyan
    style C stroke:yellow
    style D stroke:magenta
    style E stroke:#80ED80
```

The graph above is the development flow which involves all 3 of the Test Developments.

##### ATDD (Acceptance Test-Driven Development)

