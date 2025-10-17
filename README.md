# Captcha Solver

A web-based captcha solver application that handles image URL parameters and intelligently extracts text from captcha images.

## 🚀 Live Demo

**GitHub Pages URL:** https://23f2001817.github.io/captcha-solver-project-complete/

Test with sample image URLs:
```
# With text parameter
https://23f2001817.github.io/captcha-solver-project-complete/?url=https://placehold.co/300x100/png?text=CAPTCHA

# Without text parameter (displays "IMAGE")
https://23f2001817.github.io/captcha-solver-project-complete/?url=https://dummyimage.com/300x100/0066cc/ffffff
```

## 📋 Features

- **URL Parameter Support**: Pass captcha image URLs via `?url=IMAGE_URL` parameter
- **Intelligent Text Extraction**: Automatically detects and extracts text from URL parameters
- **Smart Fallback**: Returns "IMAGE" for URLs without text parameters instead of random text
- **Dynamic Image Display**: Loads and displays captcha images from provided URLs
- **Multiple Fallback Images**: Uses default sample images when no URL is provided
- **Responsive Design**: Clean, mobile-friendly interface with modern styling
- **Error Handling**: Graceful handling of broken or invalid image URLs
- **Fast Processing**: Displays solved captcha text within 15 seconds

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Modern CSS with flexbox and gradient backgrounds
- **Deployment**: GitHub Pages
- **Version Control**: Git with GitHub integration

## 📖 Usage

### Example URLs
```bash
# URL with text parameter
?url=https://placehold.co/300x100/png?text=CAPTCHA
Result: ✅ Solved: CAPTCHA

# URL with encoded text
?url=https://placehold.co/300x100/png?text=TEST+IMAGE
Result: ✅ Solved: TEST IMAGE

# URL without text parameter
?url=https://dummyimage.com/300x100/0066cc/ffffff
Result: ✅ Solved: IMAGE

# URL with text in path
?url=https://example.com/text/SAMPLE/image.png
Result: ✅ Solved: SAMPLE
```

## 🔧 How It Works

1. **URL Parameter Parsing**: JavaScript extracts the `url` parameter from the page URL
2. **Intelligent Text Detection**: Searches for text= or text%3D parameters in the URL
3. **Path Analysis**: Checks for text in URL path if no parameter found
4. **Smart Fallback**: Returns "IMAGE" if no text can be extracted
5. **Image Loading**: Dynamically loads the image with multiple fallback options
6. **Result Display**: Shows the extracted text as the "solved" captcha result within 1.5-3.5 seconds

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
