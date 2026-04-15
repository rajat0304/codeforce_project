# codeforce_project
## 🚀 The Problem & Our Solution
### The Challenge:
- **Delayed Triage:** Emergency cases mein logon ko pata nahi hota ki kab hospital bhagna hai.
- **Medication Risks:** Bina jankari ke multiple medicines lene se fatal drug interactions ho sakte hain.
- **Access to Information:** Reliable medical data dhoondhna mushkil hota hai.
## ✨ Key Features (Level 3 Autonomy)

| Feature | Description | Tech Power |
|:--- |:--- |:--- |
| **Instant Triage** | Complex symptoms ko analyze karke direct advice dena. | Groq + Llama 3.3 |
| **Drug Interaction** | Do medicines ke beech ke potential risks ko instantly check karna. | Serper API Integration |
| **Smart Hospital Locator** | Emergency mein user ki location ke basis par nearest hospitals find karna. | Real-time Geo-Search |
| **Metric Insights** | Height/Weight ke basis par health parameters (BMI) calculate karna. | Mathematical Logic Tools |
| **Direct Response** | No unnecessary follow-ups. Seedha point-to-point healthcare guidance. | Optimized System Prompting |

---

## 🛠 Tech Stack

- **LLM:** Llama-3.3-70b-versatile (via Groq Cloud)
- **Orchestration:** [Pydantic AI](https://ai.pydantic.dev/) (For Type-safe Agentic Workflows)
- **Search Engine:** Serper.dev (Google Search API)
- **UI Framework:** Gradio (For real-time streaming interface)
- **Infrastructure:** Python 3.10+

---

## 🏗 System Architecture

SwasthyaAI ek "Reason-then-Act" loop par chalta hai:
1. **Input Analysis:** Agent user ke query ka intent samajhta hai.
2. **Autonomous Tool Selection:** Kya search karna hai? Kya BMI calculate karna hai? Ya Hospital dhoondhna hai?
3. **Validation:** Pydantic models ka use karke ensure kiya jata hai ki data structure correct ho.
4. **Direct Stream:** Gradio interface ke through token-by-token response stream hota hai for low latency.

---

## ⚙️ Installation & Setup

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/swasthya-ai.git](https://github.com/your-username/swasthya-ai.git)
   cd swasthya-ai
