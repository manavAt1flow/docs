# Tuesday Leads API Documentation 📊

> **Open-source documentation for the most comprehensive LinkedIn data extraction and people intelligence API**

[![API Status](https://img.shields.io/badge/API-Live-brightgreen)](https://api.tuesday.so)
[![Documentation](https://img.shields.io/badge/docs-mintlify-blue)](https://docs.tuesday.so)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/tuesdayco/docs)](https://github.com/tuesdayco/docs)

**🔗 LinkedIn URL Scraping • 📧 Email Lookup • 📱 Phone Number API • 🏢 Company Intelligence • 🔍 Reverse Lookup**

## What is Tuesday Leads API?

Tuesday Leads API is the most powerful **LinkedIn data extraction** and **people intelligence platform** available. Extract comprehensive professional profiles, company data, and contact information from LinkedIn URLs, emails, and phone numbers.

### 🚀 Key Features

- **LinkedIn URL Scraping** - Extract full professional profiles from LinkedIn URLs
- **Email to LinkedIn Lookup** - Find LinkedIn profiles and professional data from email addresses  
- **Phone Number Reverse Lookup** - Discover professional profiles from phone numbers
- **LinkedIn Company Data** - Scrape comprehensive company information and employee lists
- **Contact Enrichment** - Add verified email addresses and phone numbers to profiles
- **People Search API** - Advanced search with 50+ filters for prospect discovery
- **Mobile Number API** - Mobile phone number lookup and validation
- **Reverse Email Lookup** - Professional profile discovery from email addresses
- **LinkedIn Profile API** - Comprehensive LinkedIn data extraction
- **Company Intelligence** - Funding data, technology stack, and employee insights

## 🔧 API Capabilities

### 👤 People Data Extraction
- **LinkedIn Profile Scraping** - Full profile data from LinkedIn URLs
- **Email-to-Profile Lookup** - Find profiles from email addresses
- **Phone Number Lookup** - Reverse phone number search
- **Contact Enrichment** - Add email/phone to existing profiles
- **Employment History** - Current and past job information
- **Location Data** - Current city, state, country information

### 🏢 Company Intelligence  
- **LinkedIn Company Scraping** - Full company profiles from LinkedIn pages
- **Domain Lookup** - Company information from website domains
- **Employee Search** - Find employees at target companies
- **Funding Data** - Investment rounds, investors, and valuation
- **Technology Stack** - Tools and platforms used by companies
- **Company Metrics** - Employee count, revenue, and growth data

### 🔍 Search & Discovery
- **Advanced People Search** - 50+ filters for prospect discovery
- **Company Search** - Find companies by industry, size, location
- **Boolean Search** - Complex search queries with multiple criteria
- **List Building** - Build targeted prospect lists at scale
- **Market Research** - Analyze markets and competitive intelligence

## 🚀 Getting Started

### Get Your API Key
1. Sign up at [Tuesday Dashboard](https://app.tuesday.so)
2. Navigate to API Keys section
3. Generate your API key
4. Start making requests!

### Quick Example - LinkedIn URL Scraping

```bash
# Extract LinkedIn profile data
curl -H "X-API-KEY: your-api-key" \
  "https://api.tuesday.so/api/v1/people/profile?linkedin_url=https://www.linkedin.com/in/example"
```

```javascript
// JavaScript example
const response = await fetch('https://api.tuesday.so/api/v1/people/profile?linkedin_url=https://www.linkedin.com/in/example', {
  headers: { 'X-API-KEY': 'your-api-key' }
});
const profile = await response.json();
```

### Email Reverse Lookup

```bash
# Find LinkedIn profile from email
curl -H "X-API-KEY: your-api-key" \
  "https://api.tuesday.so/api/v1/people/lookup/email?email=john@company.com"
```

### Phone Number API

```bash
# Reverse phone number lookup
curl -H "X-API-KEY: your-api-key" \
  "https://api.tuesday.so/api/v1/people/lookup/phone?phone=+1-555-123-4567"
```

## 📚 Documentation Structure

```
docs/
├── api-reference/
│   ├── auth/                 # API authentication
│   ├── people/              # People data extraction
│   │   ├── profile.mdx      # LinkedIn profile scraping
│   │   ├── search.mdx       # Advanced people search
│   │   ├── lookup-email.mdx # Email reverse lookup
│   │   └── lookup-phone.mdx # Phone number API
│   └── company/             # Company intelligence
│       ├── profile.mdx      # Company data extraction
│       ├── search.mdx       # Company search
│       └── employee-search.mdx # Employee discovery
├── authentication.mdx        # API key setup
├── quickstart.mdx           # Getting started guide
├── rate-limits-and-credits.mdx # Usage limits
└── errors.mdx               # Error handling
```

## 🎯 Use Cases

### 🎯 Sales & Lead Generation
- **LinkedIn Prospecting** - Find and qualify leads from LinkedIn
- **Email Enrichment** - Add email addresses to prospect lists
- **Phone Number Discovery** - Get direct contact information
- **Company Research** - Research target accounts before outreach

### 📊 Market Research
- **Competitive Analysis** - Analyze competitors and their employees
- **Industry Mapping** - Understand market landscapes
- **Talent Intelligence** - Track talent movement and hiring trends
- **Technology Adoption** - See what tools companies use

### 🔗 CRM Enhancement
- **Contact Enrichment** - Enrich existing CRM contacts
- **Data Validation** - Verify contact information accuracy
- **Profile Completion** - Fill gaps in customer profiles
- **Automated Updates** - Keep contact data fresh

### 🎯 Recruitment & HR
- **Candidate Sourcing** - Find qualified candidates
- **Profile Screening** - Research candidate backgrounds
- **Competitive Intelligence** - Track competitor hiring
- **Talent Mapping** - Map talent in specific markets

## 🔧 API Endpoints

### People APIs
- `GET /people/profile` - LinkedIn profile extraction
- `GET /people/lookup/email` - Email reverse lookup  
- `GET /people/lookup/phone` - Phone number lookup
- `POST /people/search` - Advanced people search

### Company APIs  
- `GET /company/profile` - Company data extraction
- `GET /company/search` - Company search
- `GET /company/employee-search` - Employee discovery
- `GET /company/employee-count` - Employee metrics

### Authentication
- `GET /auth/check-api-key` - Verify API key

## 🚀 Features

### LinkedIn Data Extraction
- ✅ **Profile Scraping** - Full LinkedIn profile data
- ✅ **Company Pages** - Complete company information
- ✅ **Employee Lists** - Company employee discovery
- ✅ **Contact Information** - Email and phone enrichment
- ✅ **Employment History** - Current and past positions
- ✅ **Skills & Endorsements** - Professional skills data

### Search & Discovery
- ✅ **Advanced Filters** - 50+ search parameters
- ✅ **Boolean Logic** - Complex search queries
- ✅ **Geographic Targeting** - Location-based search
- ✅ **Industry Filters** - Search by industry/vertical  
- ✅ **Company Size** - Filter by employee count
- ✅ **Technology Stack** - Find companies using specific tools

### Data Enrichment
- ✅ **Email Discovery** - Find verified email addresses
- ✅ **Phone Numbers** - Mobile and business phone lookup
- ✅ **Social Profiles** - LinkedIn and other social links
- ✅ **Company Intelligence** - Funding, revenue, technology data
- ✅ **Verification** - Data accuracy and validation
- ✅ **Real-time Updates** - Fresh, up-to-date information

## 📖 Documentation

This repository contains the complete documentation for the Tuesday Leads API, built with [Mintlify](https://mintlify.com).

### Local Development

```bash
# Install Mintlify CLI
npm install -g mint

# Start local dev server
mint dev

# The documentation will be available at localhost:3000
```

### Building Documentation

```bash
# Build the documentation
mint build

# Deploy to production
mint deploy
```

## 🏷️ Keywords & SEO

**Primary Keywords:** LinkedIn scraping, email lookup, phone number API, reverse lookup, people search, company intelligence, contact enrichment, LinkedIn API, professional data extraction

**Technical Keywords:** LinkedIn URL scraping, email to profile lookup, phone number reverse lookup, mobile number API, LinkedIn profile extraction, company data scraping, employee search, prospect discovery, sales intelligence

**Industry Keywords:** lead generation, sales automation, CRM enrichment, market research, competitive intelligence, talent acquisition, B2B data, business intelligence, contact discovery, professional networking data

## 🔗 Links

- **📊 API Dashboard:** [app.tuesday.so](https://app.tuesday.so)
- **📚 Documentation:** [docs.tuesday.so](https://docs.tuesday.so)  
- **🔑 Get API Key:** [app.tuesday.so/api-keys](https://app.tuesday.so/settings/api)

## 📋 API Reference

### Authentication
All requests require an API key in the `X-API-KEY` header. [Get your API key here](https://app.tuesday.so/settings/api).

### Rate Limits
- 20 requests/minute

### Response Format
All responses follow a consistent JSON structure:
```json
{
  "data": { /* response data */ },
  "statusCode": 200,
  "message": "Success"
}
```

## 🤝 Contributing

This is an open-source documentation project. Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This documentation is open-source and available under the [MIT License](LICENSE).

---

**Ready to start extracting LinkedIn data?** [Get your API key](https://app.tuesday.so/settings/api) and begin building with the most comprehensive people intelligence API available.

**Keywords:** linkedin scraping, email lookup, phone number api, reverse lookup, linkedin api, people search, company intelligence, contact enrichment, mobile number api, linkedin profile extraction, email to profile lookup, phone number reverse lookup, professional data extraction, sales intelligence, lead generation, crm enrichment, market research, competitive intelligence, talent acquisition, b2b data, business intelligence, contact discovery, linkedin url scraping, employee search, prospect discovery, linkedin company data, social media api, professional networking data, contact verification, data enrichment, people analytics, sales automation, linkedin data extraction
