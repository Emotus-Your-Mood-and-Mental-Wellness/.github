# Emotus - Your Journey to Emotional Wellness
![Emotus - Your Mood and Mental Wellness Companion](https://github.com/user-attachments/assets/88f4bcae-7147-423a-a66e-8113a764bf5b)
## ⭐ **About The Project**
| **Team ID**  | **Theme**                                                        |
|--------------|------------------------------------------------------------------|
| C242-PS418   | Health Innovation: Empowering Vulnerable Communities for Health and Well-being |

### **What is Emotus?**
<p align="justify">
Emotus is an innovative emotional wellness app designed to help users track their mood, understand emotional patterns, and receive personalized recommendations for improving their mental well-being. By using a combination of machine learning, mobile development, and cloud computing, Emotus offers a comprehensive, data-driven solution for users looking to improve their emotional health. The app focuses on core emotional states such as anger, love, fear, joy, and sadness, providing tailored suggestions and visualizing emotional trends over time. The solution is designed to be culturally relevant, with a particular focus on the Indonesian audience, integrating tools like Sastrawi for text preprocessing and localized emotional recommendations.
</p>

### **How did we come up with this project?**
<p align="justify">
Our team recognized the growing importance of mental health and the need for accessible tools to support emotional well-being. Through discussions, we identified that while many people are aware of the importance of mental health, they often lack structured ways to monitor and understand their emotions. Inspired by this gap, we envisioned an application that simplifies mood tracking and provides actionable insights, empowering users to recognize emotional patterns and manage their mental health proactively. The idea resonated with our team’s shared goal to create a meaningful tool that could contribute to users' overall well-being.
</p>

### **Why should we choose Emotus?**
> **Because Your Feelings Matter**

Emotus here to support you on your emotional journey, we do our best offering a friendly & caring hand whenever you need. By understanding your mood, we can suggests personalized activities to help you feel better. Why should we choose?



## 😎 **Team Members**
| **Student ID**       | **Name**                             | **Learning Path**    | **University**                             | **Contact**                                                                                         |
|----------------------|--------------------------------------|----------------------|--------------------------------------------|-----------------------------------------------------------------------------------------------------|
| M006B4KY2549         | Moh. Rendy Setiawan                  | Machine Learning     | Universitas Brawijaya                      | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moh-rendy-setiawan-448602221/)              |
| M204B4KX4112         | Setianingsih                         | Machine Learning     | Universitas Esa Unggul                     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/setianingsih03/)              |
| M278B4KX0447         | Amalia Putri                         | Machine Learning     | Universitas Negeri Makassar                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amalia-putri-0b4068328/)                |
| C278B4KY2607         | Muhammad Zaky Ramadhan Chahyadi      | Cloud Computing      | Universitas Negeri Makassar                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zakychahyadi/)              |
| C278B4KX1224         | Dzikrina Syamila                     | Cloud Computing      | Universitas Negeri Makassar                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dzikrinasyml/)            |
| A345B4KY1212         | Dymas Adi Saputra                    | Mobile Development   | Universitas 17 Agustus 1945 Surabaya       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dymas-adi-saputra-918938205/)                    |
| A179B4KX2449         | Maylieska Divaliana Setiawan         | Mobile Development   | Universitas Ahmad Dahlan                   | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maylieskadivaliana/)          |

### ☁️ **Cloud Computing**
<p align="justify">
The cloud infrastructure for Emotus is built on Google Cloud Platform. We use Cloud Run to deploy our backend API, ensuring automatic scaling based on traffic. Cloud Firestore is utilized for secure and scalable data storage. For file storage, we use Google Cloud Storage to store user profile images and other media. This setup ensures that Emotus can efficiently handle user requests, provide real-time data updates, and store data securely while offering scalability as the user base grows.
</p>

### ⚙️ **Tech Stack:**

- **Cloud Run**: Deploys containerized applications and handles scaling automatically based on user demand. **Emotus** uses **Cloud Run** to deploy both the machine learning model and the backend API, ensuring efficient, scalable processing for mood prediction and recommendations.
- **Cloud Firestore**: NoSQL database used for storing user data, mood entries, and recommendations.
- **Cloud Storage**: Used for storing media files (e.g., profile images).
- **Express.js**: A fast and lightweight web framework used for building the backend API, handling routing, and managing HTTP requests efficiently.

### 🤖 **Machine Learning**
<p align="justify">
The machine learning model in Emotus classifies user moods from their journal entries using a GRU (Gated Recurrent Unit) architecture, ideal for processing sequential text data. The model is trained on TF-IDF features extracted from preprocessed text to identify moods such as Anger, Happy, Sadness, Fear, and Love. To handle the informal nature of social media language, the Sastrawi stemmer is used to process Indonesian text. The system mitigates class imbalance using techniques like class weights, ensuring better performance for minority classes like Fear and Love. Once the mood is classified, the recommendation system suggests personalized activities based on the user's mood and the time of day, helping users manage their emotional well-being by offering tailored activities for Low, Medium, and High stress levels.
</p>

### ⚙️ **Tech Stack:**

- **TensorFlow**: A deep learning framework used to build and train the GRU model for mood classification, processing sequential text data for accurate mood predictions.
- **GRU (Gated Recurrent Unit)**: A type of Recurrent Neural Network (RNN) optimized for sequence modeling, ideal for processing user input text and classifying moods.
- **TF-IDF**: A feature extraction technique used to convert text into numerical data, enabling the model to learn from important keywords and patterns in user input.
- **Sastrawi**: A Bahasa Indonesia stemmer library used to preprocess text and normalize words, ensuring better feature extraction and more accurate classification results.
- **Scikit-learn**: A library for machine learning in Python, useful for model evaluation, preprocessing, and splitting datasets.
- **FastAPI**: A modern, fast (high-performance) web framework used for serving the trained machine learning model and providing mood classification and activity recommendations via an API.
- **Google Colab**: A cloud-based Python environment for running machine learning models and experiments quickly without requiring a local setup.
  
### 📱 **Mobile Development**
<p align="justify">
The mobile development process for Emotus focused on creating a robust and user-friendly application to enhance the user experience. Built using Kotlin, the app integrates various technologies to deliver seamless functionality. To visualize user mood trends over time, we implemented PhilJay MPAndroidChart, enabling interactive charts and graphs that help users track their emotional states. Retrofit was utilized for efficient communication between the app and backend APIs, facilitating mood prediction requests and data retrieval. The Date class ensures proper recording of user input timestamps, allowing users to observe patterns in their emotional well-being. For UI/UX design, Figma was employed to craft intuitive wireframes and prototypes. All features were developed and tested using Android Studio, ensuring a polished and functional app ready for deployment.

### ⚙️ **Tech Stack:**

- **Kotlin**: The primary programming language for building the Android application, ensuring modern and reliable development practices.
- **Figma**: Used to design wireframes and prototypes, creating an engaging and intuitive user interface.
- **Android** Studio: The IDE for developing and testing the app, integrating all features seamlessly.

### Screenshot Application
![Untitled-1](https://github.com/user-attachments/assets/0fb357fd-cf00-4d3d-819f-3fd218c1fca5)![Untitled-w1](https://github.com/user-attachments/assets/54d31e23-2b4b-449d-ac6b-54b986bfca66)

# 💖 **Special Thanks**
![Untitled design (15)](https://github.com/user-attachments/assets/3c3dda29-b5d4-44ce-ad27-f2be9332ef85)
