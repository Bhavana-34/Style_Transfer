🎨 Neural Style Transfer with TensorFlow
A Python implementation of artistic style transfer using TensorFlow Hub's pre-trained model. Transform your photos into artworks by combining content with artistic styles!

✨ Features
🖼️ Dual Input Methods: Load images from URLs or local uploads

🚀 Pre-trained Model: Uses TensorFlow Hub's Magenta model

📱 Colab Ready: Works seamlessly in Google Colaboratory

💾 Auto-save: Automatically saves the stylized output

🛡️ Error Handling: Robust download with browser headers

🛠️ Installation
bash
pip install tensorflow tensorflow_hub matplotlib pillow requests numpy
🚀 Quick Start
Set your input method:

python
use_offline = True  # 📁 Upload local images
use_offline = False # 🌐 Use image URLs
Run the script and:

Upload your content image (landscape, portrait, etc.)

Upload your style image (artwork, texture, etc.)

Watch the magic happen! ✨

📸 Example
Content Image	Style Image	Stylized Result
🏝️ Beach	🎨 Artwork	🖼️ Stylized Beach
🎯 Usage Options
🌐 URL Mode
python
content_url = "https://example.com/content.jpg"
style_url = "https://example.com/style.jpg"
📁 Upload Mode
Direct file upload in Colab

Supports common image formats (JPG, PNG, etc.)

📁 Output
File: stylized_output.png

Format: PNG with original dimensions

Location: Current working directory

🔧 Technical Details
Model: Magenta Arbitrary Image Stylization v1-256

Framework: TensorFlow 2.x

Max Dimension: 512px (optimized for performance)

Libraries: TensorFlow Hub, Matplotlib, Pillow, Requests

💡 Tips
🖼️ Use high-contrast style images for better results

⚡ Experiment with different content-style combinations

🎨 The model works best with distinct artistic styles

📱 Perfect for creating social media artwork!

🤝 Contributing
Feel free to fork this project and submit pull requests for any improvements!

📄 License
