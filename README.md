## **🎓 CSS Basics Assignment**  

### **Assignment Title**  
**"Mastering CSS Basics: Styling Your First Web Page"**  

---

### **📋 Objectives**  
- Understand the use of CSS selectors, properties, and values.  
- Apply inline, internal, and external CSS to style web pages.  
- Utilize basic CSS properties to control colors, fonts, alignment, padding, and margins.  

---

### **📂 Assignment Tasks**  

#### **Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)**  
1. Create an HTML file with at least three different types of elements (e.g., `<h1>`, `<p>`, `<div>`).  
2. Style these elements using:  
   - **Element Selector**: Change the font size of all headings.  
   - **Class Selector**: Apply a background color to specific sections.  
   - **ID Selector**: Add a border to an element with a unique ID.  

---



#### **Part 2: Inline, Internal, and External CSS (30 Points)**  
1. Use **inline CSS** to style one element (e.g., change the text color).  
2. Add **internal CSS** in the `<style>` tag within the `<head>` section to style at least three elements.  
3. Create a separate **external CSS file** and link it to your HTML. Use it to:  
   - Change the background color of the webpage.  
   - Style links with hover effects.  

---

#### **Part 3: Basic Styling Properties (50 Points)**  
1. Apply the following styles:  
   - **Colors**: Set text and background colors for different elements.  
   - **Font Styles**: Change the font family, size, and weight of text.  
   - **Text Alignment**: Center-align, left-align, or justify text in paragraphs.  
   - **Spacing**: Add padding and margin to elements for proper spacing.  

2. Create a **simple card component** using these styles:  
   - A heading for the card title.  
   - A paragraph with some description.  
   - Add padding inside the card and a margin around it.  
   - Use a light background color and a subtle border.  

```

This assignment will solidify your CSS basics while giving you a chance to style your first webpage creatively. Good luck and happy styling! 🎨🚀


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling </title>
    
    <style>
        h1, h2, h3 {
            font-size: 2em;
            font-family: Arial, sans-serif;
        }

        .highlight {
            background-color: #f0f8ff;
            padding: 15px;
        }

        #unique {
            border: 2px solid #ff6347;
            padding: 15px;
            margin: 10px 0;
        }
        .card {
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin: 20px auto;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
            width: 50%;
        }

        .card-title {
            font-size: 1.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .card-description {
            font-family: 'Georgia', serif;
            text-align: justify;
            color: #555;
        }
    </style>
   
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <h1>Welcome to My Webpage</h1>
    <h2>portfolio</h2>

    <div class="highlight">
        <p>My name is valarine i am currectly learnng at Safaricom PlP</p>
    </div>

    <div id="unique">
        <p>Key Aspects of Lifestyle:.</p>
    </div>

    <p style="color: blue;">This paragraph is styled using inline CSS to change the text color.</p>

    <div class="card">
        <h3 class="card-title">Card Title</h3>
        <p class="card-description"> This card has padding inside, a margin around it, a light background color, and a subtle border.</p>
    </div>

</body>
</html>
