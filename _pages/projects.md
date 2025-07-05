---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from:
    - /projects
    - /project
    - /project/
---

## [Receipt Processor](https://github.com/alcatrazxlr8/fetch-backend-appr)

-   Built a RESTful API using Python and FastAPI to process JSON receipt data and compute reward points using
    rule-based logic, with modular design separating routing, validation, and business logic
-   Enforced strict input validation using Pydantic with regex constraints and custom error handling for consistent
    and informative validation responses and reduced invalid request processing by 100%
-   Containerized the application using Docker and designed the service to be stateless, scalable, and easily testable with
    integration tests written in Pytest, increasing test coverage by 60%

## [TaskMaster](https://taskmaster-xlr8.vercel.app/)

-   Conceptualized an open-source web app using React, Firebase Auth, Firestore DB to address the need for a simple,
    secure and scalable task manager
-   Implemented secure authentication and used sub-collections, ensuring users’ tasks persist and remain isolated
-   Enhanced the UI with Bootstrap, enabling intuitive features like creating, reordering, and deleting tasks efficiently
-   Deployed via Vercel, achieving sub-second load times, broad accessibility and laying the groundwork for future expansions

## Fraud Detection Dashboard

-   Designed a schema & developed a suspicious transaction detection and flagging dashboard using SQL Server and Power BI to identify anomalies and fraudulent transactions
-   Optimized data processing and reporting using indexing and views to pre-aggregate frequently used metrics, improving query performance by 20%
-   Implemented percentile-based categorical transaction bucketing, duplicate checking using SQL to enhance anomaly detection and risk analysis

## [Ghosts in the Machine](https://github.com/alcatrazxlr8/Ghosts-In-The-Maze)

-   Created an N x N grid environment with stochastically moving ghosts, randomly spawned walls and our agent.
-   Implemented various search algorithms (DFS, BFS, BDBFS, A-Star etc.) to plan a path for the agent from start to finish while avoiding ghosts and walls and analyzed their performance.
-   Used various heuristics, some standard and some novel.

## [Better, Smarter, Faster](https://github.com/alcatrazxlr8/Better-Smarter-Faster)

-   Simulated a circular graph environment with 3 entities-Agent, Prey, and Predator. The Prey moved probabilistically, while the Agent was optimized to catch it, and the Prey moved greedily toward the Agent.
-   Implemented Markov Chains, designed a custom Neural Network and compared them to optimize the Agent’s decision-making, reducing the time to catch the Prey by 5%

## BuyMe: Auctioning Website

-   Led a team of 3 developers to design and implement a web-based auctioning platform with features like real-time bidding, auto-bidding and bid notifications to improve user engagement.
-   Coordinated full-stack development using MySQL and Java for the back-end, and JSP for a dynamic front-end, achieving a 15% improvement in response times compared to the initial prototype through query optimization and asynchronous updates
-   Delivered the project within a 3-month academic timeline, demonstrating the ability to handle up to 100 concurrent bids for test users

## RU-TCP

-   Implemented a custom TCP kernel module for Linux from scratch, achieving 100% throughput under test conditions
-   Designed & integrated a novel congestion control algorithm variant, improving throughput by 35% over TCP-Reno
-   Managed low-level packet transmission, ACK handling, and window scaling logic in the Linux kernel networking stack
-   Conducted extensive benchmarking & validated <1% packet loss and RTT stability
-   Debugged complex kernel-space issues, reducing crash frequency
