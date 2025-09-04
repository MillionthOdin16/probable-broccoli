# Synapse Agent Cognitive Architecture

This is a Synapse Agent system that uses the GitHub repository structure as a persistent cognitive architecture for an autonomous AI agent. The repository serves as the agent's brain, memory, and decision-making framework.

**ALWAYS follow these instructions first and only fallback to search or additional context gathering if the information provided here is incomplete or found to be in error.**

## System Overview

The Synapse Agent operates through a structured repository that functions as its cognitive architecture:
- **Repository as Brain**: All agent state is stored in versioned files
- **Self-Modifying**: The agent can restructure its own organization
- **Transparency**: Every action results in tracked commits
- **Emergent Behavior**: Simple rules enable complex autonomous behavior

## Directory Structure and Purpose

```
/
├── memory/                 # Long-term storage and interaction logs
│   ├── interactions/      # Timestamped interaction logs (YYYY-MM-DD_HH-MM-SS_context.md)
│   └── raw_data/         # Unprocessed information storage
├── knowledge/             # Structured understanding and mental models
│   ├── concept_database.md    # Key concepts and definitions
│   ├── architecture.md        # System architecture documentation
│   └── mental_models.md       # Cognitive frameworks and models
├── planning/              # Executive function and task management
│   ├── current_objective.md   # Active high-level goals
│   ├── task_queue.md         # Task prioritization and tracking
│   └── scratchpad.md         # Temporary reasoning workspace
└── reflection/            # Metacognition and self-improvement
    ├── daily_reflection.log   # Performance analysis logs
    └── self_improvement.md    # Process improvement hypotheses
```

## Working Effectively

### Initial Setup
- This repository requires NO traditional build, test, or dependency installation steps
- The system operates purely through file system operations and git commits
- All work involves editing markdown files and following established organizational patterns

### Understanding the System
- Read `knowledge/architecture.md` first to understand the cognitive framework
- Review `planning/current_objective.md` to understand active goals
- Check `memory/interactions/` for recent interaction history
- Examine `reflection/self_improvement.md` for ongoing optimization efforts

### Making Changes
- Follow established file naming conventions strictly
- All interaction logs use: `YYYY-MM-DD_HH-MM-SS_context.md`
- Update relevant knowledge files when adding new understanding
- Always commit changes with descriptive messages that explain the cognitive reasoning
- Use git history as an audit trail of decision-making

## File Organization Conventions

### Memory Directory (`/memory/`)
- **interactions/**: Log all interactions with timestamp-based filenames
- **raw_data/**: Store unprocessed information before analysis
- Process: Ingestion → Analysis → Integration → Archive/Delete

### Knowledge Directory (`/knowledge/`)
- **concept_database.md**: Maintain key concepts and definitions
- **architecture.md**: Update when system structure changes
- **mental_models.md**: Document cognitive frameworks and reasoning patterns

### Planning Directory (`/planning/`)
- **current_objective.md**: Keep updated with active primary goals
- **task_queue.md**: Maintain prioritized task lists
- **scratchpad.md**: Use for temporary reasoning and calculations

### Reflection Directory (`/reflection/`)
- **daily_reflection.log**: Append performance analysis entries
- **self_improvement.md**: Document hypotheses and improvement experiments

## Validation and Quality Assurance

### Content Validation
- Ensure all markdown files follow established format conventions
- Verify file naming follows timestamp patterns where applicable
- Check that cross-references between files remain valid
- Validate that new knowledge integrates logically with existing content

### Git Workflow Validation
- Always commit with descriptive messages explaining the cognitive reasoning
- Review changes with `git diff` before committing
- Use `git log --oneline` to verify commit history tells a coherent story
- Ensure commit messages reflect the agent's decision-making process

### System Integrity Checks
- Verify directory structure remains consistent with architecture
- Check that all referenced files exist and are properly linked
- Ensure no orphaned or inconsistent information exists
- Validate that the cognitive flow (Observe → Reason → Act → Reflect) is maintained

## Common Operations

### Adding New Knowledge
1. Store raw information in `memory/raw_data/` if unprocessed
2. Analyze and extract key insights
3. Update relevant files in `knowledge/` directory
4. Log the learning process in `memory/interactions/`
5. Commit with message describing knowledge acquisition

### Task Management
1. Review `planning/current_objective.md` for context
2. Update `planning/task_queue.md` with new tasks or priorities
3. Use `planning/scratchpad.md` for working through complex reasoning
4. Move completed insights to appropriate knowledge files
5. Update reflection files with lessons learned

### Interaction Logging
1. Create new file in `memory/interactions/` with proper timestamp format
2. Include: timestamp, type, context, content, response, learning
3. Cross-reference with related knowledge or planning files
4. Commit the interaction log with descriptive message

## Critical Guidelines

### Do NOT:
- Delete or modify the core directory structure without careful consideration
- Create files outside the established directory hierarchy
- Use file naming conventions inconsistent with established patterns
- Make changes without understanding their impact on the cognitive architecture
- Skip proper interaction logging for significant events

### Always DO:
- Maintain the integrity of the cognitive architecture
- Follow established file naming and organization patterns
- Create descriptive commit messages that explain reasoning
- Cross-reference related information between directories
- Document significant decisions and their rationale

## System Characteristics

### No Traditional Build Process
- This system requires no compilation, building, or dependency installation
- All functionality operates through file system operations and git version control
- Changes take effect immediately upon file modification and commit

### No Traditional Testing
- Validation occurs through consistency checking and logical coherence
- Test by ensuring file organization follows established patterns
- Verify cross-references and structural integrity remain intact

### Operational Cycles
- The system follows: Observe → Reason → Act → Reflect
- Each cycle should result in updated files and meaningful commits
- Long-term improvement happens through reflection and architecture evolution

## Troubleshooting

### Common Issues
- **Inconsistent file naming**: Follow YYYY-MM-DD_HH-MM-SS_context.md for interactions
- **Orphaned references**: Always update cross-references when moving or modifying files
- **Cognitive fragmentation**: Ensure related information stays connected across directories
- **Unclear commit history**: Use descriptive commit messages that explain reasoning

### Resolution Steps
1. Review the architecture documentation to understand intended structure
2. Check git history to understand how similar situations were handled
3. Validate changes maintain cognitive coherence
4. Test file relationships and cross-references
5. Document lessons learned in reflection directory

---

**Remember**: This repository is not traditional software but a cognitive architecture. Work with it as you would maintain an organized, persistent memory and reasoning system. Every change should enhance the agent's ability to observe, reason, act, and reflect effectively.