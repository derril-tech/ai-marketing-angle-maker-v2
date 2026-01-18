# 🎯 AI Marketing Angle Maker
**with AutoGen Multi-Agent System**

> **Turn live Google Trends signals into jaw-dropping marketing angles in seconds. A swarm of AI agents researches trends, analyzes audience intent, and crafts on-brand hooks, headlines, and copy variants for your campaigns.** ⚡

---

## ✨ Features

### 🎯 **Core Functionality**
- 🤖 **Multi-Agent System** - Watch Researcher and Copywriter agents collaborate in real-time
- 📈 **Google Trends Integration** - Real-time trend analysis with direction, change percentages, and related queries
- 🎨 **Ranked Marketing Angles** - Receive 3-5 distinct angles, each scored and ranked by effectiveness
- ✍️ **Copy-Ready Output** - Get hooks, headlines, and body copy ready to paste into your campaigns
- 📊 **Trend Context** - See trend direction, change percentages, and related queries for each angle
- 🔄 **AI-Powered Refinement** - Refine any angle with custom instructions using OpenAI
- 💾 **Session History** - Review past angle generation sessions with full conversation history

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism, gradients, video backgrounds, micro-animations
- 🌙 **Dark/Light Mode** - Full theme support with smooth transitions and theme toggle
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- ♿ **Accessible** - WCAG AA compliant with keyboard navigation
- 🎯 **Intuitive Interface** - Clean, user-friendly design with clear visual hierarchy

### 📊 **Playground Features**
- 🎮 **Real-Time Agent Activity** - Watch agents work with live progress updates
- 📝 **Topic Input** - Simple textarea for entering marketing topics or keywords
- 🏆 **Top Angle Display** - Featured top-ranked angle with full details
- 📋 **Angle Variants** - View all generated angles with scores and reasoning
- 📤 **Export Options** - Export angles as JSON, Markdown, or CSV
- 📋 **Copy Formats** - Copy as Markdown, HTML, or plain text
- 🔍 **Angle Comparison** - Side-by-side comparison view for multiple angles
- ⭐ **Favorites** - Bookmark your favorite angles for quick access

### 🚀 **Advanced Features**
- 🎯 **Structured Output** - Each angle includes title, hook, headline, body, score, reasoning, and trend summary
- 📊 **Trend Analysis** - Detailed trend direction, magnitude, and related query insights
- 🔄 **Background Processing** - Job-based system with polling for real-time updates
- 💾 **Persistent History** - All sessions saved to database with full conversation context
- 🎚️ **Customizable** - Refine angles with specific instructions to match your brand voice
- 🔍 **Health Monitoring** - OpenAI API health check endpoint for connectivity verification

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **AutoGen** - Multi-agent orchestration framework
- **OpenAI API** - GPT-4.1-mini for angle generation and refinement
- **Python 3.11+** - Latest features and performance

### **Frontend** ⚛️
- **Next.js 15.1** - React 19 with App Router
- **Tailwind CSS** - Utility-first styling
- **shadcn/ui** - Beautiful component library
- **Lucide Icons** - Modern icon set

### **Database & Cache** 💾
- **Supabase** - PostgreSQL with real-time capabilities (schema: `angle_maker`)
- **Upstash Redis** - Serverless job queue & caching (prefix: `angle_maker`)

### **External APIs** 🔌
- **Google Trends** - Real-time trend data via SerpAPI
- **OpenAI** - GPT-4.1-mini for AI-powered angle generation

### **Deployment** 🚀
- **Railway** - Automated deployment platform (web + api services)
- **Vercel** - Alternative deployment option for frontend

---


### 🏠 Homepage
![Homepage](public/demo/homepage.png)
*Beautiful landing page with video background, hero section, and clear value proposition*

### 🎮 Playground
![Playground](public/demo/playground.png)
*Interactive interface for angle generation with real-time agent activity*

### 📊 Dashboard
![Dashboard](public/demo/dashboard.png)
*Comprehensive dashboard with session history and metrics*

---

## 📖 User Guide

### 🎮 Using the Playground

1. **Enter Your Topic**
   - Type a marketing topic, keyword, or product description
   - Examples: *"AI copywriting tools"*, *"Remote work software"*, *"No-code SaaS launch"*

2. **Generate Angles**
   - Click **"Generate Angles"** to start the multi-agent process
   - Watch the Researcher agent analyze Google Trends data
   - See the Copywriter agent craft unique marketing angles

3. **Review Results**
   - **Top Angle** - Featured at the top with full details
   - **All Angles** - Scroll to see all 3-5 generated angles
   - Each angle includes:
     - Title, Hook, Headline, Body copy
     - Score (0.0-1.0) indicating effectiveness
     - Reasoning explaining why it works
     - Trend summary with direction and change percentage

4. **Use Your Angles**
   - **Copy** - One-click copy to clipboard
   - **Export** - Download as JSON, Markdown, or CSV
   - **Compare** - Side-by-side comparison view
   - **Refine** - Use AI to refine angles with custom instructions
   - **Favorite** - Bookmark angles you love

### 📊 Using the Dashboard

1. **View Session History**
   - See all past angle generation sessions
   - Review conversation history
   - Access previous angles

2. **Monitor Activity**
   - Track total sessions
   - View recent activity
   - Search and filter sessions

### 🔧 Refining Angles

1. **Select an Angle**
   - Click on any generated angle
   - Open the refinement modal

2. **Add Instructions**
   - Provide specific refinement instructions
   - Examples:
     - *"Make it more urgent and action-oriented"*
     - *"Focus on the B2B audience"*
     - *"Use a more casual, friendly tone"*

3. **Get Refined Angle**
   - AI refines the angle based on your instructions
   - See what changed and why
   - Copy or export the refined version

---

## 🎨 Customization

### Theme Options
- ☀️ **Light Mode** - Clean, bright interface
- 🌙 **Dark Mode** - Easy on the eyes (default)
- 🎨 **Theme Toggle** - Switch between modes anytime

### Export Formats
- **JSON** - Structured data for programmatic use
- **Markdown** - Formatted text for documentation
- **CSV** - Spreadsheet-friendly format

### Copy Formats
- **Markdown** - With formatting preserved
- **HTML** - Ready for web content
- **Plain Text** - Simple, unformatted text

---

## 👨‍💻 Creator

**Created by Derril Filemon**

---

## 🙏 Acknowledgments

- **OpenAI** - For GPT-4.1-mini API
- **AutoGen** - For multi-agent orchestration framework
- **Supabase** - For database & auth
- **Upstash** - For Redis caching
- **Railway** - For deployment platform
- **Vercel** - For Next.js hosting
- **shadcn/ui** - For beautiful components
- **SerpAPI** - For Google Trends data

---

<div align="center">

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
