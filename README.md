Img_Recog
An AI-powered Image Recognition web application built using Next.js, TensorFlow.js, and MobileNet. The application allows users to upload images and classify objects directly in the browser using pre-trained machine learning models.

🚀 Features
Upload any image from your device
Real-time image classification using TensorFlow.js
MobileNet pre-trained deep learning model
Responsive UI built with Next.js and Tailwind CSS
Fast client-side inference
Camera/Webcam integration support (work in progress)

🛠️ Tech Stack
Next.js
React.js
TensorFlow.js
MobileNet
Tailwind CSS
JavaScript

📂 Project Structure
img_recog/
│
├── public/
├── src/
│   ├── app/
│   │   ├── page.js
│   │   ├── recog/
│   │   │   └── page.jsx
│
├── package.json
├── package-lock.json
└── README.md


⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/Varun-Singh24/img_recog.git

2️⃣ Navigate into the project folder
cd img_recog

3️⃣ Install dependencies
npm install

4️⃣ Run the development server
npm run dev


🌐 Open in Browser
http://localhost:3000


🧠 How It Works
User uploads an image
TensorFlow.js loads the MobileNet model
The uploaded image is processed in the browser
The model predicts the object category
Predictions with confidence scores are displayed

📸 Future Improvements
Real-time webcam object detection
COCO-SSD integration
Bounding box detection
Multiple object recognition
Better UI/UX
Deployment optimization

🚀 Deployment
This project can be deployed easily on:
Vercel
Netlify
GitHub Pages
Recommended platform: Vercel

👨‍💻 Author
Varun Pratap Singh
GitHub: https://github.com/Varun-Singh24

⭐ Support
If you like this project:
Star the repository
Fork the project
Share feedback

📄 License
This project is open-source and available under the MIT License.
