# BERT - Next Sentence Prediction (NSP)

This project explores the use of **Next Sentence Prediction (NSP)** using BERT, a powerful transformer-based language model. NSP helps the model understand the logical flow between two sentences, enabling more coherent language comprehension across many NLP tasks.

## 🔍 What is NSP?

Next Sentence Prediction is a technique where the model is given a pair of sentences and tasked with identifying whether the second naturally follows the first. This is more than just a simple classification—it teaches the model about discourse and sequence.

For example:
- **Sentence A:** "The sun was setting behind the hills."
- **Sentence B:** "The sky turned shades of pink and orange."

In a proper sequence, these make sense. But if Sentence B were something like “Cats are domesticated animals,” the connection would likely be false.

This foundational concept strengthens a model’s performance in areas like:
- Conversational AI
- Question Answering
- Context-aware Summarization

## 🧠 Why BERT?

BERT (Bidirectional Encoder Representations from Transformers) is especially suited for tasks that require a nuanced understanding of language. Trained on massive corpora with objectives like Masked Language Modeling and NSP, BERT can discern sentence-level relationships effectively.

## ⚙️ Getting Started

To try this out, you’ll need the `transformers` and `torch` libraries. Once installed, you can experiment with feeding in sentence pairs and observing how BERT evaluates their coherence.

You won’t just get a simple yes/no answer; BERT returns logits that reflect the model’s confidence in whether the second sentence logically follows the first.

## 💡 Applications

Understanding sentence relationships is crucial in building smart systems:
- Chatbots that stay on topic
- Systems that answer follow-up questions accurately
- Tools that summarize text with contextual flow

## 📚 References

- Original BERT Paper: [arXiv:1810.04805](https://arxiv.org/abs/1810.04805)
- Hugging Face Transformers: [huggingface.co](https://huggingface.co/transformers)

---

This project is a hands-on dive into one of BERT’s key training tasks—designed not just to run, but to understand.
