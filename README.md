#  LLM Evaluation Platform

A sleek and modern platform for comparing responses from different Large Language Models (LLMs) in real-time. Test prompts across multiple models and analyze their performance metrics side by side.



##  Features

- **Multi-Model Comparison**: Test prompts simultaneously across:
  - GPT-4 (OpenAI's most advanced model)
  - GPT-3.5 (FastAI)
  - Mixtral (via Groq)

- **Real-time Metrics**:
  - Accuracy measurements
  - Response relevancy scoring
  - Response time tracking
  - Performance analytics

- **Interactive Dashboard**:
  - Clean, modern UI
  - Real-time response generation
  - Performance visualization
  - Historical data tracking

- **Usability Features**:
  - Enter key support for quick evaluation
  - Responsive design
  - Easy-to-read metrics
  - One-click analytics access

##  Getting Started

### Prerequisites

```bash
- Node.js (v14 or higher)
- NPM or Yarn
- OpenAI API key
- Groq API key
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/aneezahere/llm-evaluation.git
cd llm-evaluation-platform
```

2. Install dependencies:
```bash
npm install
```

3. Set up your environment variables:
```bash
cp .env.example .env
```

Add your API keys to the `.env` file:
```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
DATABASE_URL=your_database_url
```

4. Set up the database:
```bash
npx prisma generate
npx prisma db push
```

5. Run the development server:
```bash
npm run dev
```

Visit `http://localhost:3000` to start using the platform!

## 💡 Use Cases

- **Research & Development**: Compare model outputs and performance metrics
- **Model Selection**: Make informed decisions about which LLM best suits your needs
- **Quality Assurance**: Test prompt effectiveness across different models
- **Performance Monitoring**: Track response times and accuracy metrics
- **Cost Optimization**: Compare model performance to make cost-effective choices

## 📊 Analytics

The platform provides comprehensive analytics:
- Performance comparisons across models
- Response time tracking
- Accuracy metrics
- Usage statistics

## 🛠️ Built With

- [Next.js](https://nextjs.org/) - React Framework
- [OpenAI API](https://openai.com/api/) - GPT-4 and GPT-3.5 integration
- [Groq SDK](https://groq.com/) - Mixtral model access
- [Prisma](https://www.prisma.io/) - Database ORM
- [Recharts](https://recharts.org/) - Analytics visualization


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments

- OpenAI for their powerful GPT models
- Groq for their lightning-fast inference platform
- The amazing open-source community



