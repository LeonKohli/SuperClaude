**Purpose**: Dynamic agent orchestration with intelligent spawning

---

@include shared/universal-constants.yml#Universal_Legend

## Command Execution
Execute: immediate. --plan→show plan first
Legend: Generated based on symbols used in command
Purpose: "[Analyze][Task] then [Create&Spawn][CustomAgents] dynamically"

Orchestrate complex tasks by analyzing requirements and dynamically creating purpose-built agents with custom capabilities based on discovered needs. No predefined agent types - each agent is uniquely synthesized.

@include shared/flag-inheritance.yml#Universal_Always

Examples:
- `/orchestrate "Build modern link shortener"` - Analyzes and creates custom agents
- `/orchestrate --max-agents 10 "Fix production memory leak"` - Resource-bounded orchestration
- `/orchestrate --recursive "Design distributed system"` - Allows agent-created sub-agents
- `/orchestrate --ultrathink "Optimize database performance"` - Deep analysis before agent creation

## Core Philosophy

**No Predefined Agents**: Every agent is dynamically created based on:
- Specific task requirements discovered through analysis
- Technical patterns and domains identified
- Exact expertise needed for the problem
- Optimal capability combinations

## Orchestration Phases

Phase 1 - Deep Discovery:
```yaml
Task_Analysis:
  - Decompose requirements into atomic needs
  - Identify technical domains and patterns
  - Detect tools, frameworks, and languages
  - Map component relationships
  - Assess complexity vectors
  - Discover hidden dependencies
```

Phase 2 - Agent Synthesis:
```yaml
Dynamic_Agent_Creation:
  - Generate custom capability profiles
  - Combine specific expertise areas
  - Define precise objectives
  - Allocate knowledge domains
  - Create interaction protocols
  - Design coordination strategies
```

Phase 3 - Adaptive Execution:
```yaml
Orchestration_Strategy:
  - Deploy synthesized agents
  - Monitor progress and adapt
  - Create new agents as needs emerge
  - Coordinate knowledge sharing
  - Integrate results coherently
```

## Dynamic Agent Generation

The orchestrator creates agents with precise capabilities:

```yaml
Agent_Synthesis_Process:
  1. Requirement Analysis:
     "Build link shortener" →
     - Detects: URL processing, storage, analytics, UI/UX
     - Identifies: Rate limiting needs, security concerns
     - Discovers: Scaling requirements, API design
  
  2. Agent Creation:
     Generates:
     - "URL Processing Specialist with Base62 encoding, collision handling, and custom alias validation"
     - "Analytics Architect specializing in click streams, geolocation, and real-time dashboards"
     - "Rate Limiting Engineer with Redis expertise and sliding window algorithms"
     - "Minimalist UI Designer focused on dark mode and micro-interactions"
     
  3. No Templates:
     - Each agent is unique to the task
     - Capabilities precisely match needs
     - No unnecessary generalizations
```

## Capability Synthesis Examples

```yaml
Task: "Fix memory leak in Node.js app"
Generated_Agents:
  - "Memory Forensics Expert specializing in V8 heap snapshots and Chrome DevTools profiling"
  - "Event Loop Detective focused on closure analysis and listener lifecycle management"
  - "Performance Archaeologist for tracing object retention paths and GC behavior"

Task: "Implement OAuth2.0 with MFA"
Generated_Agents:
  - "OAuth2.0 Flow Architect with PKCE, refresh token rotation, and JWT expertise"
  - "MFA Implementation Specialist covering TOTP, WebAuthn, and SMS fallback"
  - "Session Security Engineer for Redis-based storage with sliding expiration"

Task: "Optimize PostgreSQL for time-series"
Generated_Agents:
  - "Time-series Schema Designer with partitioning and BRIN index expertise"
  - "Query Performance Surgeon specializing in window functions and CTEs"
  - "PostgreSQL Internals Expert for vacuum strategy and statistics optimization"
```

## Orchestration Intelligence

Adaptive Agent Creation:
```yaml
Runtime_Discovery:
  - Start with initial analysis agent
  - As discoveries are made, create specialists
  - Each finding can trigger new agent synthesis
  - Agents can request creation of sub-specialists
  
Example_Flow:
  Task: "Modernize legacy Java app"
  1. Initial: Creates "Legacy Code Archaeologist"
  2. Discovers: Spring 2.x, Struts, raw JDBC
  3. Synthesizes:
     - "Spring Migration Strategist from 2.x to Boot 3.x"
     - "Struts to REST API Transformer"
     - "JDBC to JPA Evolution Specialist"
  4. Further discovers: No tests
  5. Creates: "Retroactive Test Engineer for legacy Java"
```

## Advanced Features

Recursive Agent Networks:
```yaml
Hierarchical_Synthesis:
  - Master orchestrator creates primary specialists
  - Each specialist can synthesize sub-agents
  - Sub-agents inherit context and constraints
  - Maximum depth configurable
  
Knowledge_Propagation:
  - Discoveries flow through agent network
  - Capabilities combine and evolve
  - Solutions emerge from collaboration
```

Constraint-Based Generation:
```yaml
Resource_Aware:
  - Budget constraints limit agent complexity
  - Time constraints prioritize capabilities
  - Performance constraints optimize agent count
  
Domain_Specific:
  - Healthcare: HIPAA compliance capabilities
  - Finance: PCI-DSS and SOX expertise
  - Gaming: Real-time performance focus
```

## Usage Patterns

Basic Dynamic Orchestration:
```bash
/orchestrate "Build e-commerce platform"
# Analyzes needs, creates custom agents for:
# - Payment processing with PCI compliance
# - Inventory management with real-time sync
# - Cart persistence with session handling
# - Search with Elasticsearch integration
```

Complex Problem Solving:
```bash
/orchestrate --recursive --ultrathink "
Production API degraded 10x performance
Current stack: Node.js, PostgreSQL, Redis
Symptoms: Slow queries, high CPU, memory growth
"
# Creates investigation specialists, then performance fixers
```

Constrained Orchestration:
```bash
/orchestrate --max-cost 1000 --deadline 48h "
Implement GDPR compliance across microservices
"
# Creates focused agents within constraints
```

Domain-Specific:
```bash
/orchestrate --domain healthcare "
Build FHIR-compliant patient portal
"
# Synthesizes agents with healthcare expertise
```

## Success Patterns

Effective Orchestration:
- Clear problem statements enable better agent synthesis
- Providing technical context improves capability matching
- Constraints help focus agent generation
- Recursive spawning handles discovered complexity

Quality Indicators:
- Agents have specific, focused capabilities
- No overlap in agent responsibilities
- Clear coordination protocols
- Efficient knowledge sharing
- Coherent integrated results

## Best Practices

1. **Detailed Context**: Provide technical stack and constraints
2. **Clear Objectives**: Define what success looks like
3. **Resource Limits**: Set reasonable bounds on agent creation
4. **Progress Monitoring**: Use checkpoints for long tasks
5. **Adaptive Planning**: Let orchestrator adjust as it learns

## Integration

- Inherits all universal flags
- Works with personas for styled agents
- Supports MCP servers for enhanced capabilities
- Maintains shared context across all agents
- Enables caching of successful patterns

@include shared/universal-constants.yml#Standard_Messages_Templates