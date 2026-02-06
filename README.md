# Bridgewell AI: Automated Prospecting Pipeline
An end-to-end data engineering pipeline built to automate lead generation for wealth managers.

# Pipeline Process
Traffic
  ↓
Website (Positioning + CTA)
  ↓
Calendly (Qualification + Scheduling)
  ↓
Auto-confirm + prep message
  ↓
Bridgewell AI (internal support)
  ↓
Sales Call
  ↓
Client

# Business Impact
- Efficiency: Automated 25+ hours of manual prospecting per week.
- Accuracy: Achieved a 95% data validity rate post-cleaning, significantly reducing bounce rates.
- Website: bridgewellprivate.com

# Technical Architecture
The system follows a 4-stage Data Science lifecycle:
1. Data Acquisition: - Scrapes public financial data using BeautifulSoup and Selenium.
   - Integrates with Apollo.io and **LinkedIn APIs for enriched contact verification.
2. Preprocessing & Wrangling:
   - Cleans unstructured data using Pandas.
   - Implements logic to remove duplicates and validate email syntax/domain health.
3. Algorithmic Filtering:
   - Applies a weighted scoring algorithm to rank leads based on client-defined AUM and location criteria.
4. Automated Outreach:
   - Triggers AI-personalized email sequences with SMTP and OpenAI API for context-aware messaging.

# Tech Stack
- Languages: Python (Pandas, NumPy)
- Scraping: Selenium, BeautifulSoup
- API Integration: OpenAI, Apollo, LinkedIn
- Tools: SQL, Vercel (Frontend)

**Bryce Soli | Data Science Senior @ Bryant University**
