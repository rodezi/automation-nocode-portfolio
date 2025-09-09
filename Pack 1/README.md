🧠 Pack 1: AI Abandoned Checkout Assistant

This package was a full automation I did for a client in Upwork. 🛍️ Shopify + Klaviyo + Make + n8n + AI

He has a Shopify Agency and wanted to sell a solutions for his clients to track down payments and abandoned checkouts. 
This assistant tracks abandoned checkouts using webhooks, retrieves customer info, applies delays, and triggers custom events in Klaviyo. If payment doesn't go through, it uses AI to send a personalized recovery email based on the product left behind.

Main Workflow in N8N tracks down via webhooks the payment or the abandoned checkout
2nd workflow adds the potencial client to Airtable to a special sheet to retrive the customer information
