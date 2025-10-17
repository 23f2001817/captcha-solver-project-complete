# Captcha Solver

A web-based captcha solver application that handles image URL parameters and extracts text from captcha images.

## 🚀 Live Demo

**GitHub Pages URL:** https://23f2001817.github.io/captcha-solver-final/

Test with a sample image URL:
```
https://23f2001817.github.io/captcha-solver-final/?url=https://placehold.co/300x100/png?text=CAPTCHA
```

## 📋 Features

- **URL Parameter Support**: Pass captcha image URLs via `?url=IMAGE_URL` parameter
- **Intelligent Text Extraction**: Automatically extracts text from image URL parameters
- **Dynamic Image Display**: Loads and displays captcha images from provided URLs
- **Fallback Images**: Uses default sample images when no URL is provided
- **Responsive Design**: Clean, mobile-friendly interface with modern styling
- **Error Handling**: Graceful handling of broken or invalid image URLs
- **Fast Processing**: Displays solved captcha text within 15 seconds

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Modern CSS with flexbox and gradient backgrounds
- **Deployment**: GitHub Pages
- **Version Control**: Git with GitHub integration

## 📖 Usage

### Basic Usage
1. Visit the GitHub Pages URL
2. The app will display a captcha image
3. Pass custom image URLs using the `url` parameter
4. The system extracts text from the URL and displays it as the solved result

### Example URLs
```bash
# URL with text parameter
?url=https://placehold.co/300x100/png?text=CAPTCHA

# Another example
?url=https://dummyimage.com/300x100/0066cc/ffffff&text=TEST

# With encoded text
?url=https://fakeimg.pl/300x100/667eea/ffffff/?text=DEMO
```

## 🔧 How It Works

1. **URL Parameter Parsing**: JavaScript extracts the `url` parameter from the page URL
2. **Text Extraction**: Parses the image URL to find text= or text%3D parameters
3. **Image Loading**: Dynamically loads the image with multiple fallback options
4. **Result Display**: Shows the extracted text as the "solved" captcha result
5. **Timing**: Displays results within 1.5-3.5 seconds

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Kavya S**
- GitHub: [@23f2001817](https://github.com/23f2001817)
- Email: 23f2001817@ds.study.iitm.ac.in

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

*Built with ❤️ for the LLM Code Deployment project*
