🚀 **I just built a functional mini-LLM from scratch!** 🚀  
Diving deep into the nuts and bolts of transformer architecture, I created a lightweight GPT-style language model designed for educational exploration and rapid prototyping. Here’s what makes it special:  

### 🔧 **Core Highlights**  
- **Architecture**: Decoder-only transformer (6 layers, 6 attention heads, 384-dim embeddings) with a **128-token context window**.  
- **Tokenizer**: GPT-2 Byte Pair Encoding (BPE) via `tiktoken` (80k vocabulary).  
- **Training**: Optimized on the `TinyStories` dataset using **AdamW**, **gradient clipping (0.5)**, and **mixed precision (AMP)** for stability.  
- **Capabilities**: Generates coherent story snippets, handles simple prompts, and supports **temperature/top-k sampling** for creativity control.  
- **Efficiency**: Runs on a single GPU—perfect for testing ideas fast!  

### 🧠 **Why This Matters**  
This project demystifies LLM internals while emphasizing:  
1️⃣ **Scalability**: Even tiny transformers (6L/6H) can produce logical text.  
2️⃣ **Training Tricks**: LR warmup + cosine decay, gradient accumulation, and AMP prevent instability.  
3️⃣ **Real-World Gaps**: No safety layers yet (future work!), domain-limited to `TinyStories`.  

### 🌟 **What’s Next?**  
- Integrate **RoPE/ALIBI** for longer contexts → 128 tokens ➡️ 512+.  
- Add **safety adapters** and **conversational fine-tuning**.  
- Publish a full research write-up!  

**👉 Check out the [PDF] and [CODE] attached!**  
I’ve open-sourced everything to help others learn—ideal for hands-on LLM newbies or educators. Feedback welcome!  

### 🏷 **Top Tags**  
#AI #MachineLearning #DeepLearning #LLM #Transformers #NLP #ArtificialIntelligence #DataScience #NeuralNetworks #Python #OpenSource #TechRecruitment #BuildInPublic #LearnAI  


**Credits**: Made with inspiration from Andrej Karpathy’s nanoGPT & TinyStories dataset.
