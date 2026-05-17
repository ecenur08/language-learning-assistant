# language-learning-assistant
AI-powered multilingual language learning assistant with RAG architecture and LLM integration
# 🌍 Language Learning Assistant / Dil Öğrenme Asistanı

AI-powered multilingual language learning assistant with RAG architecture and LLM integration.

RAG mimarisi ve LLM entegrasyonu ile yapay zeka destekli çok dilli dil öğrenme asistanı.

## 📸 Screenshots / Ekran Görüntüleri

![Arayüz 1](foto1_ismi.png)
![Arayüz 2](foto2_ismi.png)

## 🚀 Features / Özellikler

- 🧠 Neural network for language detection (%99.7 accuracy) / Dil tespiti için sinir ağı (%99.7 doğruluk)
- 🗄️ RAG architecture with ChromaDB / ChromaDB ile RAG mimarisi
- 🤖 LLM integration with Groq (Llama 3.3) / Groq ile LLM entegrasyonu
- 🌍 6 language support / 6 dil desteği (Türkçe, İngilizce, Almanca, Fransızca, İspanyolca, İtalyanca)
- 💬 Conversation continuation suggestions / Konuşmayı devam ettirme önerileri
- 📈 Self-improving system / Kendini geliştiren sistem

## 🛠️ Technologies / Teknolojiler

| Teknoloji | Kullanım |
|-----------|----------|
| TensorFlow & Keras | Sinir ağı eğitimi |
| Sentence Transformers | Embedding modeli |
| ChromaDB | Vektör veritabanı |
| Groq API (Llama 3.3) | LLM entegrasyonu |
| Deep Translator | Çeviri API |
| LangDetect | Dil tespiti |
| Gradio | Kullanıcı arayüzü |

## 📊 Dataset / Veri Seti

- 473.035 Türkçe-İngilizce cümle çifti / Turkish-English sentence pairs
- Kaynak / Source: [Turkish to English Translation Dataset](https://www.kaggle.com/datasets/seymasa/turkish-to-english-translation-dataset)

## ⚙️ How It Works / Nasıl Çalışır?

1. Kullanıcı herhangi bir dilde yazar / User writes in any language
2. Sinir ağı dili tespit eder / Neural network detects the language
3. Deep Translator çeviri yapar / Deep Translator translates
4. ChromaDB benzer cümleleri getirir (RAG) / ChromaDB retrieves similar sentences
5. Groq LLM konuşma önerileri üretir / Groq LLM generates suggestions
6. LLM çıktıları ChromaDB'ye eklenir / LLM outputs added to ChromaDB

## 🔑 Setup / Kurulum

1. [groq.com](https://groq.com) adresinden Groq API key alın
2. [kaggle.com](https://kaggle.com) adresinden Kaggle token alın
3. Notebook'u Google Colab'da açın
4. Tüm hücreleri çalıştırın

## ⚠️ Not / Note

Groq API key'inizi notebook'a ekleyin:
```python
GROQ_API_KEY = "your_api_key_here"
```
