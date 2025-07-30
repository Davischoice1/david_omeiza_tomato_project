## 🍅 Tomato Leaf Disease Detection App

A deep learning-powered web application built with Streamlit to detect tomato leaf diseases from uploaded or captured images, providing actionable solutions for farmers and agricultural professionals.

---

### 🔗 Live Demo

> ✅ Deployed on **Streamlit Cloud**
> 🌍 [Click to view app](https://tpdcsys.streamlit.app/)


---

### 📌 Features

* 🌱 Classifies tomato leaves into 5 categories (including healthy).
* 🖼️ Supports both image upload and camera capture.
* 💡 Offers treatment suggestions based on predictions.
* 🚫 Rejects non-tomato images and invalid inputs.
* 🧠 Powered by a trained Convolutional Neural Network.
* 🌐 Deployed and accessible via any web browser.

---

### 🧪 Supported Classes

| Label | Description     |
| ----- | --------------- |
| 0     | Bacterial Spot  |
| 1     | Early Blight    |
| 2     | Late Blight     |
| 3     | Southern Blight |
| 4     | Healthy Leaf    |

---

### 📁 Project Structure

```
tomato-disease-app/
│
├── app.py                          # Streamlit app
├── requirements.txt                # App dependencies
├── plant_disease_model.keras   # Trained CNN model
├── Logo.jpg                        # Sidebar logo
├── toma.jpg                        # Home page banner
```

---

### ⚙️ Installation

#### 📥 Clone the Repository

```bash
https://github.com/Davischoice1/david_omeiza_tomato_project.git
cd tomato-disease-app
```

#### 🧪 Install Dependencies

```bash
pip install -r requirements.txt
```

#### 🚀 Run the App Locally

```bash
streamlit run app.py
```

---

### 📷 Usage

1. Click **Prediction** in the sidebar.
2. Upload or capture a clear image of a tomato leaf.
3. Click **Predict**.
4. View the disease type, confidence level, and treatment suggestion.

> ✅ Only tomato leaf images are supported. Other inputs will be flagged.

---

### 📦 Requirements

```
streamlit==1.27.2
tensorflow==2.12.0
pillow==9.5.0
numpy==1.24.4
```

---

### 🌍 Deployment

To deploy on [Streamlit Cloud](https://streamlit.io/cloud):

1. Push your code to a public GitHub repository.
2. Sign in to [Streamlit Cloud](https://streamlit.io/cloud).
3. Click **"New App"**.
4. Select your GitHub repo and set:

   * `Main file path`: `app.py`
   * Python version: 3.10 (Streamlit default)
5. Upload `plant_disease_model.keras`, `Logo.jpg`, and `toma.jpg` via GitHub.

---

### 🙋‍♂️ FAQ

* **What types of images are accepted?**
  Only clear images of tomato leaves in JPEG/PNG format.

* **How accurate is the model?**
  The CNN was trained on a curated dataset with high accuracy on validation data.

* **What happens if I upload something else?**
  The model may return an error or low confidence warning.

---

### 📬 Contact

* **Email**: [support@davischoice@gmail.com](mailto:support@davischoice@gmail.com)
* **Phone**: +234-706-420-6404
* **Team**: Aurevo Global

