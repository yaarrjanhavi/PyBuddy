# PyBuddy 🐍✨

## Your Friendly Python AI Coding Companion

A specialized GPT-2 based conversational AI that exclusively answers Python programming questions through intelligent keyword filtering.

### What PyBuddy Does

PyBuddy is like having a coding buddy who's obsessed with Python (in a good way!). It:
- Accepts user prompts and validates them against Python coding keywords
- Generates helpful responses for Python-related queries using GPT-2 Medium
- Politely rejects non-coding questions with a friendly message
- Provides a simple, focused tool for learning and troubleshooting Python code

PyBuddy keeps you on track - it only wants to talk about Python, all day, every day! 🎓

### Key Components

**1. Keyword Filter (`is_coding_question`)**: Scans prompts for 30+ Python-related terms including language constructs (def, class, import), data types (list, dict, tuple), control flow (if, for, while), and common functions (print, input, open).

**2. Response Generator (`answer_question`)**: Uses the pre-trained GPT-2 Medium model to generate context-aware responses for validated coding questions, with configurable output length and quality parameters.

**3. Model Configuration**: Implements proper tokenization with padding and attention masking to ensure high-quality text generation.

### Use Cases

- **Learning Tool**: Beginners can ask PyBuddy about Python syntax and concepts
- **Quick Reference**: Get instant explanations for Python features from your buddy
- **Focused Assistance**: PyBuddy ensures conversations stay on-topic for coding help
- **Educational Demo**: Shows how to implement constrained LLM behavior with personality

### Technical Approach

Built with Hugging Face Transformers, the system uses a simple but effective keyword-matching algorithm to filter incoming queries before passing them to the GPT-2 model. While not as sophisticated as a trained classifier, this approach provides fast, reliable filtering with minimal computational overhead.

### Why PyBuddy Matters

PyBuddy demonstrates how to create purpose-specific AI assistants with personality from general-purpose language models without expensive fine-tuning or retraining. It's a practical example of prompt engineering and response filtering that can be adapted for other domain-specific applications. Plus, who doesn't want a dedicated Python buddy? 🤝

---

**Tech Stack**: Python 3 | PyTorch | Transformers | GPT-2 Medium (355M parameters)

**Perfect For**: Students, educators, Python learners, and anyone who needs a reliable coding buddy! 

*Made with 💙 and lots of Python enthusiasm*
