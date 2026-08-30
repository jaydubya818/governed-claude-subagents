# 🚀 Claude Code Sub-Agents Collection

A comprehensive collection of **116 specialized AI sub-agents** optimized for Claude Code with parallel execution capabilities, enhanced communication protocols, and comprehensive quality assurance.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Subagents](https://img.shields.io/badge/subagents-116-7057ff.svg)](#)
[![Categories](https://img.shields.io/badge/categories-12-informational.svg)](#)
[![Claude Code](https://img.shields.io/badge/for-Claude%20Code-D97757.svg)](https://claude.com/claude-code)

> **Note:** this repository was previously named `awesome_claude_agents`. GitHub redirects the old URL, but please update any bookmarks or clones.

> **Provenance:** parts of this collection are adapted from other people's work —
> six agents from [wshobson/agents](https://github.com/wshobson/agents) (MIT, © 2024 Seth Hobson),
> and `external_repos/open-swe/` is a vendored copy of
> [LangChain's Open SWE](https://github.com/langchain-ai/open-swe) (MIT, © LangChain, Inc.)
> that is not covered by this repository's root LICENSE. Full detail in [CREDITS.md](CREDITS.md).

## 🎯 Quick Start

### **Setup**
```bash
# Run the setup script
./setup_claude_agents.sh

# Optimize all agents
./optimize_agents.sh

# Clean up untracked files (optional)
./cleanup_untracked.sh

# Validate setup
./.claude/validate_agents.sh
```

### **Usage**
```bash
# Start with orchestrator for complex projects
@supervisor-orchestrator Build a React e-commerce app

# Set up sprint management
@ai-scrum-master Set up automated sprint management

# Review code with parallel testing
@code-reviewer Review this codebase
```

## 📊 Agent Distribution

| Category | Count | Status |
|----------|-------|--------|
| 🎯 Orchestration & Management | 6 | ✅ Enhanced |
| 🏗️ Development & Architecture | 30 | ✅ Enhanced |
| 🎨 Design & UX | 7 | ✅ Enhanced |
| 🔧 Quality Assurance & Testing | 15 | ✅ Enhanced |
| 🔒 Security & Compliance | 4 | ✅ Enhanced |
| 📊 Data & AI | 4 | ✅ Enhanced |
| 🚀 DevOps & Infrastructure | 13 | ✅ Enhanced |
| 📝 Documentation & Communication | 6 | ✅ Enhanced |
| 🎯 Product & Business | 9 | ✅ Enhanced |
| 📈 Marketing & Growth | 7 | ✅ Enhanced |
| 🏢 Operations | 5 | ✅ Enhanced |
| 🎭 Specialized & Utility | 9 | ✅ Enhanced |
| **Total** | **116** | **100% Optimized** |

## 🚀 Key Features

- ✅ **Parallel Execution**: All agents can work simultaneously
- ✅ **Enhanced Communication**: Standardized protocols across all agents
- ✅ **Quality Gates**: Built-in validation and review processes
- ✅ **Intelligent Coordination**: Optimal agent selection and delegation
- ✅ **Comprehensive Documentation**: Complete setup and usage guides
- ✅ **Wshobson Integration**: Enhanced with 6 high-priority development agents

## 📁 Project Structure

```
agents/
├── .claude/                    # Claude Code configuration
│   ├── agents/                # All 116 optimized agents
│   ├── config.json           # Claude Code configuration
│   └── optimization/         # Optimization settings
├── docs/                     # Documentation
├── setup_claude_agents.sh    # Setup script
├── optimize_agents.sh        # Optimization script
├── cleanup_untracked.sh      # Cleanup script
├── .gitignore               # Git ignore file
└── README.md                # This file
```

## 🎯 Usage Examples

### **Development Projects**
```
@supervisor-orchestrator Build a React e-commerce app with payment integration
```

### **Systems Programming**
```
@c-pro Optimize this C function for better performance
@rust-pro Fix these ownership and borrowing issues in this Rust code
@cpp-pro Refactor this C++ code to use modern patterns
```

### **Web & Enterprise Development**
```
@javascript-pro Refactor this JavaScript code to use modern ES6+ features
@java-pro Create a Spring Boot microservice with parallel processing
@sql-pro Optimize this SQL query for better performance
```

### **Business Projects**
```
@supervisor-orchestrator Launch a meditation app with marketing strategy
```

### **Sprint Management**
```
@ai-scrum-master Set up automated sprint management for the development team
```

### **Quality Assurance**
```
@code-reviewer Review this codebase with parallel testing
```

## 📋 Available Commands

### **Setup & Management**
- `./setup_claude_agents.sh` - Initial setup of all agents
- `./optimize_agents.sh` - Optimize all agents with parallel execution
- `./cleanup_untracked.sh` - Clean up untracked files and organize documentation
- `./.claude/discover_agents.sh` - Discover all agents
- `./.claude/validate_agents.sh` - Validate agent setup

### **Agent Usage**
- `@supervisor-orchestrator` - Master coordinator for complex projects
- `@ai-scrum-master` - Automated sprint management
- `@code-reviewer` - Code review and quality assurance
- `@test-automator` - Automated testing
- `@react-pro` - React development with parallel optimization
- `@backend-architect` - Backend architecture and design

### **New Development Agents**
- `@c-pro` - C programming and systems development
- `@cpp-pro` - C++ programming and modern patterns
- `@rust-pro` - Rust programming and memory safety
- `@javascript-pro` - Modern JavaScript development
- `@java-pro` - Java development and Spring Boot
- `@sql-pro` - SQL development and database optimization

## 🎉 Success Metrics

- **Parallel Efficiency**: >80% parallel task completion
- **Task Completion**: >90% successful task completion
- **Quality Score**: >95% quality standards maintained
- **Coordination Effectiveness**: >85% effective agent coordination

## 📚 Documentation

All detailed documentation is available in the `docs/` directory:
- Setup guides and tutorials
- Optimization reports and analysis
- Usage examples and best practices
- Agent specifications and capabilities

---

**🎉 Ready to use with 116 optimized agents featuring parallel execution, enhanced communication, and comprehensive quality assurance! 🚀**

---

## Where these run

These subagents are the execution layer. If you want the control plane around
them — governed intake, bounded execution, independent verification, evidence,
and human-approved pull requests — see
**[Mission Control](https://github.com/jaydubya818/MissionControl)**, which treats
agent completion and verified success as two different things.

Related: [Agentic-KB](https://github.com/jaydubya818/Agentic-KB) for durable agent
memory, and [multi-agent-observability](https://github.com/jaydubya818/multi-agent-observability)
for tracing what a fleet of these actually did.

## License

MIT — see [LICENSE](LICENSE), and [CREDITS.md](CREDITS.md) for the parts of this
repository that belong to other people.
