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

#### 🥏 Disc Golf Course Explorer (Shiny App)

**Explore and compare disc golf courses across the U.S. using interactive maps and visualizations.**

- Built with **R Shiny**, **Leaflet**, and **ggplot2** to create an intuitive app for browsing, filtering, and analyzing over 7,000 disc golf courses.
    
- Users can:
    
    - Filter courses by state
        
    - View location details and links via popups
        
    - Jump to a random course with a smooth map animation
        
    - Compare course ratings to state or national distributions using dynamic histograms
        
- Integrated external datasets and designed custom icons for a polished user experience.
    

🔗 [Live App](https://lxeimz-doron-fingold.shinyapps.io/CourseRating/)  
📊 [Dataset on Kaggle](https://www.kaggle.com/datasets/lanekatris/pdga-united-states-disc-golf-courses)

### 🚀 SpaceX Launch Success Prediction (ML Model)

**Built a supervised machine learning model to predict the success of SpaceX Falcon 9 launches.**

- Explored and visualized SpaceX launch data using **pandas**, **matplotlib**, **seaborn**, and **plotly**.
    
- Engineered features from categorical launch attributes including launch site, payload mass, and booster version.
    
- Trained and evaluated several classification models (**Logistic Regression**, **Random Forest**, **SVM**, **KNN**) to determine the likelihood of a successful landing.
    
- Tuned hyperparameters and assessed performance using metrics like **accuracy**, **F1 score**, and **confusion matrix**.
    

📓 [Notebook on GitHub](https://github.com/DoronF/IBM_DS_Capstone/blob/main/SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb)
