---
# 🧠 Sentiment Analysis Tool with AI Summary & Suggestions

An intelligent, user-friendly Sentiment Analysis GUI application built with Python. This tool allows users to load text data (preloaded, CSV, or manual), analyze sentiments, and receive **AI-generated summaries and suggestions** for better interpretation and decision-making.
---
## 📌 Key Features

- 📂 **Flexible Data Input**:
  - Preloaded sample datasets
  - Upload your own CSV file
  - Manual text input
- ⚡ **One-Click Analysis**:
  - Just select your input method and click **Load Data** to start analysis.
- 📊 **Detailed Visualizations**:
  - Sentiment classification (Positive, Neutral, Negative)
  - Word cloud of frequently used terms
  - Bar graph showing sentiment distribution
- 🤖 **AI-Powered Summaries & Suggestions**:
  - Automatically generates a concise summary of overall sentiment
  - Offers suggestions for improvement or actions based on detected sentiment patterns
- 💡 **Beginner-Friendly GUI**:
  - Built with `tkinter`, offering a clean and intuitive interface.
---
## 🧠 How It Works

1. Choose an input method:
   - Preloaded dataset
   - Upload a CSV file
   - Enter custom text manually
2. Click **Load Data**
3. View:
   - Sentiment breakdown
   - Word cloud
   - Graphs
   - **AI summary and recommendations**
---
## 📄 Software Requirements Specification (SRS)

A full **SRS document** was created to formally define:

- **Project purpose & goals**
- **Design architecture** (frontend, backend, visualization engine)
- **Supported data types and sources**
- **UI design specifications** (with screen-by-screen layout)
- **Risk and performance considerations**
- **Assumptions, constraints, and user expectations**

📘 The SRS helps guide structured development and ensures the app is scalable, user-friendly, and applicable for real-world use cases like:
- HR teams analyzing work-life balance
- Businesses reviewing customer satisfaction
- Researchers running sentiment analysis on surveys

> _You can find this document in `SRS.pdf` included in the project repository._

---
## 💻 Tech Stack

- **Python 3.10+**
- `Tkinter` – GUI framework
- `Pandas` – Data processing
- `TextBlob` – NLP and sentiment analysis
- `WordCloud` – Word cloud generation
- `Matplotlib` – Visualization
- `Scikit-learn` – ML utilities
- *(AI summary and suggestion logic is implemented using custom logic with NLP patterns)*
---
## 🧪 Installation

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/srivallinalla12/Sentiment-Analysis-For-Work-Life-Balance.git
```
### 2️⃣ Navigate into the project directory:

```bash
cd Sentiment-Analysis-For-Work-Life-Balance
```

### 3️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application:
```bash
python sentiment_analysis.py
```
### 4️⃣ Run the Application (for MAC):
```bash
python3 sentiment_analysis.py
```
```bash
📁 Project Structure

├── sentiment_analysis.py     # Main Python script (GUI + Logic)
├── requirements.txt          # Dependency list
├── SRS.pdf                   # Software Requirements Specification
└── README.md                 # Project documentation
```
---
🎯 Use Cases

- Analyze customer feedback and auto-generate improvement tips
- Review public sentiment on social media posts
- Use AI-generated insights for smarter business or product decisions
- Academic exploration of NLP and data visualization
---
🔮 Sample AI Output

Summary: Majority of the feedback is positive, indicating good overall satisfaction.
Suggestion: However, neutral and negative sentiments suggest improving delivery time and product descriptions.
---

👤 Author

Srivalli Nalla
- Computer Information Science Major 
- 💡 Focused on building intelligent and impactful software using AI and Python
- 🌱 Passionate about AI, NLP, and data-driven design
---

📃 License

Open-source project under the MIT License.
---

