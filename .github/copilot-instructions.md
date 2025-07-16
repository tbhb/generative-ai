# Copilot Instructions for Generative AI Repository

## Repository Purpose
This repository contains notebooks, proofs of concept, and other resources for personal generative AI learning and research. The focus is on educational exploration and experimentation with various AI models, techniques, and implementations.

## Tech Stack
- **Python**: 3.12+ (required)
- **Package Management**: uv (used for dependency management and virtual environments)
- **Code Quality**: ruff (for formatting and linting)
- **Development Environment**: Jupyter notebooks for experimentation and exploration

## Code Standards and Conventions

### Python Code Style
- Use ruff for both formatting and linting
- Follow PEP 8 conventions
- Use type hints where appropriate
- Write clear, descriptive docstrings for functions and classes
- Prefer readable code over clever one-liners

### Project Structure
- Use notebooks (.ipynb) for experimentation and learning
- Keep utility functions and shared code in separate modules
- Include clear README files in subdirectories when needed

### Dependencies
- Use uv for package management (uv add <package>)
- Keep dependencies minimal and focused
- Document any special installation requirements
- Use virtual environments for isolation

## Development Guidelines

### Notebooks
- Include clear markdown cells explaining the purpose and approach
- Add comments explaining complex AI concepts or implementations
- Include sample outputs and results when possible
- Clean up outputs before committing (optional, but preferred for clarity)

### Code Quality
- Run `ruff check` to identify linting issues
- Run `ruff format` to format code consistently
- Test code thoroughly before committing
- Include error handling for API calls and external dependencies

### Documentation
- Document learning objectives and outcomes
- Include references to papers, tutorials, or resources used
- Explain AI concepts and techniques for future reference
- Note any limitations or known issues

## AI-Specific Considerations

### API Usage
- Handle API keys securely (use environment variables)
- Implement proper error handling for API failures
- Respect rate limits and usage policies
- Include fallback mechanisms when appropriate

### Model Integration
- Abstract model interfaces when working with multiple providers
- Document model-specific parameters and behaviors
- Include examples of different prompt engineering techniques
- Test with different model versions when relevant

### Experimentation
- Keep experimental code organized and well-documented
- Include both successful and failed experiments for learning
- Document hyperparameters and configuration choices
- Save intermediate results and model outputs

## File Organization
- Use descriptive filenames that indicate the AI technique or model being explored
- Group related experiments in subdirectories
- Keep shared utilities in a common location
- Maintain a clear separation between different AI providers/platforms

## Contributing Guidelines
- This is a personal learning repository - prioritize educational value
- Include explanations of AI concepts and techniques
- Document the learning process and insights gained
- Keep code examples simple and focused on specific concepts

## Security and Ethics
- Never commit API keys or sensitive credentials
- Respect AI model usage policies and terms of service
- Consider ethical implications of AI implementations
- Document any data privacy or security considerations