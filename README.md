# Academic Matchmaker - n8n Automation

An intelligent academic opportunity matching system powered by n8n workflow automation. This system automatically matches research opportunities and academic posts with relevant users based on their interests and profiles using advanced AI embeddings and semantic similarity.

## 🎯 Overview

The Academic Matchmaker workflow automatically processes new academic opportunities and intelligently matches them with users who have relevant interests. It uses AI-powered embeddings to understand content and user profiles, then sends personalized email notifications to matched users.

## ✨ Features

- **Automated Scheduling**: Runs every 5 minutes to check for new opportunities
- **AI-Powered Matching**: Uses Jina AI embeddings for semantic understanding
- **Smart Filtering**: Only matches users above a 25% similarity threshold
- **Personalized Emails**: Sends beautifully formatted HTML emails with opportunity details
- **Batch Processing**: Efficiently handles large volumes of users and posts
- **Scalable Architecture**: Built to handle production workloads

## 🚀 How It Works

1. **Data Collection**: Fetches new posts and user profiles from Firestore
2. **AI Embedding**: Generates vector embeddings for posts and user interests
3. **Semantic Matching**: Calculates similarity scores using cosine similarity
4. **Smart Filtering**: Identifies matches above the threshold
5. **Email Delivery**: Sends personalized notifications to matched users

## 📊 Demo

### Workflow Overview

![Workflow Diagram](images/workflow-diagram.png)

*Add your n8n workflow screenshot here*

### Email Preview

![Email Preview](images/email-preview.png)

*Add your email notification preview here*

### Matching Dashboard

![Matching Dashboard](images/dashboard.png)

*Add your matching dashboard or analytics view here*

## 🛠️ Technology Stack

- **n8n**: Workflow automation platform
- **Jina AI**: Embedding model for semantic understanding
- **Google Firestore**: Database for posts and user data
- **Gmail API**: Email delivery service
- **JavaScript/Code Nodes**: Custom logic and processing

## 📝 Workflow File

Import the `ai auto.json` file into your n8n instance to get started with this automation.

## 🔧 Setup

1. Import the workflow JSON file into n8n
2. Configure your Firestore credentials
3. Set up Gmail OAuth2 authentication
4. Configure Jina AI API key
5. Activate the workflow

## 📧 Email Features

- Professional HTML formatting
- Personalized greeting with user's first name
- Opportunity details with clear formatting
- Match score display
- Clear call-to-action steps

## 📈 Future Enhancements

- Customizable matching thresholds
- User preference settings
- Analytics dashboard
- Multi-language support
- Advanced filtering options

---

**Built with ❤️ using n8n automation**

