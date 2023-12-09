<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Invitation</title>
    <style>
        body {
            font-family: 'Dancing Script', cursive; /* Changing to a fancy font */
            text-align: center;
            margin: 0;
            padding: 0;
            background: url('image.png') no-repeat center center fixed;
            background-size: cover;
        }
        .invitation {	
            background-color: rgba(255, 255, 255, 0.8);
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-family: 'Alex Brush', cursive;
            color: #333;
        }
        h2 {
            font-family: 'Alex Brush', cursive;
            color: #333;
            font-size: 3em;
        }
        p {
            color: #666;
        }
        .details {
            background-color: #f9f9f9;
            padding: 10px;
            margin-top: 20px;
            border-radius: 4px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            margin-top: 20px;
        }
        video {
            max-width: 100%;
            border-radius: 4px;
            margin-top: 20px;
        }
    </style>
    <!-- Link to Alex Brush font from Google Fonts -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Alex+Brush&display=swap">
    <!-- Link to Dancing Script font from Google Fonts -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400&display=swap">
</head>
<body>

    <div class="invitation">
        <h1>Greetings!</h1>
        <p>You are cordially invited to the wedding of</p>
        <h2>Mifraah & Shaufa</h2>
        <p>On</p>
        <p>Date: Wednesday, January 1, 2025</p>
        <p>Time: 08:30 PM</p>
        <p>Location: Boduharuge, Sosun Magu, L. Hithadhoo</p>

        <div class="details">
            <!-- Additional details here -->
        </div>

        <video controls>
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>

        <img src="colour pallet.png" alt="Wedding Venue Image">

    </div>

</body>
</html>
