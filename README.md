# Doron Fingold

(pronounced *Finegold*)

I'm currently working on a series of personal projects to deepen my understanding of **Data Science** and **Statistics**, using both **Python** and **R**. My focus has been on building practical tools like a next-word prediction model and visualizing natural language data.

Before pivoting into data science, I spent over two decades in **web and mobile startups**, building B2B and consumer-facing products. My work included:

- Early 2000s: Secure document collaboration platforms and e-learning systems for continuing education credits  
  *(ASP, .NET, C#, JavaScript, SQL)*  
- 2010s: Two mobile social networks — one for short-form video (iPhone 3 and early Android), another in the dating space  
  *(Objective-C, Java, PHP, SQL)*
  
Now, I'm bringing that product and engineering background into the world of data.

### 🛠 Projects

#### 🔮 Next Word Prediction App

A Shiny web application that predicts the next word in a sequence of English text using **Kneser-Ney-smoothed n-gram language models** (bigrams to fivegrams). The app includes:

- An interactive UI with real-time predictions
    
- A backend powered by preprocessed corpora and optimized SQLite queries
    
- Optional Markov chain visualizations of text structure
    
- Perplexity metrics for evaluation  

🖥️ **Live App**: [Next Word Predictor on Shiny](https://lxeimz-doron-fingold.shinyapps.io/simple_word_prediction/)  
🧾 **Project Presentation**: [Slides](https://rpubs.com/DoronF/word_predictor)

Technologies: `R`, `Shiny`, `SQLite`, `tidyverse`, `textclean`, `textstem`, `Kneser-Ney smoothing`

**What I Learned**:

- **Higher-order n-grams (four- and five-grams) are rarely useful in practice**, supporting Markov’s insight that language is mostly driven by short-term dependencies.
    
- **Efficient text preprocessing and query optimization** were essential to making the app run on **limited hardware** (8GB RAM, 2017 MacBook Air), which involved aggressive normalization, indexed lookups, and careful memory use.

<!--
**DoronF/DoronF** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
