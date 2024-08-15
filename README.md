```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/asset/css/style.css">
    <title>Interview Qustions</title>
</head>
<style>
    *{
    margin: 0;
    box-sizing: border-box;
}
.head{
    width: 100%;
    height: 100px;
    background-color:#6495ED;
    z-index: 100;
    position: fixed;
    display: flex;
    justify-content: center;
    box-shadow: 0px 0px 10px 0px gray;
    align-items: center;
}
.head h1{
    color: aliceblue;
}
.body-main{
    position:relative;
    top: 100px;
    padding: 30px;
    width: 100%;
    height: 100%;
    background-color: #fffafa;
}
.body-main h2{
    margin-bottom: 10px;
    color: #494F55;
}
.body-main h3{
    margin-bottom: 20px;
    color: #494F55;

}

</style>
<body>
    <div class="container">
        <div class="head">
            <h1>Interveiw Qustions</h1>
        </div>
        <div class="body-main">
            <h2>Q1. What does HTML stand for?</h2>
            <h3>Answer: HTML stands for HyperText Markup Language.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q2. What is the purpose of the &lt;head&gt; tag in HTML?</h2>
            <h3>Answer: The &lt;head&gt; tag contains meta-information about the HTML document, such as the title, character set, linked CSS files, and scripts.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q3. What is the difference between a block-level element and an inline element?</h2>
            <h3>Answer: Block-level elements occupy the full width available and start on a new line (e.g., &lt;div&gt;, &lt;p&gt;), while inline elements only take up as much width as necessary and do not start on a new line (e.g., &lt;span&gt;, &lt;a&gt;).</h3>
        </div>
        
        <div class="body-main">
            <h2>Q4. How can you include comments in HTML?</h2>
            <h3>Answer: Comments in HTML are included using &lt;!-- This is a comment --&gt;.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q5. What is the purpose of the &lt;alt&gt; attribute in the &lt;img&gt; tag?</h2>
            <h3>Answer: The &lt;alt&gt; attribute provides alternative text for an image if it cannot be displayed. It improves accessibility for screen readers and provides context for images.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q6. What are semantic HTML elements?</h2>
            <h3>Answer: Semantic HTML elements clearly describe their meaning in a human- and machine-readable way. Examples include &lt;article&gt;, &lt;section&gt;, &lt;header&gt;, &lt;footer&gt;, and &lt;aside&gt;.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q7. How do you create a hyperlink in HTML?</h2>
            <h3>Answer: A hyperlink is created using the &lt;a&gt; tag with the href attribute, like so: &lt;a href="https://www.example.com"&gt;Click here&lt;/a&gt;.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q8. What is the difference between the &lt;div&gt; and &lt;span&gt; tags?</h2>
            <h3>Answer: &lt;div&gt; is a block-level element used for grouping content and layout purposes, while &lt;span&gt; is an inline element used for styling small chunks of content within a block.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q9. What is the use of the &lt;form&gt; element?</h2>
            <h3>Answer: The &lt;form&gt; element is used to create an HTML form for user input. It can contain various input elements like text fields, checkboxes, radio buttons, and submit buttons.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q10. How can you embed a video in an HTML page?</h2>
            <h3>Answer: You can embed a video using the &lt;video&gt; tag, like so: &lt;video controls src="video.mp4"&gt;&lt;/video&gt;.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q11. What is the purpose of the &lt;meta&gt; tag in HTML?</h2>
            <h3>Answer: The &lt;meta&gt; tag provides metadata about the HTML document, such as character encoding, viewport settings, and author information.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q12. How do you create a table in HTML?</h2>
            <h3>Answer: A table is created using the &lt;table&gt; tag, with rows defined by &lt;tr&gt;, headers by &lt;th&gt;, and data cells by &lt;td&gt;. Example:
            <pre><code>&lt;table&gt;
              &lt;tr&gt;
                &lt;th&gt;Header 1&lt;/th&gt;
                &lt;th&gt;Header 2&lt;/th&gt;
              &lt;/tr&gt;
              &lt;tr&gt;
                &lt;td&gt;Data 1&lt;/td&gt;
                &lt;td&gt;Data 2&lt;/td&gt;
              &lt;/tr&gt;
            &lt;/table&gt;</code></pre></h3>
        </div>
        
        <div class="body-main">
            <h2>Q13. What is the difference between &lt;strong&gt; and &lt;b&gt; tags?</h2>
            <h3>Answer: The &lt;strong&gt; tag indicates that its contents have strong importance and is often displayed as bold, while &lt;b&gt; simply applies bold styling without implying any importance.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q14. How do you specify the language of an HTML document?</h2>
            <h3>Answer: The language of an HTML document is specified using the lang attribute in the &lt;html&gt; tag, like so: &lt;html lang="en"&gt;.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q15. What is the difference between the &lt;input&gt; types "text" and "password"?</h2>
            <h3>Answer: The "text" type creates a single-line text input field, while the "password" type hides the text entered by the user for privacy.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q16. How do you create a list in HTML?</h2>
            <h3>Answer: HTML supports ordered lists (&lt;ol&gt;) and unordered lists (&lt;ul&gt;), with list items defined by &lt;li&gt;. Example:
            <pre><code>&lt;ul&gt;
              &lt;li&gt;Item 1&lt;/li&gt;
              &lt;li&gt;Item 2&lt;/li&gt;
            &lt;/ul&gt;</code></pre></h3>
        </div>
        
        <div class="body-main">
            <h2>Q17. What does the target="_blank" attribute do in a link?</h2>
            <h3>Answer: The target="_blank" attribute makes the link open in a new browser tab or window.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q18. How can you include external CSS in an HTML document?</h2>
            <h3>Answer: External CSS is included using the &lt;link&gt; tag in the &lt;head&gt;, like so: &lt;link rel="stylesheet" href="styles.css"&gt;.</h3>
        </div>
        
        <div class="body-main">
            <h2>Q19. What is the purpose of the id attribute in HTML?</h2>
            <h3>Answer: The id attribute provides a
