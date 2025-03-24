<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunova Solar</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #ffffff; }
        .container { width: 80%; margin: auto; text-align: center; padding: 20px; }
        .header { background-color: #00274d; color: white; padding: 20px; text-align: center; }
        .logo-container { display: flex; justify-content: center; align-items: center; }
        .logo-container img { max-width: 300px; height: auto; }
        .cta-button { background-color: #ffcc00; color: #00274d; padding: 15px 25px; border: none; cursor: pointer; text-decoration: none; font-size: 18px; font-weight: bold; border-radius: 5px; }
        .cta-button:hover { background-color: #e6b800; }
        .form-container { background: #f8f9fa; padding: 30px; margin-top: 20px; border-radius: 10px; box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1); }
        input, button { width: 100%; padding: 10px; margin: 10px 0; border-radius: 5px; border: 1px solid #ddd; }
        button { background-color: #ffcc00; color: #00274d; font-size: 16px; font-weight: bold; }
        button:hover { background-color: #e6b800; }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo-container">
            <img src="Youtube Cover Photo.png" alt="Sunova Solar Logo">
        </div>
    </div>
    
    <div class="container">
        <h2>Get a Free Solar Quote</h2>
        <p>Fill out the form below to see if you qualify for solar savings.</p>
        
        <div class="form-container">
            <form action="#" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone Number" required>
                <input type="text" name="address" placeholder="Your Address" required>
                <button type="submit" class="cta-button">Get My Free Quote</button>
            </form>
        </div>
    </div>
</body>
</html>
