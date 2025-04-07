# Chhota Helper - Bachchon Ka Project Buddy

**Chhota Helper** ek web-based chatbot hai jo class 1 se 8 ke bachchon ke liye banaya gaya hai. Yeh unhe kisi bhi subject ya topic pe projects banane mein madad karta hai – text, chart, aur image ideas ke saath. Iska design colorful aur fun hai, aur yeh Hindi aur English dono mein kaam karta hai. Saath hi, bachchon ki mental health ka dhyan rakhta hai aur stress detect karte hi motivation deta hai.

---

## Features
- **Har Topic Pe Jawab**: Wikipedia API ke saath, koi bhi topic pe project ideas milte hain.
- **Class Level Customization**:  
  - Class 1-2: Simple aur chhote jawab.  
  - Class 3-5: Medium detail.  
  - Class 6-8: Detailed content.
- **Output Options**: Text explanation, chart ideas, aur image suggestions.
- **Language Support**: Hindi aur English mein toggle kar sakte ho.
- **Mental Health**: Stress words (jaise "mushkil", "darr") pe positive messages.
- **Fun Design**: Bachchon ke liye colorful layout, animations, aur easy UI.

---

## Tech Stack
- **HTML**: Structure aur layout ke liye.
- **CSS**: Colorful design aur animations (bounce, slide-in).
- **JavaScript**: Chatbot logic aur Wikipedia API integration.
- **Wikipedia API**: Real-time topic info fetch karne ke liye.

---

## Kaise Chalayein?
### Requirements
- Koi bhi modern web browser (Chrome, Firefox, etc.).
- Internet connection (Wikipedia API ke liye).

### Steps
1. **Download**:  
   - Code ko `chhota_helper_wiki.html` naam se save karo.
2. **Open**:  
   - File ko browser mein kholo (double-click ya drag karke).
3. **Input Do**:  
   - Format: `Class [number], [Subject], [Topic], [text/chart/image]`  
   - Example: `Class 5, Science, Volcano, text aur chart`
4. **Interact**:  
   - "Send" button dabao ya Enter key use karo.
   - Language toggle ke liye "Hindi"/"English" button dabao.

---

## Example Usage
### Input
```
Class 5, Science, Volcano, text aur chart
```
### Output
```
Bot: Wait a sec, I’m searching...
Bot: Hello, chhote dost! Yeh raha tumhara Volcano ka project (Class 5):
Text: A volcano is an opening in the Earth's crust where molten lava, ash, and gases escape. They are often found where tectonic plates meet. Some volcanoes are active and can erupt.
Chart: Volcano ka ek chitra banao.
```

### Input (Hindi Mode)
```
Class 3, Maths, Fractions, text mushkil hai
```
### Output
```
Bot: हाय, छोटे दोस्त! ये रहा तुम्हारा Fractions का प्रोजेक्ट (क्लास 3):
Text: Fractions के 3 उदाहरण लिखो।
मज़े करो, तुम सबसे अच्छा प्रोजेक्ट बनाओगे!
```

---

## Project Structure
- **`chhota_helper_wiki.html`**: Ek hi file mein pura code – HTML, CSS, aur JavaScript.
  - **HTML**: Chatbox aur input area.
  - **CSS**: Styling aur animations.
  - **JavaScript**: Chatbot logic, API calls, aur dynamic responses.

---

## Kaise Kaam Karta Hai?
1. **Input Parsing**: User ka input (class, subject, topic, output type) samajhta hai.
2. **Database Check**: Pehle pre-loaded database mein topic dhundta hai.
3. **API Call**: Agar topic nahi milta, toh Wikipedia API se info fetch karta hai.
4. **Fallback**: API fail ho toh generic templates use karta hai.
5. **Response**: Class level ke hisaab se adjust karke text/chart/image deta hai.
6. **Mental Health**: Stress detect karke motivation add karta hai.

---

## Customization
- **Naye Subjects**: `subjectsDb` object mein aur topics add karo.
- **Hindi Translation**: Wikipedia ke English content ko Hindi mein translate karne ke liye Google Translate API add kar sakte ho.
- **Design**: CSS mein colors, fonts, ya animations change karo.
- **Offline Mode**: API bina kaam ke liye `genericTemplates` ko expand karo.

---

## Limitations
- **Internet**: Wikipedia API ke liye net chahiye.
- **Hindi**: Abhi API se Hindi content nahi aata, placeholder use hota hai.
- **Speed**: API call thodi slow ho sakti hai.

---

## Future Improvements
- **Voice Input**: Mic se input lene ka feature.
- **More APIs**: OpenAI ya Google Search API ke saath aur smart content.
- **Sound Effects**: Button clicks pe fun sounds.
- **Backend**: Node.js ya Flask se server-side database connect karna.

---

## Credits
- **Built By**: WebTech Infinity - https://www.webtechinfinity.com
- **Inspiration**: Bachchon ke liye ek fun aur helpful tool banane ka khayal.
