# Architectural Decision Record (ADR): Usage of C4 Modelling

## Context

### Problem Statement
The current approach to system design documentation lacks a standardized and clear method for representing software architecture. This leads to inconsistencies, misunderstandings, and communication barriers among development teams and stakeholders. A standardized modelling approach is needed to improve clarity, consistency, and communication across projects.

### Background
In this industry, software systems are complex and require precise and clear documentation to ensure all stakeholders have a shared understanding of the architecture. Our recent adoption of Domain Driven Design (ADR 4), Hexagonal Architecture (ADR 5), and a Container-First Approach (ADR 14) necessitates a modelling approach that can clearly represent these architectures.

## Decision

### Summary
We will adopt C4 Modelling as our standard approach for representing software architecture. C4 Modelling provides a clear, hierarchical way of describing software architecture, making it easier to communicate and understand the system's structure and design.

### Scope
This decision applies to all new development projects and will be progressively applied to existing systems through refactoring efforts where feasible.

## Decision Drivers
1. **Clarity**: Provides a clear and concise way to represent software architecture at different levels of abstraction.
2. **Consistency**: Ensures a standardized approach across all projects, reducing misunderstandings.
3. **Communication**: Enhances communication among developers, architects, and non-technical stakeholders.
4. **Alignment with ADRs**: Complements our existing architectural decisions, such as DDD and Hexagonal Architecture.
5. **Support for Complex Systems**: Capable of modelling the complexity inherent in banking systems.

## Considered Options
1. **C4 Modelling**: A hierarchical approach to software architecture modelling with distinct levels of abstraction.
2. **UML (Unified Modelling Language)**: A standardized modelling language offering various diagram types.
3. **Custom Diagrams**: Ad hoc diagrams created as needed without a standardized approach.

## Benefits
1. **Clear Hierarchical Representation**: Breaks down the architecture into Context, Container, Component, and Code diagrams, providing different levels of detail.
2. **Improved Communication**: Simplifies communication among all stakeholders, ensuring everyone has a clear understanding of the system.
3. **Consistency Across Projects**: Establishes a standard method for documenting architecture, leading to consistent and high-quality documentation.
4. **Alignment with DDD and Hexagonal Architecture**: Facilitates the representation of domain models and architectural layers effectively.
5. **Enhanced Collaboration**: Promotes better collaboration between development teams and other stakeholders by providing a common visual language.

## Drawbacks
1. **Learning Curve**: Requires training and adjustment time for teams to learn and adopt the C4 Modelling approach.
2. **Initial Effort**: Requires an initial investment of time to create comprehensive C4 diagrams for existing systems.

## Architecture Details

### Design Principles
- **Clarity**: Ensures that all architectural diagrams are clear and easy to understand.
- **Consistency**: Maintains a consistent approach to documenting architecture across all projects.
- **Modularity**: Supports modular design by clearly representing different components and their interactions.
- **Communication**: Enhances communication through a common visual language for all stakeholders.

### Implementation Strategy
- **Standardized Guidelines**: Develop and document guidelines for creating and maintaining C4 models, including best practices for each level of abstraction.
- **Training**: Provide training sessions and resources for development teams to get up to speed with C4 Modelling.
- **Tooling**: Utilize tools that support C4 Modelling, such as Structurizr or draw.io, to facilitate diagram creation and management.
- **Incremental Adoption**: Start with new projects and progressively create C4 models for existing systems.

### Integration Considerations
- **Legacy Systems**: Plan and execute the integration of C4 models with existing documentation practices during refactoring.
- **Continuous Improvement**: Regularly review and update C4 diagrams to ensure they accurately reflect the current state of the architecture.
- **Alignment with ADRs**: Ensure that C4 models align with the principles and practices outlined in our other ADRs, such as DDD and Hexagonal Architecture.

### Implementation Plan
1. **Phase 1: Assessment and Planning**: Assess current documentation practices and develop a detailed plan for C4 Modelling adoption.
2. **Phase 2: Training and Tooling Setup**: Provide training and set up necessary tooling to support C4 Modelling.
3. **Phase 3: Incremental Adoption**: Begin using C4 Modelling in new projects and incrementally create models for existing systems.
4. **Phase 4: Continuous Improvement**: Regularly review and refine C4 diagrams based on feedback and evolving project needs.

## Alternatives Considered
1. **UML (Unified Modelling Language)**: Considered but not chosen due to its complexity and the potential for over-complication in representing software architecture.
2. **Custom Diagrams**: Rejected due to the lack of standardization, which leads to inconsistent and unclear documentation.

## Decision Outcome

### Expected Results
- **Clarity**: Achieve clear and understandable architectural documentation.
- **Consistency**: Establish a consistent approach to software architecture modelling.
- **Communication**: Improve communication and collaboration among all stakeholders.
- **Alignment with ADRs**: Ensure that C4 models complement our existing architectural practices.

### Review and Evaluation
The decision will be reviewed six months after implementation to assess its effectiveness and make necessary adjustments based on feedback and performance metrics.

## Review Date
The decision will be reviewed six months after implementation to evaluate its effectiveness and make necessary adjustments.

## Stakeholders
- **Solution Architects**: Define the overall strategy and ensure adherence to design principles.
- **Development Teams**: Implement C4 Modelling and follow new documentation practices.
- **QA Teams**: Ensure the documentation accurately reflects the architecture.
- **Project Managers**: Support the transition and ensure teams adhere to the new standards.
- **Management**: Provide strategic support and resources for training and implementation.

## Approved By
- **Chief Technology Officer**
- **Head of Solution Architecture**
- **Head of Software Development**
- **Head of IT Operations**

## Document History
- **Date**: February 11th, 2025
- **Version**: 1.0
- **Authors**: [Author Name, Role]
