# Historical-Artifact-3D-Reconstruction-Tool
An AI-powered tool for reconstructing 3D models of historical artifacts from 2D images, leveraging LiheYoung/depth-anything-small-hf for accurate depth estimation and digital preservation.


Overview
The Historical Artifact 3D Reconstruction Tool, developed by ITSOLERA PVT LTD, is designed to convert 2D images into 3D models for the preservation and accessibility of cultural heritage. The tool uses the LiheYoung/depth-anything-small-hf model from Hugging Face to estimate depth maps and reconstruct 3D structures, ensuring historical artifacts remain digitally preserved for researchers, educators, and the public.

Features
  1. AI-Powered 3D Reconstruction – Converts 2D images into 3D models using advanced depth estimation techniques.
  2. Texture Preservation – Retains fine details and textures from the original images.
  3. User-Friendly Interface – Web-based UI with image upload, reconstruction parameters, and interactive 3D viewing.
  4. Handles Low-Quality Images – Supports aged, low-resolution, and archival images.
  5. Exportable 3D Models – Allows users to download and share reconstructed artifacts.

Technologies Used
  Deep Learning & Computer Vision (LiheYoung/depth-anything-small-hf for depth estimation)
  PyTorch & Transformers (for model implementation)
  OpenCV (for image processing)
  3D Mesh Reconstruction Algorithms (for geometry creation)
  Streamlit (for web-based user interface)
  
Workflow
  1️⃣ Image Upload – Users upload historical artifact images via the web interface.
  2️⃣ Depth Estimation – The pre-trained depth estimation model predicts depth maps from 2D images.
  3️⃣ 3D Geometry Construction – Depth data and 2D images are used to generate 3D meshes.
  4️⃣ Texture Mapping – The original image textures are applied to enhance realism.
  5️⃣ User Interaction – Users can view, adjust, and export the 3D models.
