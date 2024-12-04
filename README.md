# ☕ **Llama-Latte**

> **Llama-Latte** is an AI-powered coffee shop application designed to enhance customer experience through personalized chatbot interactions, real-time recommendations, and seamless order management. Built with **React Native** and **Llama 3 model**, it leverages **Retrieval-Augmented Generation (RAG)** and **Market Basket Analysis** for accurate, context-aware responses and tailored product suggestions.

<div align="center">
  <img src="https://github.com/user-attachments/assets/b8efdd37-d366-40c3-90e6-bb050779a2a4" alt="Llama-Latte Screenshot" width="300"/>
</div>

---

## 📸 **Screenshots**

<table>
  <tr>
    <td>
      <div align="center">
        <img src="https://github.com/user-attachments/assets/03a3f8c7-274e-4b87-bfe6-52e112286ff8" alt="Image 1" width="60%"/>
      </div>
    </td>
    <td>
      <div align="center">
        <img src="https://github.com/user-attachments/assets/8bd28126-35f4-4812-912b-ec8669daecf5" alt="Image 2" width="60%"/>
      </div>
    </td>
  </tr>
</table>

---

## 💻 **Technologies**

### **Frontend**

- **React Native**
- **Expo** for rapid app development
- **NativeWind** for styling

### **AI and Backend**

- **Llama 3 Model** for AI-driven chatbot
- **Retrieval-Augmented Generation (RAG)** for personalized responses
- **Firebase Firestore** for real-time database
- **RunPod API** for scalable model hosting

### **Data Science**

- **Market Basket Analysis** using Apriori algorithm for recommendation generation

### **DevOps**

- **Docker** for containerization
- **RunPod** for deployment and hosting
- **GitHub Actions** for CI/CD

---

## 🚀 **Features**

### 🤖 **AI-Driven Chatbot**

- Built with **Llama 3 Model** to handle customer queries, recommend products, and manage orders seamlessly.
- Enhanced with **RAG** for context-aware responses by retrieving real-time data from the coffee shop database.

### 🛒 **Personalized Recommendations**

- Utilizes **Market Basket Analysis** to provide tailored recommendations based on purchase patterns.
- Offers **popularity-based** and **category-specific** recommendations for drinks and pastries.

### 🎯 **Agent-Based System**

- Specialized agents handle:
  - **Order-taking**: Validates menu items and calculates totals.
  - **Product recommendations**: Suggests complementary products.
  - **Query filtering**: Ensures only relevant questions are processed.

### 🖥️ **Cross-Platform Compatibility**

- Developed with **React Native** for smooth deployment on iOS and Android.
- Deployed on **RunPod** for scalable API and AI model integration.

---

## 🛠️ **Getting Started**

### 📋 **Prerequisites**

- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **Expo CLI**
- **Firebase** account with Firestore configured
- **Docker** for local containerization (optional)

### 🚀 **Installation**

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/llama-latte.git
   cd llama-latte

   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a .env file in the root directory with:

   RUNPOD_TOKEN=your_runpod_token

   RUNPOD_CHATBOT_URL=your_runpod_chatbot_url

   MODEL_NAME=meta-llama/Meta-Llama-3-8B-Instruct

   FIREBASE_API_KEY=your_firebase_api_key

4. **Start the Application**:
   ```bash
   npx expo start --tunnel
   ```

## 📊 Architecture

Frontend

    •	React Native app powered by Expo

    •	NativeWind for consistent and flexible UI styling

Backend

    •	Llama 3 model deployed on RunPod API

    •	Firebase Firestore for real-time database management

Recommendation System

    •	Apriori algorithm for generating purchase-based recommendations

    •	Popularity-based recommendations categorized by product types

## 🛠️ Key Functionalities

🌟 AI-Driven Order Management

    •	Process orders with accurate validation and price calculation.

    •	Suggest complementary products based on the customer’s current selection.

🔍 Smart Recommendations

    •	Apriori Recommendations: Suggest items frequently purchased together.

    •	Popular Recommendations: Suggest trending items in the coffee shop.

    •	Category-Specific Recommendations: Suggest items within a specific category based on customer interest.

🔒 Secure and Scalable Deployment

    •	Deployed with Docker and RunPod, ensuring scalability and cross-platform compatibility.

    •	Sensitive configurations securely managed with environment variables.
