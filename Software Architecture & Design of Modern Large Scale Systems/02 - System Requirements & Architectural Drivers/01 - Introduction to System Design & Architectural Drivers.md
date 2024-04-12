# Introduction to System Design & Architectural Drivers

## Importance of System Requirements

- **Definition:** System requirements are the specifications of what needs to be built for the client.
- **Differences from Small-Scale Projects:**
  - **Scope and Abstraction:** Larger scope and higher level of abstraction compared to implementing a method or class.
  - **Ambiguity:** Requirements may come from non-technical sources and can be vague, requiring clarification and technical translation.

## Challenges in Gathering Requirements

- **Scope:** Designing a large-scale system like a file storage system, video streaming solution, or ride-sharing service can be overwhelming.
- **Ambiguity:** Clients may not provide detailed technical requirements, leaving it up to engineers to ask the right questions.

## Risks of Inaccurate Requirements

- Large-scale systems are complex and costly to build, involving multiple engineering teams and significant time and resources.
- Changes are difficult to make once development is underway.
- Failure to deliver on time can harm the company's reputation and financial stability.

## Classifying Requirements

1. **Functional Requirements (Features):**
   - Describe what the system does (e.g., displaying nearby drivers on a map, charging a rider's credit card).
   - Do not dictate the architecture but define the system's behavior.
2. **Non-Functional Requirements (Quality Attributes):**
   - Describe properties the system must have (e.g., scalability, availability, reliability).
   - Dictate the software architecture and are critical for defining system quality.
3. **System Constraints:**
   - Limitations such as deadlines, budget, or available resources.
   - Influence architectural decisions and may require trade-offs.

## Architectural Drivers

- The combination of features, quality attributes, and system constraints drive architectural decisions, narrowing down the vast possibilities to a solution that meets the client's needs.

---

In this lecture, the importance of accurately gathering and classifying system requirements was emphasized, highlighting the role of functional requirements, non-functional requirements, and system constraints in driving architectural decisions for large-scale systems.
