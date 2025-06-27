# Claude Code Changelog

A comprehensive changelog tracking all updates and improvements to Claude Code, Anthropic's agentic command line coding tool.

## Overview

Claude Code is a terminal-based AI coding assistant that helps developers code faster by executing routine tasks, explaining complex code, and handling git workflows through natural language commands.

---

## Version History

### v1.0.27 - Latest (June 2025)
**Status: Generally Available**

#### 🚀 Major Features
- **Sonnet 4 & Opus 4 Model Support**: Access to the latest Claude models for enhanced coding capabilities
- **Claude Pro & Max Integration**: Full support for Pro and Max subscription plans
- **SDK Release**: TypeScript and Python SDKs now available for developers

#### 🔧 Core Features
- **Todo List Management**: Claude can now create and track todo lists to stay organized during complex tasks
- **Conversation Resumption**: Resume previous coding sessions seamlessly
- **Web Search Integration**: Claude can search the web for documentation and solutions
- **Image Support**: Paste and drag images directly into conversations

#### 🛠 Technical Improvements
- **MCP Server Enhancements**: 
  - SSE and HTTP transport support
  - Real-time communication capabilities
  - OAuth 2.0 authentication via `/mcp` command
  - Resource referencing with `@server:protocol://path` format
- **Performance Optimizations**: Faster startup times and improved responsiveness
- **Enhanced Error Handling**: More robust error detection and recovery

---

### v1.0.0 - June 11, 2025
**Status: General Availability Launch**

#### 🎉 Milestone Release
- **Official GA Release**: Claude Code transitions from research preview to generally available
- **SDK Launch**: 
  - TypeScript SDK for Node.js applications
  - Python SDK for Python applications
- **Enterprise Ready**: Production-ready stability and support

#### 🔐 Authentication & Security
- **Multiple Auth Methods**: Support for various authentication mechanisms
- **Tool Permissions**: Granular control over tool access and permissions
- **Secure API Integration**: Direct connection to Anthropic's APIs

---

### v0.2.x Series - March - May 2025
**Status: Research Preview Evolution**

#### 🆕 New Commands & Features
- **Custom Slash Commands**: 
  - Markdown files in `.claude/commands/` appear as custom slash commands
  - Insert custom prompts into conversations
- **Release Notes Command**: New `/release-notes` command for viewing updates
- **Thinking Mode**: Ask Claude to plan with enhanced reasoning:
  - `think` - standard planning mode
  - `think harder` - enhanced reasoning
  - `ultrathink` - maximum reasoning depth

#### ⚙️ Configuration Improvements
- **Multi-value Config**: `claude config add/remove` commands accept comma or space-separated values
- **MCP Integration**: 
  - Import MCP servers from Claude Desktop with `claude mcp add-from-claude-desktop`
  - Interactive MCP setup wizard via `claude mcp add`
  - Configurable startup timeout via `MCP_TIMEOUT` environment variable

#### 🎯 User Experience
- **Vim Bindings**: Enable vim-style keybindings with `/vim` or `/config`
- **Fuzzy Command Matching**: Improved command discovery and execution
- **Streaming Output**: Real-time response streaming for better interactivity

---

### v0.2.9 - February 24, 2025
**Status: Research Preview Launch**

#### 🚀 Initial Release
- **Agentic Command Line Tool**: First public release of Claude Code
- **Core Functionality**:
  - File editing across entire codebase
  - Code architecture analysis and explanations
  - Test execution and debugging
  - Git history searching and analysis
  - Merge conflict resolution
  - Commit and PR creation
  - Natural language command interface

#### 📦 Installation & Setup
- **NPM Package**: Install via `npm install -g @anthropic-ai/claude-code`
- **Simple Execution**: Run with `claude` command
- **No Additional Setup**: Direct terminal integration without complex configuration

#### 🔧 Development Tools
- **Multi-language Support**: Works with various programming languages and frameworks
- **Git Integration**: Comprehensive git workflow automation
- **Context Awareness**: Maintains understanding of project structure and context

---

## Enterprise & Platform Support

### Cloud Platform Integration
- **Amazon Bedrock**: Enterprise-grade deployment on AWS
- **Google Vertex AI**: Secure deployment on Google Cloud
- **Direct API**: Direct connection to Anthropic's infrastructure

### Security Features
- **Terminal-based Operation**: Runs directly in your development environment
- **API-only Communication**: No additional servers or complex infrastructure
- **Project Context Security**: Maintains secure awareness of your codebase

---

## Installation & Usage

### Quick Start
```bash
# Install Claude Code
npm install -g @anthropic-ai/claude-code

# Run Claude Code
claude
```

### Configuration
```bash
# Add configuration values
claude config add key value1,value2

# Remove configuration values  
claude config remove key

# Enable vim bindings
claude /vim
```

### MCP Server Setup
```bash
# Interactive setup wizard
claude mcp add

# Import from Claude Desktop
claude mcp add-from-claude-desktop
```

---

## Community & Feedback

### GitHub Repository
- **Source Code**: [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **Issues & Feedback**: Report bugs and request features
- **Full Changelog**: Detailed version history in `CHANGELOG.md`

### Community Requests
- Consistent release documentation
- Version pinning capabilities
- Enhanced update notifications
- Detailed feature migration guides

---

## What's Next

Claude Code continues to evolve with regular updates focusing on:
- Enhanced AI model capabilities
- Expanded tool integrations
- Improved development workflow automation
- Better enterprise features and security
- Community-requested features and improvements

---

*Last Updated: June 2025*  
*For the most current information, visit [docs.anthropic.com/claude-code](https://docs.anthropic.com/en/docs/claude-code)*