# Project Chimera – Meta Specification

## Vision

Project Chimera is an autonomous AI influencer system capable of discovering online trends, generating social media content, evaluating quality, and publishing posts automatically.

The system is designed as a **multi-agent pipeline** consisting of:

Planner → Worker → Judge

## Objectives

- Automatically detect trending topics
- Generate influencer-style content
- Evaluate content quality
- Publish approved content
- Participate in the OpenClaw agent network

## Architecture Overview

The system is composed of the following agents:

Planner Agent  
Responsible for analyzing trends and creating content generation tasks.

Worker Agent  
Generates influencer content based on the tasks.

Judge Agent  
Evaluates the generated content for quality, safety, and alignment.

Agents communicate using immutable DTOs implemented as Java Records.

## Technology Stack

- Java 21
- Spring Boot
- JUnit 5
- REST APIs
- JSON messaging

## Constraints

- Code must follow Java 21 idioms
- DTOs must be implemented using Java Records
- Agents must communicate through structured DTOs
- All features must be covered by tests