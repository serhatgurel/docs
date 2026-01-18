# Agricultural System - A Multi-Stack Learning Project

## 🎯 Project Goals

**Primary Objective:** Learn diverse technology stacks through practical implementation of a real-world agricultural management system

**Key Principles:**

- **Breadth over perfection** - Exposure to many technologies trumps optimization
- **Sustainable pace** - This is a marathon, not a sprint; consistency beats intensity
- **Learn by doing** - Focus on hands-on implementation with different tech stacks
- **Document everything** - Create reusable cheat sheets and learnings for future reference
- **Containerize all** - Use Docker to ensure consistent, portable deployments
- **Life balance** - Family and work come first; learning is a long-term investment

## ⏰ Realistic Time Commitment

**You have a full-time job and family - this plan respects that reality.**

**Weekday Schedule (Monday-Friday):**

- **1-2 hours/day** (before work, lunch break, or evening)
- Focus on smaller tasks: code katas, reading docs, small features
- Some days you'll do 0 hours - **that's okay and expected**

**Weekend Schedule (Choose 1-2 days, max 6 days/week total):**

- **3-5 hours/day** on 1-2 weekend days
- Tackle larger features, deployments, new service creation
- **Keep 1 day completely free** for family/rest

**Monthly Commitment:**

- **Minimum:** 20-30 hours/month (still makes progress)
- **Realistic:** 40-50 hours/month (good sustainable pace)
- **Maximum:** 60-70 hours/month (if you're excited, but not required)

**Yearly Projection:**

- At 40 hours/month = **480 hours/year** of focused learning
- That's equivalent to 12 weeks of full-time work
- **Plenty to build 8-12 microservices and learn multiple stacks**

## 🏗️ Architecture Approach

Build the same agricultural domain using **Clean Architecture** principles, but implement each microservice with a different technology stack. This creates:

- **Comparative learning** - Direct experience with strengths/weaknesses of each stack
- **Realistic architecture** - Polyglot microservices mirror real-world enterprise systems
- **Reusable patterns** - Clean architecture concepts translate across languages
- **Portfolio diversity** - Demonstrate competency across multiple ecosystems

## 📚 Technology Learning Goals

# architectural patterns

- clean architecture
- event driven
- micro service oriented

# patterns

- Repository Pattern
- Unit of Work
- CQRS (Command Query Responsibility Segregation)
- Event Sourcing
- Saga Pattern (for distributed transactions)
- Circuit Breaker
- Retry / Resilience patterns
- Strangler Fig Pattern (for legacy migration)
- API Gateway Pattern
- Backend for Frontend (BFF)
- Domain-Driven Design (DDD)
- Dependency Injection
- Factory Pattern
- Observer Pattern
- Strategy Pattern

# database

- postgres (with PostGIS for geospatial data - perfect for agricultural plots)
- maria db
- mongo db
- memcached
- redis (caching & pub/sub)
- CosmosDB (Azure multi-model database)
- DynamoDB (AWS)
- SQLite (for mobile/embedded scenarios)
- InfluxDB (time-series for sensor data)
- TimescaleDB (PostgreSQL extension for time-series)

# mobile

- react native
- swift
- android

# rest api

- c# minimal api
- c# web api
- asp.net
- express js
- fast api
- go lang
- swift
- rust
- java
- php

# grpc

- c#
- python
- golang?
- consider swift, rust & java

# graphQL

- c#
- python?

# front ends

- vue
- react / react native
- angular
- blazor
- maui
- swift ui
- asp.net
- php
- win form
- bonus points for tcl/tk

# css / styling

- CSS Fundamentals (Flexbox, Grid, Animations)
- Tailwind CSS
- Bootstrap
- Sass/SCSS
- CSS-in-JS (styled-components, emotion)
- CSS Modules
- Utility-first CSS
- Responsive design patterns
- Dark mode implementation
- Accessibility (a11y) best practices

# cloud

- azure - bicep deployment
- aws
- consider google

# queues

- RabbitMQ
- Azure Service Bus
- AWS SQS
- Apache Kafka
- Redis Queue
- NATS
- ActiveMQ

# events

- Azure Event Grid
- AWS EventBridge
- Apache Kafka (event streaming)
- NATS JetStream
- Webhooks
- Server-Sent Events (SSE)
- WebSockets (real-time bidirectional)

# ci / cd

use github & github actions

# testing

- tdd (Test-Driven Development)
- bdd (Behavior-Driven Development)
- Unit Testing (xUnit, NUnit, Jest, pytest, JUnit)
- Integration Testing
- E2E Testing (Playwright, Cypress, Selenium)
- Contract Testing (Pact)
- Load Testing (k6, JMeter, Artillery)
- Mutation Testing
- Property-based Testing

# ai

- mcp server (Model Context Protocol)
- ai agent development
- LangChain / LangGraph
- Semantic Kernel
- Azure OpenAI Service
- AWS Bedrock
- Vector databases (Pinecone, Weaviate, Qdrant)
- RAG (Retrieval-Augmented Generation)
- Fine-tuning models
- Prompt engineering
- AI evaluation & monitoring

# cloud certifications

- azure
  - AZ-900 (Azure Fundamentals)
  - AZ-104 (Azure Administrator)
  - AZ-204 (Azure Developer)
  - AI-102 (Azure AI Engineer)
- aws
  - AWS Cloud Practitioner
  - AWS Solutions Architect Associate
  - AWS Developer Associate

# ai certification

- Microsoft AI-900 (AI Fundamentals)
- Microsoft AI-102 (AI Engineer Associate)
- AWS Machine Learning Specialty
- Google Professional ML Engineer
- Prompt Engineering certifications

# Agricultural System - Project Ideas

## Core Modules (Microservices)

1. **Farm Management Service**

   - Field/plot management with geospatial data
   - Crop rotation planning
   - Equipment tracking

2. **Crop Monitoring Service**

   - Growth stage tracking
   - Disease/pest detection (AI-powered)
   - Yield prediction

3. **Irrigation Management Service**

   - Soil moisture monitoring
   - Weather integration
   - Automated watering schedules

4. **Inventory Management Service**

   - Seeds, fertilizers, pesticides tracking
   - Equipment maintenance schedules
   - Supplies ordering

5. **Weather Service**

   - Real-time weather data
   - Historical weather patterns
   - Forecasting integration

6. **IoT Sensor Service**

   - Sensor data collection
   - Real-time monitoring
   - Alert generation

7. **Analytics & Reporting Service**

   - Dashboard data aggregation
   - Historical trends
   - Financial reporting

8. **User Management Service**

   - Authentication & Authorization
   - Role-based access control
   - Multi-tenancy support

9. **Notification Service**

   - Email notifications
   - SMS alerts
   - Push notifications

10. **Task Management Service**
    - Daily task scheduling
    - Worker assignment
    - Task completion tracking

## Sample Implementation Roadmap

### Phase 1: Foundation (Basic CRUD)

- Implement User Management with C# Minimal API + PostgreSQL
- Use Clean Architecture structure
- Deploy to Azure with Bicep
- Document learnings

### Phase 2: Different Stack

- Implement Farm Management with Express.js + MongoDB
- Add Docker support
- Deploy to AWS
- Compare with C# experience

### Phase 3: Mobile Integration

- Build mobile app with React Native
- Connect to existing APIs
- Add offline support

### Phase 4: Advanced Patterns

- Implement CQRS for Crop Monitoring (FastAPI + Python)
- Add Event Sourcing
- Use RabbitMQ for events

### Phase 5: Real-time Features

- Build IoT Sensor Service with Go
- Implement gRPC for sensor communication
- Add WebSocket for real-time dashboards

### Phase 6: AI Integration

- Add AI-powered disease detection
- Implement RAG for agricultural knowledge base
- Build MCP server for farm data access

## 📖 Learning Documentation Structure

For each service/stack, document:

- Setup & installation steps
- Key learnings & gotchas
- Performance observations
- Comparison with other stacks
- Code snippets & patterns
- Docker configuration notes
- Deployment challenges & solutions
- Testing strategies used

## 🎓 Optimized Learning Strategy

### 1. **Progressive Complexity Approach** (Realistic Timeline)

Start simple, layer in complexity. **Each phase = 4-6 weeks** at sustainable pace:

- **Phase 1 (Month 1-1.5):** Basic CRUD with REST API (C# Minimal API) + Simple HTML/CSS
  - ~40-60 hours total
  - Perfect for 1-2 hours on weekdays + weekend sessions
- **Phase 2 (Month 2-3):** Add database patterns (Repository, Unit of Work) + Tailwind CSS
  - Build on existing service
  - Focus on patterns, not speed
- **Phase 3 (Month 3.5-5):** Different language (Express.js or FastAPI) + Responsive design
  - Compare with Phase 1 service
  - Document differences
- **Phase 4 (Month 5.5-7):** Event-driven patterns (RabbitMQ integration)
  - Connect your two services
  - Learn async communication
- **Phase 5 (Month 7.5-9):** Advanced patterns (CQRS, Event Sourcing)
  - Ambitious but doable
  - Can take longer if needed
- **Phase 6 (Month 9.5-11):** gRPC & real-time features
  - Build performance-critical service
- **Phase 7 (Month 11+):** AI integration & MCP servers
  - Apply everything learned
  - Portfolio-ready project

**Total Timeline: 12-18 months** to complete all phases. That's realistic and sustainable.

### 2. **Monthly Themes** (Alternative to Progressive)

Focus on one aspect per month across multiple stacks (realistic for part-time learning):

- **Month 1:** "Auth Month" - Implement authentication in 2-3 languages (C#, Node.js)
- **Month 2:** "Database Month" - Try PostgreSQL deeply, then MongoDB
- **Month 3:** "API Month" - Build REST thoroughly, explore gRPC basics
- **Month 4:** "CSS/Styling Month" - Master Tailwind, compare with vanilla CSS
- **Month 5:** "Events Month" - RabbitMQ deep dive, try one other (Kafka or Azure Service Bus)
- **Month 6:** "Testing Month" - Unit, Integration tests across stacks
- **Month 7:** "Cloud Month" - Azure deployment end-to-end
- **Month 8:** "AWS Month" - Repeat deployment on AWS, compare

**Each month:** 40-50 hours = depth instead of breadth. Quality learning.

### 3. **Learning Clusters** (Group Related Technologies)

**Cluster A: Microsoft Ecosystem**

- C# (Minimal API, Web API, Blazor, MAUI)
- Azure (Bicep, App Service, Functions, CosmosDB)
- Entity Framework Core
- Azure DevOps / GitHub Actions

**Cluster B: JavaScript/TypeScript Full Stack**

- Node.js (Express, NestJS)
- React & React Native
- Next.js
- Tailwind CSS & CSS fundamentals
- GraphQL
- MongoDB
- AWS deployment

**Cluster C: Python Data & AI**

- FastAPI
- Django/Flask
- AI/ML libraries
- RAG & vector databases
- pytest & BDD

**Cluster D: Systems Programming**

- Go (APIs, gRPC, microservices)
- Rust (performance-critical services)
- Comparative benchmarking

**Cluster E: Mobile Native**

- Swift (iOS + SwiftUI)
- Kotlin/Java (Android)
- Platform-specific features

### 4. **Cross-Cutting Concerns Checklist**

Apply these to EVERY service you build:

- ✅ Logging (structured logging)
- ✅ Error handling & retries
- ✅ Health checks
- ✅ Metrics/monitoring
- ✅ API documentation (Swagger/OpenAPI)
- ✅ Dockerization
- ✅ Unit tests (minimum 70% coverage)
- ✅ Integration tests
- ✅ CI/CD pipeline
- ✅ Environment configuration
- ✅ Security (auth, rate limiting, input validation)

### 5. **Deliberate Practice Techniques**

- **Code Katas:** Rebuild the same service in different stacks (e.g., User Management in C#, then Go, then Rust)
- **Comparison Matrix:** After each implementation, fill out a comparison chart (speed, ease of use, ecosystem, etc.)
- **Teach Back:** Write blog posts or create videos explaining what you learned
- **Pair Programming:** Alternate between stacks with AI assistance for learning
- **Code Reviews:** Review your own code after 1 week to see what you'd do differently

### 6. **Certification Alignment**

Map services to certification topics:

- **AZ-204 prep:** Use Azure services (App Service, Functions, CosmosDB, Service Bus)
- **AWS Developer prep:** Parallel implementation with AWS services (Lambda, DynamoDB, SQS)
- **AI-102 prep:** Build AI features (disease detection, yield prediction, chatbot)

### 7. **Time-Boxing Strategy** (Adjusted for Part-Time)

- **4-6 weeks per service** - Allows for sustainable learning pace
- **1-2 weeks per technology switch** - Setup, hello world, basic CRUD
- **3-4 weeks for complex patterns** - CQRS, Event Sourcing, gRPC deserve time
- **Monthly retrospective** - What worked? What didn't? Adjust approach
- **No guilt rule** - Some weeks you'll do 2 hours, others 15 hours. Both are fine.

### 8. **Knowledge Retention Tools**

- **Anki Flashcards:** Create flashcards for syntax, concepts, commands
- **Cheat Sheet Repository:** One Markdown file per tech with quick references
- **Decision Log:** Document why you chose certain approaches
- **Error Journal:** Catalog errors encountered and solutions
- **Architecture Decision Records (ADRs):** Lightweight docs for architectural choices

### 9. **Realistic Daily/Weekly Rhythm**

**Weekday Options** (pick what fits YOUR schedule):

- **Early Bird (6:00-7:30 AM):** 1-1.5 hours before work, fresh mind for coding
- **Lunch Learner (12:00-1:00 PM):** Watch tutorials, read docs, review code
- **Evening Coder (8:00-10:00 PM):** 1-2 hours after family time
- **Mixed:** 30 min morning + 30 min evening

**Weekend Structure** (choose 1-2 days only):

- **Saturday OR Sunday morning (8:00-12:00):** Deep work session (4 hours)
- **Weekend afternoon (2:00-5:00 PM):** Lighter session (3 hours)
- **One full day OFF:** No coding, no learning. Family/rest/hobbies.

**Weekly Focus Areas**:

- **Mon-Tue:** Active coding (build features)
- **Wed-Thu:** Learning (tutorials, docs, experimenting)
- **Fri:** Light (review, documentation, cheat sheets)
- **Sat/Sun (1 day):** Big tasks (new service, deployment, integration)
- **Sat/Sun (1 day):** Complete break

**Monthly Rhythm**:

- **Week 1:** New concept introduction
- **Week 2:** Practice and experimentation
- **Week 3:** Build something real
- **Week 4:** Polish, document, retrospective

### 10. **Metrics to Track Progress**

- Services completed per stack
- Test coverage percentage
- Deployment success rate
- Lines of documentation written
- Technologies mastered vs. familiar vs. beginner
- Certification progress
- Performance benchmarks across stacks

### 11. **CSS/Styling Learning Path** (Slow & Deliberate)

Since you're slightly familiar but want to go slow and build mastery:

**Phase 1: CSS Fundamentals (Week 1-2)**

- Pure CSS layouts (no frameworks)
- Flexbox deep dive - build 5 different layouts
- CSS Grid deep dive - recreate common patterns
- Box model, positioning, specificity
- Build agricultural dashboard with vanilla CSS only

**Phase 2: Responsive Design (Week 3)**

- Media queries and breakpoints
- Mobile-first approach
- Responsive typography
- Fluid layouts and clamp()
- Make your dashboard fully responsive

**Phase 3: Tailwind CSS Introduction (Week 4-5)**

- Setup and configuration
- Utility-first concepts
- Rebuild your dashboard in Tailwind
- Compare: time spent, bundle size, maintainability
- Custom themes and design tokens

**Phase 4: Advanced CSS (Week 6-7)**

- CSS animations and transitions
- CSS custom properties (variables)
- Dark mode implementation
- Accessibility (focus states, screen readers)
- Performance optimization (critical CSS, purging)

**Phase 5: CSS-in-JS Exploration (Week 8)**

- styled-components with React
- Emotion
- CSS Modules
- Compare all approaches with decision matrix

**Phase 6: Production Polish (Week 9-10)**

- Cross-browser compatibility
- CSS architecture (BEM, SMACSS)
- Design system creation
- Component library with Storybook
- Performance auditing with Lighthouse

**CSS Practice Projects** (Build each 3 times: vanilla CSS, Tailwind, CSS-in-JS):

1. **Login/Auth Pages** - Form styling, validation states
2. **Dashboard** - Complex layouts, charts, cards
3. **Data Tables** - Sorting, filtering, pagination UI
4. **Mobile Navigation** - Hamburger menus, slide-outs
5. **Farm Plot Visualizer** - Grid layouts, maps, overlays
6. **Settings Panel** - Tabs, accordions, forms
7. **Notification System** - Toasts, badges, animations
8. **Weather Widget** - Icons, gradients, animations

**CSS Deliberate Practice**:

- **Daily:** Spend 30 min on CSS challenges (CSSBattle, Frontend Mentor)
- **Weekly:** Rebuild a real website's layout
- **Document:** Screenshot before/after, note what you learned
- **Cheat Sheet:** Collect common patterns (centering, layouts, animations)

## 🗂️ Suggested Tech Stack Combinations

### Combination 1: Microsoft Stack

- C# Minimal API
- Blazor (frontend) + CSS Modules
- SQL Server / PostgreSQL
- Azure (Bicep)
- gRPC
- xUnit testing

### Combination 2: JavaScript/Node Stack

- Express.js
- React (frontend) + Tailwind CSS
- MongoDB
- AWS
- GraphQL
- Jest testing

### Combination 3: Python Stack

- FastAPI
- Vue (frontend) + Tailwind CSS
- PostgreSQL
- Azure
- REST API
- pytest testing

### Combination 4: Polyglot Microservices

- Go (IoT Service) - gRPC
- Rust (Analytics Service) - REST
- Python (AI Service) - REST/gRPC
- C# (User Management) - REST
- Java (Inventory) - REST
- All communicating via RabbitMQ/Kafka events

## 🎯 Quick Start Recommendations

### Option A: Steady Sustainable Path (Recommended for Full-Time Job + Family)

**Timeline: 12-15 months | ~40-50 hours/month**

1. **Month 1-2:** Start with **C# Minimal API** + **vanilla CSS** (go slow, learn fundamentals)
2. **Month 2-3:** Add **Docker** and deploy to **Azure** with Bicep
3. **Month 4-5:** Build simple UI with **Tailwind CSS** (compare with vanilla)
4. **Month 6-7:** Switch to **FastAPI** (Python) for second service
5. **Month 8-9:** Build **React** frontend connecting both services
6. **Month 10-11:** Introduce **RabbitMQ** for async communication
7. **Month 12-13:** Add **AI features** with Azure OpenAI
8. **Month 14-15:** Build **React Native** mobile app (optional if excited)

**Result:** 3-4 stacks, full-stack experience, CSS mastery, AI integration, portfolio-ready
**Reality check:** You'll have breaks, busy work periods, family events - that's life!

### Option B: Deep Dive Comparison (For Patient Learners)

**Timeline: 8-10 months | Focus on mastery over breadth**

1. **Months 1-2:** Build User Management service in C# Minimal API
2. **Months 3-4:** Rebuild same service in Express.js
3. **Months 5-6:** Rebuild again in FastAPI
4. **Month 7:** Compare performance, DX, ecosystem (detailed documentation)
5. **Month 8:** Choose best 2 stacks for next services
6. **Months 9-10:** Build 2 new services with chosen stacks

**Result:** Deep understanding of trade-offs, expert-level knowledge of 3 stacks
**Perfect for:** People who prefer depth and want to make informed career decisions

### Option C: Certification-Driven Path (Career Advancement Focus)

**Timeline: 10-12 months | Aligned with AZ-204 or AWS Developer Associate**

1. **Months 1-3:** Build 2 services using Azure services (prep for AZ-204)
2. **Month 4:** Take AZ-204 certification exam
3. **Months 5-7:** Build 2 parallel services using AWS (prep for AWS Developer)
4. **Month 8:** Take AWS Developer Associate exam
5. **Months 9-10:** Compare platforms, document decision matrices
6. **Months 11-12:** Build hybrid/multi-cloud architecture

**Result:** 2 certifications + hands-on experience + cloud expertise + salary bump potential
**Bonus:** Certifications create external accountability and deadlines

### Option D: Minimal Viable Learning (Ultra-Sustainable)

**Timeline: 6-8 months | ~20-30 hours/month**

Perfect for when life is extra busy:

1. **Months 1-3:** One service, one stack (C# + PostgreSQL + Docker)
2. **Months 4-6:** One frontend (React + Tailwind)
3. **Months 7-8:** Deploy everything to cloud (Azure OR AWS)

**Result:** Complete full-stack project, deployable portfolio piece
**Reality:** Sometimes this is all you can do, and that's 100% okay!

## 📋 Minimum Viable Service Template

Every service should have:

```
/src
  /domain          # Business logic (stack-agnostic)
  /application     # Use cases
  /infrastructure  # DB, external services
  /api            # Controllers/handlers
/tests
  /unit
  /integration
/docker
  Dockerfile
  docker-compose.yml
/.github
  /workflows
    ci.yml
README.md         # Setup, API docs, learnings
.env.example
```

## 🚀 Success Metrics (Choose Your Own Level)

### 🥉 Bronze Level (6-8 months, realistic minimum)

- [ ] 2-3 services built across 2 tech stacks
- [ ] All services containerized with Docker
- [ ] Deployed to 1 cloud platform (Azure OR AWS)
- [ ] Basic frontend built (React/Vue with Tailwind)
- [ ] Documentation for each service created
- [ ] GitHub repository showcasing work

### 🥈 Silver Level (12-15 months, solid achievement)

- [ ] 5-6 services built across 3-4 tech stacks
- [ ] All services containerized
- [ ] Deployed to 2 cloud platforms (Azure AND AWS)
- [ ] 1 mobile app built (React Native OR Swift)
- [ ] AI feature integrated (RAG, Azure OpenAI, or MCP server)
- [ ] 1 certification obtained (AZ-204, AWS Developer, or AI-102)
- [ ] Comprehensive cheat sheets for each tech
- [ ] Portfolio website showcasing projects

### 🥇 Gold Level (18-24 months, exceptional for part-time)

- [ ] 8-10 services built across 5+ tech stacks
- [ ] All services containerized and orchestrated (Docker Compose/Kubernetes basics)
- [ ] Multi-cloud deployment with comparison docs
- [ ] 1-2 mobile apps built
- [ ] Multiple AI features (RAG, agents, MCP servers)
- [ ] 2+ certifications obtained
- [ ] Published blog posts or tutorials about learnings
- [ ] Complete portfolio with architecture diagrams
- [ ] GitHub contributions and open source involvement

### 💎 Platinum Level (24+ months, mastery achievement)

- [ ] 12+ services in polyglot microservices architecture
- [ ] Production-grade setup (monitoring, logging, CI/CD)
- [ ] Deployed across Azure, AWS, and experimented with GCP
- [ ] Multiple mobile apps (iOS + Android native experience)
- [ ] AI-powered features across multiple services
- [ ] 3+ certifications (cloud + AI)
- [ ] Active tech blog or YouTube channel
- [ ] Speaking at meetups or conferences
- [ ] Mentoring others or teaching

## 🎯 The Real Success Metric

**Consistency over intensity.** If you code 1 hour per week for 2 years, you'll learn more than coding 20 hours/week for 2 months and burning out.

**Life balance maintained.** Your family is happy, your job performance is good, and you're still excited about learning = TRUE SUCCESS.

## 🛡️ Sustainability & Burnout Prevention

### Warning Signs to Watch For:

- ❌ Feeling guilty when you don't code
- ❌ Sacrificing sleep to meet self-imposed deadlines
- ❌ Family complaining about your absence
- ❌ Work performance suffering
- ❌ No longer enjoying the learning process
- ❌ Comparing yourself to full-time students or bootcamp grads

### Healthy Practices:

- ✅ Schedule learning time like meetings (but okay to cancel)
- ✅ Celebrate small wins (finished a tutorial counts!)
- ✅ Take full weeks off when life gets busy
- ✅ Join communities for accountability (not comparison)
- ✅ Remember why you started (career growth, curiosity, portfolio)
- ✅ Track hours to see real progress over months

### Monthly Check-in Questions:

1. Am I still enjoying this?
2. Is my family okay with the time I'm spending?
3. Am I learning, or just "going through motions"?
4. Do I need a break this month?
5. Should I adjust my goals?

### When Life Happens (And It Will):

- **Busy work period?** Take 2-4 weeks off, come back refreshed
- **Family emergency?** Learning can wait, no guilt needed
- **Lost motivation?** Switch to a different tech or project
- **Feeling overwhelmed?** Reduce scope, focus on ONE thing
- **Vacation coming?** Plan a learning break before/after

### The 3-Month Rule:

If you haven't coded for 3 months straight, don't quit - just start smaller:

- Week 1: 30 minutes, 2 days
- Week 2: 30 minutes, 3 days
- Week 3: 1 hour, 3 days
- Week 4: Back to normal rhythm

**Remember: This is a multi-year journey. Breaks are part of the process.**
