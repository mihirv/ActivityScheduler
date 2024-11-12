**Activity Scheduler** is a flexible, programmable scheduling system designed to schedule activities on potentially constrained and dependent resources to maximize outcomes. This system is ideal for scenarios where activities need to be scheduled across multiple resources with varying constraints, dependencies, and optimization requirements.

## Features

### Functional Requirements

#### **Activity**
- Activities can be scheduled on multiple resources within a domain.
- Supports dependencies between activities based on shared resources.
  
#### **Resources**
- Capable of handling 1 to N resources.
- Resources can be grouped together for configuration purposes.
- Programmable constraints and dependencies between resources.
- Resources can be utilized up to X% capacity (where X > 0).

#### **Outcome**
- Optionally optimize scheduling for maximized outcomes.
- Programmatic optimization functions can be added to fine-tune results.

### Non-functional Requirements
- Consistency and reliability for event creation.
- High availability for continuous operation.
