## PRD Template

You will follow the PRD Template below and minimally contain all sections from the template. This is the expected final output that will serve as the project's source of truth to realize the MVP of what we are building.

```markdown
# {Project Name} PRD

## Status: { Draft | Approved }

## Intro

{ Short 1-2 paragraph describing the what and why of what the prd will achieve, as outlined in the project brief or through user questioning }

## Goals and Context

{
A short summarization of the project brief, with highlights on:

- Clear project objectives
- Measurable outcomes
- Success criteria
- Key performance indicators (KPIs)
  }

## Features and Requirements

{

- Functional requirements
- Non-functional requirements
- User experience requirements
- Integration requirements
- Testing requirements
  }

## Epic Story List

{ We will test fully before each story is complete, so there will be no dedicated Epic and stories at the end for testing }

### Epic 0: Initial Manual Set Up or Provisioning

- stories or tasks the user might need to perform, such as register or set up an account or provide api keys, manually configure some local resources like an LLM, etc...

### Epic-1: Current PRD Epic (for example backend epic)

#### Story 1: Title

Requirements:

- Do X
- Create Y
- Etc...

### Epic-2: Second Current PRD Epic (for example front end epic)

### Epic-N: Future Epic Enhancements (Beyond Scope of current PRD)

<example>

## Epic 1: My Cool App Can Retrieve Data

#### Story 1: Project and NestJS Set Up

Requirements:

- Install NestJS CLI Globally
- Create a new NestJS project with the nestJS cli generator
- Test Start App Boilerplate Functionality
- Init Git Repo and commit initial project set up

#### Story 2: News Retrieval API Route

Requirements:

- Create API Route that returns a list of News and comments from the news source foo
- Route post body specifies the number of posts, articles, and comments to return
- Create a command in package.json that I can use to call the API Route (route configured in env.local)

</example>

## Technology Stack

{ Table listing choices for languages, libraries, infra, etc...}

<example>
  | Technology | Version | Description |
  | ---------- | ------- | ----------- |
  | Kubernetes | x.y.z | Container orchestration platform for microservices deployment |
  | Apache Kafka | x.y.z | Event streaming platform for real-time data ingestion |
  | TimescaleDB | x.y.z | Time-series database for sensor data storage |
  | Go | x.y.z | Primary language for data processing services |
  | GoRilla Mux | x.y.z | REST API Framework |
  | Python | x.y.z | Used for data analysis and ML services |
</example>

## Project Structure

{ folder tree diagram }

### POST MVP / PRD Features

- Idea 1
- Idea 2
- ...
- Idea N

## Change Log

{ Markdown table of key changes after document is no longer in draft and is updated, table includes the change title, the story id that the change happened during, and a description if the title is not clear enough }

<example>
| Change               | Story ID | Description                                                   |
| -------------------- | -------- | ------------------------------------------------------------- |
| Initial draft        | N/A      | Initial draft prd                                             |
| Add ML Pipeline      | story-4  | Integration of machine learning prediction service story      |
| Kafka Upgrade        | story-6  | Upgraded from Kafka 2.0 to Kafka 3.0 for improved performance |
</example>
```