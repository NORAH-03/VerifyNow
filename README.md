# VerifyNow

## About the Project

**VerifyNow** is a software engineering project that proposes a web-based system for helping users verify information and identify potentially misleading or untrustworthy content.

The system is designed to accept different types of content, including **links, text, and images**, and analyze the submitted information using AI and external verification sources. The goal is to provide users with a clear verification result, a confidence level, a warning when information may be misleading, and a brief explanation of how the result was determined.

## Key Features

* Submit links, text, or images for verification
* Display the confidence level of verification results
* Warn users when information may be misleading or untrustworthy
* Provide a brief explanation of the verification result
* Allow users to report incorrect results
* Compare information with trusted external sources
* Support fact-checking and web search services
* Allow users to view and download verified documents

## System Overview

VerifyNow interacts with several external services to support the verification process. These include:

* **Social Media Platforms** — to retrieve source IDs and post context
* **Search Engines** — to perform reverse searches and retrieve relevant metadata
* **Fact-Check APIs** — to validate information and obtain matching results

The system then generates a verification report to help users determine whether submitted content is trustworthy or potentially misleading.

## System Design

The project includes several software engineering models and diagrams:

* Software Requirements Specification (SRS)
* Use Case Diagram
* High-Level Class Diagram
* Sequence Diagram
* System workflow and requirements
* Test Cases
* Development schedule and risk analysis

The use case model describes interactions between the Information Seeker, VerifyNow, and external supporting services.

## Development Approach

VerifyNow follows a **Plan-Driven Development Model** with a structured lifecycle consisting of:

1. Requirements
2. Design
3. Development
4. Testing
5. Deployment

The project was planned across a 32-week lifecycle with defined milestones and dependencies.

## Testing

The project defined test cases for different verification scenarios, including:

* **Reliable Information Verification** — reliable content should produce a “Verified” result.
* **Misleading Information Detection** — misleading content should produce a “Not Verified” warning.

## Project Status

The project completed its **SRS and UML modeling**, along with the definition of the system workflow and requirements.

Full system implementation and integration were identified as remaining work.

## Future Enhancements

Future improvements identified for VerifyNow include:

* Improve verification accuracy
* Support additional trusted sources
* Develop a mobile application
* Enhance the user interface and user experience (UI/UX)

## Project Type

**Course Project — Software Engineering**

## Documentation

The repository contains the project's final report and presentation, including the requirements, system models, testing, planning, and project documentation.

---

**VerifyNow — Making information easier to verify.**
