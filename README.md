# Model Prompts

This repository contains standardized instruction sets for AI model behaviors in development environments. Currently supporting Claude Desktop and Cline.

## Directory Structure

```
model-prompts/
├── claude-desktop/ - Claude's desktop environment instructions
│   ├── project/ - Project-level behaviors
│   │   └── instructions.md - Defines behavior within projects
│   └── system/ - System-level behaviors
│       └── instructions.md - Defines system operations
└── cline/ - Cline assistant instructions
    └── extension/
        └── instructions.md - Defines Cline's behavior and capabilities
```

## Components

### Claude Desktop
The Claude Desktop instructions define behavior for Claude in desktop environments, including:
- Project and system-level operations
- Memory bank management
- Documentation patterns
- Mode behaviors (Plan/Act)
- File operation formatting
- Response prefixing rules

### Cline
The Cline instructions define behavior for the Cline development assistant, featuring:
- Enhanced mode indicators with task tracking
- Memory bank structure
- Project intelligence system
- Documentation patterns
- Communication formatting

## Usage

### Claude Desktop
1. Clone this repository
2. Use `claude-desktop/project/instructions.md` for project-level behaviors
3. Use `claude-desktop/system/instructions.md` for system operations
4. Customize as needed while maintaining core functionality

### Cline
1. Clone this repository
2. Use `cline/extension/instructions.md` for Cline configuration
3. Follow the Memory Bank structure for project documentation
4. Maintain .clinerules for project-specific patterns

## Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with a clear description of changes

## License

This project is open source and available under the MIT license.
