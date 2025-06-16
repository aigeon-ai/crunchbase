# Crunchbase MCP Server

Welcome to the Crunchbase MCP Server README. This document provides an overview of the features and functionalities of the Crunchbase server, allowing you to effectively harness its capabilities for building powerful applications.

## Overview

The Crunchbase MCP Server offers a RESTful API that allows you to integrate Crunchbase data into your web and mobile applications. It provides detailed information about organizations, people, funding rounds, acquisitions, IPOs, and more, enabling you to create dynamic applications with rich data insights.

## Key Features

- **Comprehensive Data Access**: The server provides access to a wide range of data endpoints, including organizations, people, categories, and locations. It supports retrieving both core properties and detailed information about related items.

- **Efficient Data Retrieval**: Utilize collection endpoints to retrieve entire datasets, or item detail endpoints for more specific data queries. The server supports pagination to handle large data sets efficiently.

- **Customizable Queries**: Refine your searches by specifying relationship types and customizing queries to focus on specific data points, such as funding rounds or investors.

- **Optimized Pagination**: Leverage key set pagination for faster and more reliable data traversal, ensuring you never miss an entity as the dataset evolves.

## Collections and Endpoints

The server offers a variety of collection endpoints to access key data types:

| Node Type     | Endpoint         |
|---------------|------------------|
| Organizations | /organizations   |
| Person        | /people          |
| Category      | /categories      |
| Location      | /locations       |

Detailed item endpoints allow you to delve deeper into specific data relationships:

| Node Type     | Endpoint                     |
|---------------|------------------------------|
| Organization  | /organizations/:permalink    |
| Person        | /people/:permalink           |
| Funding Round | /funding_rounds/:uuid        |
| Acquisition   | /acquisitions/:uuid          |
| IPO           | /ipos/:uuid                  |
| Fund          | /funds/:uuid                 |

## Search Functionality

The server includes powerful search capabilities, allowing complex filtering based on defined query parameters. Key search tool:

- **Organization Search**: Perform advanced searches on organization entities to filter data according to specific query criteria.

## Conclusion

The Crunchbase MCP Server is a robust tool for accessing and integrating Crunchbase data into your applications. With its extensive data access, customizable queries, and optimized pagination, you can efficiently build applications that leverage the rich dataset provided by Crunchbase.

For detailed usage and tool declarations, refer to the tool list and declarations within this README. Explore the potential of Crunchbase data and enhance your applications with valuable insights.