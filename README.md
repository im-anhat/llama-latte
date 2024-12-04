# ☕ **Llama-Latte**

> **Llama-Latte** is an AI-powered coffee shop application designed to enhance customer experience through personalized chatbot interactions, real-time recommendations, and seamless order management. Built with **React Native** and **Llama 3 model**, it leverages **Retrieval-Augmented Generation (RAG)** and **Market Basket Analysis** for accurate, context-aware responses and tailored product suggestions.

---

## 📸 **Screenshots**

<table>
  <tr>
    <td>
      <img src="https://via.placeholder.com/500x300?text=Screenshot+1" alt="Screenshot 1" width="100%" />
    </td>
    <td>
      <img src="https://via.placeholder.com/500x300?text=Screenshot+2" alt="Screenshot 2" width="100%" />
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

3. **Start the Application**:
   ```bash
   npx expo start
   ```