# MultiLLM_Autogen

## AI-powered Multi-Agent System for Building Portfolio Websites

This project creates a personal portfolio webpage targeted at product managers who are searching for jobs in the United States. The system uses Microsoft AutoGen to simulate an entire web development company where five specialized AI agents (Product Manager, Designer, Developer, Researcher, and User Proxy) collaborate to build professional, modern portfolio websites.

## Features

- **Product Manager Agent**: Oversees the overall project direction, ensuring that the webpage aligns with the goal of showcasing the profile for a job search.
- **Software Developer Agent**: Responsible for coding the webpage, generating HTML, CSS, and any required backend code.
- **Designer Agent**: Creates innovative UI/UX designs to clearly present the product manager's skills, experience, and projects.
- **Researcher Agent**: Gathers information on what makes a successful personal portfolio webpage for product managers.
- **User Proxy Agent**: Acts as the human input interface, allowing human intervention where necessary.

## Project Structure

The project leverages the following agents:
- **ProductManager**: Directs the project to ensure that the webpage meets the expectations of a product manager's job search portfolio.
- **SoftwareDeveloper**: Generates code files for the webpage, including HTML and CSS.
- **Designer**: Focuses on creating a clean and effective design for the personal webpage.
- **Researcher**: Performs research to optimize the webpage's content and structure based on industry best practices.
- **UserProxyAgent**: Facilitates human input when needed.

## Setup and Installation

### Prerequisites
- Python 3.7+
- [OpenAI API Key](https://openai.com/)
- [Dotenv](https://pypi.org/project/python-dotenv/) for loading environment variables
