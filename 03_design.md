# Phase 3 – Project Design

## Architecture
Browser → Flask Web Application → MongoDB Database

## Main Components
1. Presentation layer – HTML/CSS
2. Application layer – Flask/Python
3. Data layer – MongoDB

## Database
Database: `pocketsmart_db`
Collection: `expenses`

### Expense Document
- title: string
- amount: number
- category: string
- date: datetime

## Main Flow
Add Expense → Flask validates input → MongoDB stores document → Dashboard reads records → Summary and recommendation are displayed.
