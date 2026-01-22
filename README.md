# GDG-chaitanya

# PS-1
# TASK-1
This project implements an end-to-end financial time series forecasting engine using Keras (TensorFlow) and LSTM neural networks, designed specifically to model uncertainty and volatility in market data rather than producing a single point estimate.

The system trains on historical stock data and produces:
- Historical trend visualization
- 7-day forward forecasts
- Shaded confidence intervals (quantile-based)
- Accuracy metrics (RMSE, MAE)

# TASK-2
# done before easy method
This project implements a chat-bot using libraries like PyPDFLoader RecursiveCharacterTextSplitter,FAISS,HuggingFaceEmbeddings,ChatGroq,ConversationalRetrievalChain,ConversationBufferMemory,Tool, initialize_agent,ChatMessageHistory,MessagesPlaceholder . Often called as RAG(retrieval augmented generation)
# implemented for this task
A natural-language financial chatbot that explains stock movements by combining market data, news retrieval (RAG), and LLM-based reasoning.
- Identifies companies and tickers from user queries
- Analyzes price trends and drops
- Retrieves relevant financial news
- Explains *why* stocks moved and *when* trends started
 Example Questions
- “Why did Apple stock drop?”
- “When did Microsoft go up?”
 Tech Stack
- Python
- LangChain
- OpenAI / LLM API
- yfinance
- FAISS
- newspaper3k

