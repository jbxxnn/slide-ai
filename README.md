# Slide AI - Instagram Automation Platform

Transform your Instagram engagement with AI-powered automation that converts comments into conversations and leads into customers.

## 🚀 What is Slide AI?

Slide AI is a smart Instagram automation platform that combines trigger-based messaging with AI-powered conversation continuation. When someone comments on your post with a trigger word, they automatically receive a DM. But here's where it gets interesting - if they reply, our AI steps in and acts like a trained sales representative, handling objections, answering questions, and guiding them toward conversion.

### ✨ Key Features

**🎯 Smart Automation**
- Set custom trigger words/phrases for your posts
- Automatic DM sending when users comment triggers
- Seamless Instagram API integration

**🤖 AI-Powered Sales Assistant (Premium)**
- Conversational AI that responds like a human sales rep
- Handles product questions, pricing inquiries, and objections
- Guided conversion paths to bookings, purchases, or lead capture
- Customizable response styles (formal, casual, emoji-heavy)

**📚 Business Intelligence**
- Upload your FAQs, product descriptions, and pricing
- AI learns from your business knowledge using RAG technology
- Pre-built templates for common business types
- Live conversation monitoring with human intervention options

**📊 Analytics & Insights**
- Track conversion rates and response rates
- Monitor AI performance vs. human escalation
- Measure ROI and cost per lead
- Real-time engagement quality metrics

## 💰 Pricing

- **Free Tier**: Basic trigger → DM automation
- **Premium**: $9.99/month - Full AI conversation continuation

## 🛠️ Tech Stack

- **Frontend**: Next.js 14 with TypeScript
- **Backend**: Supabase (PostgreSQL, Auth, Real-time)
- **AI**: OpenAI Assistants API with RAG implementation
- **Integration**: Instagram Graph API
- **Styling**: Tailwind CSS
- **Deployment**: Vercel-ready

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- Instagram Business Account
- OpenAI API key (for AI features)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Slide-ai.git
   cd Slide-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   
   Configure your `.env.local`:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
   OPENAI_API_KEY=your_openai_api_key
   INSTAGRAM_APP_ID=your_instagram_app_id
   INSTAGRAM_APP_SECRET=your_instagram_app_secret
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📖 Usage Guide

### 1. Connect Your Instagram Account
- Link your Instagram Business account through our secure OAuth flow
- Grant necessary permissions for automation

### 2. Set Up Your First Automation
- Choose a post to monitor
- Define trigger words (e.g., "DEMO", "PRICING", "START")
- Write your initial DM message

### 3. Configure AI Assistant (Premium)
- Upload your business knowledge (FAQs, pricing, product info)
- Choose from pre-built templates or create custom ones
- Set your preferred response style and tone

### 4. Launch and Monitor
- Activate your automation
- Monitor conversations in real-time
- Step in when needed or let AI handle the conversation

## 🎯 Example Use Cases

### E-commerce Store
**Post**: "Comment 'SHOP' to see our latest collection!"
**Trigger**: "SHOP"
**Auto DM**: "Hey! 👋 Check out our new arrivals here: [link]"
**AI Response to "How much is shipping?"**: "Free shipping on orders over $50! Standard shipping is $5.99. Want to see what's in your cart?"

### Service Business
**Post**: "Comment 'BOOK' for a free consultation!"
**Trigger**: "BOOK"
**Auto DM**: "Thanks for your interest! When's the best time for a 15-min call?"
**AI Response to "What do you charge?"**: "Our consultation is completely free! After that, packages start at $299/month. What specific challenges are you facing?"

## 🔧 Development

### Project Structure
```
Slide-ai/
├── app/                    # Next.js app directory
│   ├── auth/              # Authentication pages
│   ├── dashboard/         # Main application
│   └── api/               # API routes
├── components/            # Reusable UI components
├── lib/                   # Utilities and configurations
│   ├── supabase/         # Supabase client setup
│   └── ai/               # AI integration logic
└── types/                # TypeScript type definitions
```

### Key Components

- **Instagram Integration**: Direct API connection for automation
- **AI Conversation Engine**: RAG-based response generation
- **Real-time Monitoring**: Live conversation tracking
- **Analytics Dashboard**: Performance metrics and insights

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Documentation**: [docs.Slide.ai](https://docs.Slide.ai)
- **Email**: support@Slide.ai
- **Discord**: [Join our community](https://discord.gg/Slide)

## 🚀 Roadmap

- [ ] TikTok integration
- [ ] Twitter/X automation
- [ ] Advanced AI training options
- [ ] Team collaboration features
- [ ] Advanced analytics and reporting
- [ ] Mobile app

---

**Built with ❤️ for social media entrepreneurs**
#   s l i d e - a i  
 