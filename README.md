Visualytix
Spot the invisible. Prevent the inevitable.
The winning AI inspection engine for the TrackShift 2025 Hackathon.

🚦 Inspiration
Modern industries demand a new standard for quality assurance—one that is fast, accurate, and tireless. The team behind Visualytix is passionate about solving the invisible defects missed by manual inspection and legacy digital tools. Our project aims to revolutionize how brand compliance and infrastructure safety are maintained, preventing costly errors before they impact operations.

💡 What It Does
Visualytix uses advanced computer vision and AI to automatically detect subtle visual defects in manufacturing, infrastructure, and branding. It flags anomalies with high confidence, empowering operations teams to act before issues escalate.

Tech Highlights:

Logo and branding compliance checking for F1 and other industries

Infrastructure health monitoring (crack, corrosion, deformation detection)

Manufacturing quality control (PCB and solder joint inspection)

Realistic AI confidence and severity scoring

🏗️ How We Built It
Visualytix combines:

PyTorch-powered deep learning for robust visual detection

OpenCV for precise image manipulation

FastAPI to build a lightweight API layer

Streamlit for intuitive image upload and review demos

All proof-of-concept demo images were hand-crafted using Photoshop/Canva to simulate realistic AI outputs for the TrackShift hackathon timeline.

🖼️ Proof of Concept Gallery
Before (Raw Input)	                              After (AI Output)
Screenshots of Haas F1 brand compliance scenario	Bounding box + warning on subtle color shift
Concrete bridge (infrastructure)	                Grad-CAM style heatmap showing crack detection
PCB board (manufacturing)	                        Red box highlighting bad solder joint

See the media/ folder for all demo images.

⚡ Getting Started
Clone the repository and install dependencies:

bash
git clone https://github.com/Srinath-Y-dev/Visualytix.git
cd Visualytix
pip install -r requirements.txt

Launch the demo:
bash
streamlit run app.py

🔧 Requirements
torch
opencv-python-headless
scikit-learn
numpy
fastapi
uvicorn
streamlit

🚀 Try It Out
View all demo images and diagrams in the repo's media folder.

Upload your own screenshots in the Streamlit UI to see simulated outputs.

🙌 Team
Srinath.Y
Naveen Kumar.G

📄 License
MIT License.
See LICENSE file for details.

📢 Devpost Submission
For the full story, technical write-up, and inspiration, please refer to our [Devpost Project Story] and check out the gallery for demo imagery.
