# Orchestrate Command Examples

## Example 1: Simple Web App Development

```bash
/orchestrate "Build a todo list web app with user authentication"
```

**Master Agent Analysis:**
```
Task Analysis Complete:
- Type: Full-stack web application
- Components: Frontend, Backend, Database, Auth
- Complexity: Medium
- Security Requirements: High (user data)
- Testing Requirements: High

Spawning Agent Team:
1. Architect Agent - System design and structure
2. Security Agent - Authentication implementation  
3. Frontend Builder - React UI components
4. Backend Builder - API and business logic
5. Database Expert - Schema and optimization
6. Test Engineer - Unit and integration tests
```

## Example 2: Performance Crisis

```bash
/orchestrate --ultrathink --max-agents 8 "
Production API response times degraded 10x in last hour.
Find and fix the issue with minimal downtime.
"
```

**Dynamic Response:**
```
URGENT: Performance Crisis Detected
Phase 1 - Immediate Triage (Parallel):
- Spawn: Performance Profiler (analyzing metrics)
- Spawn: Log Analyzer (checking error patterns)
- Spawn: Database Expert (query analysis)
- Spawn: Infrastructure Monitor (resource check)

Phase 2 - Root Cause Found: Database locks
- Spawn: DBA Specialist (immediate fix)
- Spawn: Optimizer (query rewrite)

Phase 3 - Prevention:
- Spawn: Monitoring Expert (alerts setup)
- Spawn: Documenter (incident report)
```

## Example 3: Legacy Code Refactoring

```bash
/orchestrate --recursive --phased "
Refactor 10-year-old Java monolith:
- Preserve all functionality
- Improve maintainability
- Add comprehensive tests
- Modernize patterns
"
```

**Orchestration Plan:**
```yaml
Phase 1 - Analysis (2 agents):
  Lead: Architecture Analyst
    ├── Spawns: Code Archaeologist (understand legacy patterns)
    └── Spawns: Dependency Mapper (chart connections)

Phase 2 - Planning (4 agents):
  Lead: Refactoring Strategist
    ├── Spawns: Risk Assessor
    ├── Spawns: Test Planner
    └── Spawns: Migration Expert

Phase 3 - Execution (6-10 agents dynamically):
  Lead: Refactoring Coordinator
    ├── Module Teams (spawned per component):
    │   ├── Refactoring Expert
    │   ├── Test Builder
    │   └── Quality Reviewer
    └── Integration Team:
        ├── System Integrator
        └── Regression Tester
```

## Example 4: Security Audit

```bash
/orchestrate --collaborative "
Comprehensive security audit of e-commerce platform:
- Check OWASP Top 10
- Review authentication
- Analyze data handling
- Test API endpoints
- Verify compliance
"
```

**Specialized Team Spawn:**
```
Security Orchestration Initialized:

Core Team (Parallel Execution):
1. OWASP Specialist - Top 10 vulnerability scan
2. Auth Expert - Authentication/authorization audit
3. Crypto Analyst - Encryption and key management
4. API Tester - Endpoint security testing
5. Compliance Officer - GDPR/PCI compliance check

Conditional Spawns:
- IF: Vulnerabilities found > 5
  THEN: Spawn Penetration Tester
- IF: Crypto issues detected
  THEN: Spawn Cryptography Expert
- IF: Compliance gaps found
  THEN: Spawn Legal Advisor
```

## Example 5: Machine Learning Pipeline

```bash
/orchestrate --adaptive "
Build production ML pipeline for customer churn prediction:
- Research approaches
- Design architecture  
- Implement pipeline
- Add monitoring
- Create documentation
"
```

**Adaptive Orchestration:**
```
Initial Analysis → Dynamic Team Building:

Research Phase:
- Spawn: ML Researcher (algorithm selection)
- Spawn: Data Scientist (feature engineering)
→ Discovers: Need for real-time processing

Adaptive Response:
- Spawn: Streaming Expert (Kafka/Spark setup)
- Spawn: Infrastructure Architect (scaling design)

Implementation Phase:
- Original: ML Engineer (model implementation)
- Added: DevOps Expert (pipeline automation)
- Added: Monitor Designer (ML metrics)

Testing Phase:
- Spawn: ML Tester (model validation)
- Spawn: Performance Tester (latency checks)
→ Discovers: Data drift issues

Final Adaptation:
- Spawn: Drift Detection Expert
- Spawn: Retraining Strategist
```

## Example 6: Microservices Migration

```bash
/orchestrate --recursive --budget-aware "
Migrate monolithic e-commerce to microservices:
- Minimize downtime
- Preserve all features
- Improve scalability
- Stay within $50k budget
"
```

**Budget-Aware Orchestration:**
```
Resource-Optimized Plan:

Tier 1 Agents (Essential - 40% budget):
- Migration Architect (strategy)
- Service Designer (boundaries)
- Data Architect (database split)

Tier 2 Agents (Important - 35% budget):
- API Designer (contracts)
- Testing Lead (strategy only)
- DevOps Engineer (CI/CD)

Tier 3 Agents (As budget allows - 25%):
- Performance Optimizer
- Documentation Specialist
- Security Reviewer

Recursive Spawning Rules:
- Each Tier 1 agent can spawn 1 helper
- Tier 2 agents share 2 helpers total
- Tier 3 works independently
```

## Usage Patterns

### Basic Orchestration
```bash
/orchestrate "task description"
```

### With Constraints
```bash
/orchestrate --max-agents 5 --timeout 30m "task"
```

### Phased Execution
```bash
/orchestrate --phased "complex multi-stage task"
```

### Recursive Spawning
```bash
/orchestrate --recursive --max-depth 3 "hierarchical task"
```

### Collaborative Mode
```bash
/orchestrate --collaborative --ultrathink "complex problem"
```

### Budget-Aware
```bash
/orchestrate --budget-aware --max-cost 1000 "resource-constrained task"
```