# Doqanh12.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Form Example</title>
    <style>
        input, textarea, button {
        width: 100%;
        font-size: 1.4rem;
        margin-bottom: 15px;
        padding: 10px;
        border: none;
        box-sizing: border-box; 
        }
    </style>
</head>
<body>
    <body>
    <h1>Contact Us</h1>
        <form method="post" action="/contact-form-data/">
            <input name="readername" type="text" placeholder="Name" required/>
            <input name="readeremail" type="email" placeholder="Email" required/>
            <textarea name="message" rows="5" cols="30" placeholder="Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </body>
</body>
</html> 
