

# **Overall Project Overview**

**Objective:**  
Develop an intelligent AI agent using the ElizaOS framework that:  
- Monitors X (Twitter) for tweets related to lotteries and crypto topics.
- Generates cheerful, on-brand replies that highlight Boost Lottery’s unique selling points (USPs) by drawing on source material (whitepaper, website, industry data).
- Provides a “review” (or dry-run) mode so that responses can be previewed before posting.
- Is fully configurable for keywords, topics, training data, and sentiment.

**Key Technologies:**
- **ElizaOS Framework:** Built in TypeScript for creating, deploying, and managing autonomous AI agents.
- **APIs:**  
  - Twitter credientials tweet monitoring and posting.
  - OpenAI API for natural language generation.

---

# **Phase 1: Automated Twitter Reply Agent**

### **Goals for Phase 1:**
- Configure eliza to monitors Twitter for tweets about lotteries and crypto-related topics.
- Generate on-brand, cheerful replies that emphasize the advantages of Boost Lottery.
- Incorporate a review/dry-run mode where generated replies can be previewed before being posted.
- Provide full documentation and instructions for further training and configuration.

### **Detailed Tasks and Timeline (5–6 Working Days):**

    
3. **Data Acquisition Module**
   - **Keyword & Topic Configuration:**  
     - Define configurable keywords (e.g., “lottery”, “crypto”, “ticket”, “dreaming of winning”, “buying a ticket”, “disappointment”, etc.).

5. **Review/Dry-run Functionality (Day 3–4)**
   - **Preview Mode Implementation:**  
     - Develop a feature (via a web dashboard or command-line output) that displays the generated tweet for manual review.
     - Include a toggle option (e.g., via an environment variable such as `DRY_RUN=true`) to switch between live posting and review mode.
   - **Approval Workflow:**  
     - Optionally, implement a manual approval mechanism where a user can trigger the posting after reviewing the response.
   - **Testing:**  
     - Run end-to-end tests to simulate the complete flow from tweet detection to review output.


# **Phase 2: Enhanced Social Media Automation**

### **Goals for Phase 2:**
- Expand the system to support drafting tweets based on real-time sentiment analysis and scraping news sources.
- Automate the overall social media strategy across multiple platforms, including Twitter, Discord, and Telegram.
- Implement an intelligent marketing strategy module that suggests campaigns and content before execution.
- Maintain configurability and review/dry-run functionalities to ensure quality and on-brand communication.

### **Detailed Tasks and Timeline:**

1. **Advanced Tweet Drafting Module**
   - **Sentiment-Based Drafting:**  
     - Enhance the reply generation module to factor in real-time sentiment analysis from scraped news and social sentiment on Twitter.
     - Integrate additional data sources (news feeds, industry reports) to refine content generation.
   - **Automated Draft Creation:**  
     - Develop a module that drafts tweets automatically and stores them in a queue.
     - Include options for manual review and scheduling before posting.

2. **Multi-Platform Integration (Twitter, Discord, Telegram)**
   - **Platform Connectors:**  
     - Build connectors for Discord and Telegram in addition to Twitter.
     - Ensure that the core logic (data acquisition, content generation, and review) is abstracted so it can be reused across platforms.
  
3. **Automated Social Media Strategy Module**
   - **Campaign Drafting & Scheduling:**  
     - Create a module that can automatically suggest campaign strategies based on trending topics, sentiment analysis, and historical engagement data.
   

