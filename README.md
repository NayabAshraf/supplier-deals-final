# Market Lens: Supplier Analysis

A web-based supplier analysis platform designed to help users discover, analyze, and compare supplier deals across multiple online marketplaces.

The platform provides a user-friendly interface where users can search for products, explore supplier listings, compare prices, and identify potential deals with the help of AI-powered analysis.

## Live Demo

**[View Live Application](https://supplier-deals-final.vercel.app/)**

## Project Overview

Supplier Analysis is a web application that simplifies supplier research and price comparison. It helps users evaluate product listings from different marketplaces and make more informed purchasing decisions.

The project consists of two main parts:

- **Frontend:** A web application built with Next.js, React, and TypeScript.
- **Backend:** An n8n automation workflow responsible for the supplier data processing and analysis.

The backend automation is maintained separately and is not included in this public repository due to confidentiality requirements.

## Key Features

- **Product Search:** Search for products to explore available supplier listings.
- **Multi-Marketplace Comparison:** Compare supplier offers and product prices across six different marketplaces.
- **Supplier Analysis:** Review supplier information, ratings, pricing, and available product details.
- **Best Deal Identification:** Identify competitive supplier offers based on available listing information.
- **AI-Powered Insights:** Generate analysis and insights to support supplier evaluation.
- **Currency Conversion:** View prices in different supported currencies.
- **Supplier Reports:** View and export supplier analysis reports.
- **Responsive Interface:** User-friendly design for different screen sizes.

## Technology Stack

| Category | Technologies |
|---|---|
| Frontend | Next.js, React |
| Programming Language | TypeScript |
| Styling | Tailwind CSS |
| Icons | Lucide React |
| Backend Automation | n8n |
| Deployment | Vercel |

## System Architecture

The application uses a frontend and backend automation architecture.

1. Users enter product search information through the frontend.
2. The frontend communicates with the backend automation.
3. The n8n workflow handles supplier data collection and processing.
4. Supplier information is analyzed and compared.
5. Results and insights are presented through the frontend.

**Note:** The n8n backend workflow and its configuration are private and are not included in this repository.

## Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

1. Clone the repository:

```bash
git clone https://github.com/NayabAshraf/supplier-deals-final.git
```

2. Navigate to the project directory:

```bash
cd supplier-deals-final
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

5. Open your browser:

```text
http://localhost:3000
```

**Note:** The complete application functionality may require access to the separately maintained backend automation and its configured services.

## Deployment

The frontend application is deployed using **Vercel**.

Live Application: https://supplier-deals-final.vercel.app/

## Backend Confidentiality

The n8n automation workflows, backend configuration, API credentials, and related confidential implementation details are intentionally excluded from this public repository.

The public repository contains the frontend source code only.

