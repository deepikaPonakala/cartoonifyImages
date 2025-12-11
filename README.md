📘 Cartoonify Images Using Python & OpenCV

Transform ordinary images into cartoon-style artwork using Python, OpenCV, and image processing techniques.
This project provides a simple GUI-based tool to upload an image and instantly convert it into a cartoon version.

🚀 Features

🖼️ Upload any JPG/PNG image

🎨 Convert the image to cartoon style

📦 Save the cartoonified image

🧠 Uses OpenCV filters + edge detection

🪟 Simple GUI built using Tkinter

⚡ Fast and easy to use

🛠️ Technologies Used
Library	Purpose
OpenCV	Image processing (filters, edge detection)
NumPy	Handling image arrays
Tkinter	GUI for image upload
Python 3.x	Core programming language
📂 Project Structure
cartoonifyImages/
│
├── cartoonifier-python-project.py   # Main application
├── README.md                        # Project documentation
└── sample/                          # (Optional) images to test

🖥️ How It Works

The cartoon effect is created by applying:

Bilateral Filtering
Smoothens the image but preserves edges.

Edge Detection
Converts edges into a clean black outline.

Color Quantization
Reduces the number of colors to give the “cartoon” style.

Combining Edges + Smoothed Image

📥 Installation

Make sure you have Python installed (3.10+ recommended).

Install dependencies:

pip install opencv-python
pip install numpy

▶️ Usage

Run the script:

python cartoonifier-python-project.py


GUI will open → Click Upload Image → Choose an image → Cartoon version appears.

📝 Example Output
Original	Cartoonified
<img src="images/original.jpg" width="250">	<img src="images/cartoon.jpg" width="250">

(Add your own samples here)

🤝 Contributing

Pull requests are welcome!
If you’d like to improve the GUI or add new filters, feel free to contribute.
