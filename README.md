# LLM-course

1. Ollama might be more suited for users looking for structured and detailed content extraction from a website.
2. Gemini seems better at offering quick and streamlined summaries, especially for users wanting a brief professional overview.

## Limitations of Frontier Models
1. Specialized domain: Most are not Phd level models, and are not trained on a wide range of topics.
2. Limited context: They may not be able to provide detailed information on a topic.
3. Recent updates: They may not be able to provide the most up-to-date information.
4. Confidentiality: They may not be able to provide information on sensitive topics.

# Rise of Transformers
1. Google published "Attention is All You Need" in 2017, introducing the Transformer architecture.
2. 2018 - GPT1
3. 2019 - GPT2
4. 2020 - GPT3
5. 2022- RLHF and ChatGPT
6. 2023 -GPT4
7. 2024- GPT4o

## Topic: Context Window
- Max number of tokens that model can consider when generating output.  
- Include original i/p text, prompt, subsequent text, etc.
- it governs how well model can remember and generate coherent text.

## 1st Project: Web Scraping
- using BeautifulSoup library
- llm used = Ollama, Gemini

## Business Problem:
Creating a product that can generate marketing broucher about a company (for clients, investors, rectuitment)
Tech (Gemini API, one shot prompting, stream result)