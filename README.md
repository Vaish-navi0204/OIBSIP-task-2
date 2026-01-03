# OIBSIP-task-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adventure Booking</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f8ff;
        }

        /* Header Section */
        .header {
            background-image: url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee');
            background-size: cover;
            background-position: center;
            height: 60vh;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .header h1 {
            font-size: 50px;
            margin: 0;
        }

        .header p {
            font-size: 20px;
        }

        /* Booking Section */
        .booking {
            background: white;
            width: 80%;
            margin: -50px auto;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            border-radius: 10px;
        }

        .booking input, .booking select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .booking button {
            width: 100%;
            padding: 12px;
            background: #2a8cff;
            color: white;
            border: none;
            font-size: 18px;
            border-radius: 5px;
        }

        .section {
            padding: 40px;
            text-align: center;
        }

        .activities {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .card {
            width: 25%;
            background: white;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        .card h3 {
            margin: 10px 0;
        }

    </style>
</head>

<body>

    <!-- Header -->
    <div class="header">
        <h1>Adventure Booking</h1>
        <p>Your next adventure is waiting!</p>
    </div>

    <!-- Booking Form -->
    <div class="booking">
        <h2>Book Your Adventure</h2>
        <input type="text" placeholder="Enter Your Name">
        <input type="date">
        <select>
            <option>Select Activity</option>
            <option>River Rafting</option>
            <option>Mountain Trekking</option>
            <option>Forest Camping</option>
        </select>
        <button>Book Now</button>
    </div>

    <!-- Adventure Activities -->
    <div class="section">
        <h2>Popular Adventures</h2>
        <div class="activities">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e">
                <h3>Rafting</h3>
                <p>Enjoy a thrilling river experience.</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1500534314209-a25ddb2bd429">
                <h3>Trekking</h3>
                <p>Explore beautiful mountains.</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05">
                <h3>Camping</h3>
                <p>Spend the night under the stars.</p>
            </div>

        </div>
    </div>

</body>
</html>
