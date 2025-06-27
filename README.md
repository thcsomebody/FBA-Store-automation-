Workflow Overview

This automation runs weekly and handles the complete Amazon FBA pipeline from sourcing to repricing. This workflow is designed to make your Amazon FBA store completely hands off by automatically sourcing products, establishing supplier relationships, manages inventory processing, and optimizes pricing. Each component includes error handling and fallback options to ensure reliable operations. 

Key Components:

1. Prep Center Discovery: 
Scrapes prepcenter.com to find reliable prep centers with high ratings

2. AI-Powered Wholesaler Research:
Uses Claude API with your exact prompt to find 10 authorized wholesale distributors

3. Automated Dealer Inquiries: 
Sends professional emails using your provided script to establish wholesale accounts

4. Winning Product Analysis: 
Connects to Scan Unlimited to identify profitable products with low competition

5. Automated Ordering: 
Places orders with wholesalers and coordinates shipping to prep centers

6. Prep Center Integration:
Manages FBA prep services (labeling, bundling, inspection)

7. GoAura Repricing Setup: 
Automatically configures competitive repricing strategies

8. Comprehensive Logging & Notifications: 
Tracks all activities and sends completion alerts

Advanced Features:

Smart Product Filtering: Only selects products with 25%+ margins and sales rank under 100k

Automated Email Campaigns: 
Professional dealer inquiry emails with attachments

Status Monitoring: 
Tracks prep center processing until Amazon shipment

Competitive Repricing: 
Sets up hourly repricing with 20-40% margin protection

Complete Audit Trail: 
Logs all automation runs for business intelligence

Required Credentials:

- Anthropic API 

- Gmail OAuth2

- Scan Unlimited API

- GoAura API

- PostgreSQL Database

- Whatsapp Bot (notifications)

Setup instructions: 
1. Import this JSON code into n8n 

2. Implement API credentials 

3. Set up Whatsapp id for notifications 

4. Config database connection 

5. Test out , deploy and enjoy! 


1. Import this workflow into n8n
2. Configure all API credentials in the credentials section
3. Update business documents for email attachments
4. Set your Telegram chat ID for notifications
5. Configure database connection for logging
6. Test individual nodes before full automation

This workflow creates a completely hands-off Amazon FBA business that automatically sources products, establishes supplier relationships, manages inventory processing, and optimizes pricing - all while providing full visibility into operations.

The automation is designed to run weekly but can be adjusted based on your business needs. Each component includes error handling and fallback options to ensure reliable operation. 
