# CrewAI Marketplace Template

Welcome to the CrewAI Marketplace Template! This project is designed to help you build and submit your own AI crew templates to the [CrewAI Marketplace](https://marketplace.crewai.com). Using the powerful [crewAI](https://crewai.com) framework, you can create multi-agent AI systems that collaborate effectively on complex tasks, and then share them with the community.

## What is a Crew Template?

A crew template is a pre-configured set of AI agents, tasks, and workflows that solve a specific problem or perform a particular function. By creating a crew template, you make it easy for others to deploy sophisticated multi-agent systems for their own needs.

**Approved templates will be hosted in the CrewAI Enterprise application**, giving your creation visibility to a wide range of enterprise users.

## Getting Started with This Template

This template provides a foundation for creating your own marketplace-ready crew. Below are the steps to customize it for your specific use case.

## Installation

Ensure you have Python >=3.10 <3.13 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```

### Creating Your Project README

When preparing your crew for the marketplace, it's essential to replace this template README with your own. Your README should include:

- **Title**: A clear, descriptive title for your crew
- **Description**: A detailed explanation of what your crew does, what problem it solves, and why it's valuable
- **Example Use Cases**: Real-world scenarios where your crew would be helpful
- **Dependencies**: List all required dependencies, APIs, or external services
- **Configuration Instructions**: How to set up and customize your crew
- **Usage Examples**: Sample commands and expected outputs

A well-crafted README is critical for marketplace acceptance and helps users understand how to leverage your crew effectively.

### LLM Flexibility and Custom Tools

You are encouraged to:
- **Use any LLM model** of your choice, not just OpenAI models
- **Implement custom tools** that enhance your crew's capabilities
- Optimize your crew for specific use cases or industries

Creating a template with unique tools and model flexibility will make your submission more valuable to the marketplace users.

When designing your crew for the marketplace, focus on creating a solution that:
- Solves a specific, valuable problem
- Has clear inputs and outputs
- Is easy for users to understand and implement
- Demonstrates the power of multi-agent collaboration

## Running Your Crew

To test your crew of AI agents and verify task execution, run this from the root folder of your project:

```bash
$ crewai run
```

This command initializes your crew, assembling the agents and assigning them tasks as defined in your configuration.

The example template, unmodified, will create a `report.md` file with research on LLMs in the root folder.

## Preparing for Marketplace Submission

Before submitting your crew template to the [CrewAI Marketplace](https://marketplace.crewai.com), ensure:
1. You've replaced this template README with your own custom README (as outlined in the "Creating Your Project README" section)
2. Your code is well-documented
3. The configuration files are clear and properly formatted
4. You've tested the crew thoroughly with different inputs
5. Your README explains what the crew does and how users can customize it for their needs
6. You've specified any special LLM requirements or custom tools needed
7. All dependencies are clearly listed and version-pinned where appropriate

Remember that approved templates will be featured in the CrewAI Enterprise application, so enterprise-ready templates with clear business value have a higher chance of being approved.

## Support

For support, questions, or feedback regarding this template or crewAI:
- Visit our [documentation](https://docs.crewai.com)
- Reach out to us through our [GitHub repository](https://github.com/joaomdmoura/crewai)
- [Join our Discord](https://discord.com/invite/X4JWnZnxPb)
- [Chat with our docs](https://chatg.pt/DWjSBZn)
- For marketplace submission questions: [marketplace.crewai.com](https://marketplace.crewai.com)

Let's build the future of AI agent marketplaces together with crewAI!
