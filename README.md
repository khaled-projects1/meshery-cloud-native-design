# Meshery Cloud-Native Design

A hands-on project where I designed a cloud-native application architecture
using **Meshery Playground** and **Kubernetes** concepts.

## Objective

Practice visualizing and designing a Kubernetes application made of a
frontend, a backend and a PostgreSQL database, and understand how these
resources work together.

## Architecture

| Component  | Role                                      |
|------------|-------------------------------------------|
| Frontend   | User interface, exposed through a Service |
| Backend    | Application logic and API                 |
| PostgreSQL | Database with persistent storage          |

Kubernetes resources used: Namespace, Deployments, Services, Secret,
PersistentVolumeClaim.

## Repository content

- `design/` : design file exported from Meshery (YAML)
- `screenshots/` : screenshots of the design in Meshery Playground
- `README.md` : project documentation

## What I learned

- Designing Kubernetes applications visually with Meshery
- How frontend, backend and database resources connect
- Why storage, namespaces and secrets matter for a database
- Using open-source tools to learn cloud-native concepts

## Badge

Earned the **Design Pioneer** badge from Layer5 for creating my first design.

<div><a href="https://cloud.layer5.io/user/2bdef8f1-6483-4271-b649-518cc91c4049?tab=badges&badge=first-design" alt="First Design" ><img width="175px" height="252px" src="https://badges.layer5.io/assets/badges/first-design/first-design.png" alt="First Design" /></a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sup><a href="https://badges.layer5.io">Get your own badge</a></sup></div>

## Next improvements

- Fix the namespace configuration
- Add persistent storage for PostgreSQL
- Store the database password in a Kubernetes Secret
- Publish the design to the Meshery Catalog

## Author

**Khaled Neji** , Junior Cloud and DevOps
[LinkedIn](https://www.linkedin.com/in/khaled-neji-b00029265/) | [GitHub](https://github.com/khaled-projects1)
