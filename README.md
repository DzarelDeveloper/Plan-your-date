# Let's Plan Our Special Date 💝

This project is an interactive webpage to ask someone on a date, featuring a date scheduler and WhatsApp integration.

---
## **🚀 Respect Open-Source**
I built this for **fun & learning**. If you fork or modify it:  
✔ **Use it for creativity, personal projects, or learning**  
✔ **Give proper credit when using it in public**  
✔ **Respect the original creator’s work**  
❌ **DO NOT try to profit from free content**  

 **If I find people selling this project, I will take action to prevent unauthorized use.**  



## How It Works 

This project consists of two main pages:
1. A landing page with "Yes" and "No" buttons (`index.html`)
2. A date scheduler page (`yes.html`) that appears after clicking "Yes"

### Features:
- **Interactive Buttons**: The "No" button cycles through messages, while the "Yes" button grows in size
- **Date Scheduler**: Choose your preferred date and time for the date
- **WhatsApp Integration**: Automatically sends the chosen date via WhatsApp
- **Responsive Design**: Works on all screen sizes

---

## How to Use 

1. **Download the Files**:
   - Clone this repository or download the files:
     - `index.html`
     - `styles.css`
     - `yes.html`
     - `yes.css`
     - `script.js`

2. **Configure WhatsApp Number**:
   - Open `yes.html`
   - Locate the `shareToWhatsApp` function
   - Change the phone number in `https://wa.me/yournumber` to your desired WhatsApp number
   - Make sure to include the country code without any symbols or spaces

3. **Open the Project**:
   - Open `index.html` in your web browser

---

## Code Overview 

### Files:
- `index.html`: Main landing page
- `styles.css`: Styles for the landing page
- `yes.html`: Date scheduler page
- `yes.css`: Styles for the date scheduler
- `script.js`: Button interaction logic

### Key Functions:
- `handleNoClick()`: Changes "No" button text and increases "Yes" button size
- `handleYesClick()`: Redirects to the date scheduler
- `confirmDate()`: Saves the selected date
- `shareToWhatsApp()`: Sends the date via WhatsApp

---

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy 💖
