# Software Requirements Specifications (SRS)

The purpose of this document is to act as a guide for the development team, detailing how the software should perform and interact. It outlines the purpose, behavior, and functionality of a software application.

| Document Version | Date (mm/dd/yyyy) |
| :--------------- | :---------------- |
| 1.0.             | 04/02/2026        |

## 1. Introduction

### 1.1. Purpose

The **Daily Dish Book** project is built to digitalize, collect and organize food recipes that should be easily accesible from the website. The website is intended to be used only for personal use.

### 1.2. Intended Audience

This document is intended for software developers that participe in the project to provide a clear direction on how the development of the project should be performed.

### 1.3. Product Scope

- The website offers the user a modern and digitalized way to consult the collected food recipes from a device with internet access.
- The website access is free, and no authentication is needed to use it.
- The system does not offer an interface to add new recipes from the website. New recipes will be added by the developer from source code contents.
- The website allows to search and filter recipes using rules defined by the developer.

## 2. System Features and Requirements

### 2.1. Functional Requirements

2.1.1. The system shall provide a navigation bar for navigating between website pages.

2.1.2. While the user is in the recipes page, the system shall provide an option to order the recipe previews by recently added date.

2.1.3. While the user is in the recipes page, the system shall provide an option to filter the recipe previews by categories.

2.1.4. When the user clicks on a recipe preview, the system shall navigate to the actual recipe content page.

2.1.5. While the user is in the search page, the system shall provide a search bar for searching recipes.

2.1.6. When introducing an input in the search bar, the system shall display a list of matching recipe previews. When the user clicks on one of them, the system shall navigate to the recipe content page.

2.1.7. While the user is in a recipe content page, the system may provide an option to download a recipe in PDF format.

### 2.2. Non-Functional Requirements

2.2.1. The system shall function in a continuous and reliable way, without unexpected crashes.

2.2.2. The system shall support browsers < 2 years old. IE shall be excluded.

2.2.3. The system shall provide quick response times to user requests, be accesible and SEO oriented, performing a score of > 90 in lighthouse analysis.

2.2.4. The system UI shall be responsive to different device sizes.

2.2.5. Adding new content shall not impact other website pages and its deployment shall not take longer than 1 hour.

2.2.6. Deployment of website shall be automated using a deployment pipeline.

## 3. Other Requirements

### 3.1. Internationalization and Localization

3.1.1. System shall provide content in Spanish (ESP).

3.1.2. System may provide content in English (ENG).
