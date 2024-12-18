<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chhath Puja Festival</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        header {
    width: 100%; /* Set a width to control the row span */
    max-width: 800px; /* Limit the maximum width */
    margin: 0 auto; /* Center the header */
    text-align: center;
    padding: 20px;
    background-color: #ffcc00;
    border-radius: 10px;
    animation: fadeIn 1s ease-in;
}

/* Medium screens (tablets) */
@media (max-width: 768px) {
    header {
        width: 80%;
        padding: 15px;
        font-size: 1.2em;
    }
}

/* Small screens (phones) */
@media (max-width: 480px) {
    header {
        width: 90%;
        padding: 10px;
        font-size: 1em;
        border-radius: 5px;
    }
}


        h1 {
            text-align: center;
            font-size: 2.5em;
            color: #8B4513; /* Dark brown color for heading */
            animation: slideIn 1s ease-in;
        }
        .content {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease-in;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        img {
            width: auto;
            max-width: 500px;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        img:hover {
            transform: scale(1.05);
        }
        footer {
            text-align: center;
            padding: 10px;
            margin-top: 20px;
            color: #555;
        }

        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            from {
                transform: translateY(-20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes drop {
            0% {
                top: -50px; /* Start above */
                opacity: 1;
            }
            100% {
                top: 200px; /* Drop to this position */
                opacity: 0; /* Fade out */
            }
        }
    </style>

<style>
    .chhath_puja, .ravi {
        font-size: 2.5em;
      font-weight: bold;
      background: linear-gradient(to right, #ff416c, #ff4b2b);
      -webkit-background-clip: text;
      color: transparent;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
      animation: multicolor-blink 2s infinite;
    }

    @keyframes multicolor-blink {
      0% {
        opacity: 1;
        text-shadow: 0 0 5px red, 0 0 5px orange, 0 0 5px yellow;
      }
      25% {
        opacity: 1;
        text-shadow: 0 0 5px green, 0 5px blue, 0 0 5px indigo;
      }
      50% {
        opacity: 1;
        text-shadow: 0 0 5px violet, 0 0 5px purple, 0 0 5px pink;
      }
      75% {
        opacity: 0.5;
        text-shadow: 0 0 5px cyan, 0 0 5px lime, 0 0 5px magenta;
      }
      100% {
        opacity: 1;
        text-shadow: 0 0 5px red, 0 0 5px orange, 0 0 5px yellow;
      }
    }

    .logo-image {
    position: absolute; /* Keeps the image positioned absolutely */
    top: 5px; /* Adjust the space from the top */
    left: 50%; /* Center horizontally */
    transform: translateX(-50%); /* Shift back by half the width of the image */
    width: 70px; /* Adjust the width of the image */
    height: auto; /* Maintain aspect ratio */
    }
        h1 {
            color: #ffd700;
            font-size: 3.5em;
            text-shadow: 4px 4px 8px #ff9900;
            margin-bottom: 40px;
        }

        .countdown-container {
    display: flex;
    flex-wrap: wrap; /* Allows wrapping on smaller screens */
    justify-content: center; /* Center flex items horizontally */
    max-width: 840px; /* Maximum width for the container */
    margin: 0 auto; /* Center the container within its parent */
    gap: 10px; /* Space between items */
    padding: 20px; /* Padding inside the container */
}

/* Medium screens (tablets) */
@media (max-width: 768px) {
    .countdown-container {
        gap: 8px; /* Reduce gap slightly for tablets */
    }
}

/* Small screens (phones) */
@media (max-width: 480px) {
    .countdown-container {
        gap: 5px; /* Further reduce gap for small screens */
        padding: 10px; /* Reduce padding for small screens */
    }
}

        .countdown-box {
        flex: 1;
        min-width: 100px;
        max-width: 200px;
        background: rgba(255, 215, 0, 0.1);
        border: 3px solid rgba(255, 215, 0, 0.7);
        border-radius: 12px;
        padding: 20px;
        text-align: center;
        box-shadow: 0 8px 16px rgba(255, 165, 0, 0.5);
    }

        .countdown-box h2 {
            font-size: 3.5em;
            margin: 0;
            color: #ffdd44;
            text-shadow: 3px 3px 6px rgba(255, 165, 0, 0.8);
        }

        .countdown-box p {
            font-size: 1.5em;
            color: #f4e2c1;
            margin: 0;
            font-weight: bold;
        }

        .countdown-end-message {
            color: #ffd700;
            font-size: 2.5em;
            font-weight: bold;
            margin-top: 50px;
            text-shadow: 4px 4px 10px rgba(255, 165, 0, 0.8);
        }
  
  </style>

</head>
<body>
    <h1>Countdown to Chhath Puja 2024</h1>
    <div class="countdown-container">
        <div class="countdown-box">
            <h2 id="days"></h2>
            <p>Days</p>
        </div>
        <div class="countdown-box">
            <h2 id="hours"></h2>
            <p>Hours</p>
        </div>
        <div class="countdown-box">
            <h2 id="minutes"></h2>
            <p>Minutes</p>
        </div>
        <div class="countdown-box">
            <h2 id="seconds"></h2>
            <p>Seconds</p>
        </div>
    </div>

    <div id="message" class="countdown-end-message"></div>

    <script>
        // Set the date for the countdown (5th November 2024)
        var countDownDate = new Date("Nov 5, 2024 00:00:00").getTime();

        // Update the countdown every 1 second
        var countdownFunction = setInterval(function() {
            // Get today's date and time
            var now = new Date().getTime();

            // Find the distance between now and the countdown date
            var distance = countDownDate - now;

            // Calculate time components
            var days = Math.floor(distance / (1000 * 60 * 60 * 24));
            var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            var seconds = Math.floor((distance % (1000 * 60)) / 1000);

            // Display the results in the respective HTML elements
            document.getElementById("days").innerHTML = days;
            document.getElementById("hours").innerHTML = hours;
            document.getElementById("minutes").innerHTML = minutes;
            document.getElementById("seconds").innerHTML = seconds;

            // If the countdown is finished, display a message
            if (distance < 0) {
                clearInterval(countdownFunction);
                document.querySelector('.countdown-container').style.display = 'none';
                document.getElementById("message").innerHTML = "Blessed Chhath Puja!";
                document.getElementById("message").style.paddingTop = "25px";
            }
        }, 1000);
    </script>


<header>

    <img src="https://raw.githubusercontent.com/Ravisinghpatna/my-chhathpuja/main/logo-removebg.png" alt="image not found" class="logo-image" id="logo">
    <h1 class="chhath_puja">Happy Chhath Puja!</h1>
    <h2>Bihar Most Awaited Chhath Puja Festival</h2>
    <p>Celebrate the festival of Chhath with joy and devotion.</p>

</header>
<script>
    document.getElementById('logo').addEventListener('click', function() {
        this.style.display = 'none'; // Hides the image
    });
</script>
    
<div class="content">
    <h2>About Chhath Puja</h2>
    <p>Chhath Puja is an ancient Hindu festival dedicated to the Sun God (Surya) and Chhathi Maiya. It is primarily celebrated in the Indian states of Bihar, Jharkhand, Uttar Pradesh, and by the diaspora worldwide. The festival lasts for four days and involves various rituals, including fasting, offering prayers, and making offerings of traditional food to the Sun.</p>

    <h2>Significance</h2>
    <p>The festival is a time for families to come together and express gratitude for the blessings of health, wealth, and prosperity. Devotees believe that worshiping the Sun God during this festival brings happiness and prosperity to their lives.</p>

   <p>Chhath Puja is a major Hindu festival dedicated to the Sun God (Surya) and Chhathi Maiya (Goddess Usha). The festival is celebrated over four days, primarily in Bihar, Jharkhand, and Uttar Pradesh, as well as in Nepal and parts of India where Bihari communities live. Each day of the festival holds specific rituals:</p>

<h2> Day 1: Nahay Khay (First Day) Significance: </h2>
<p>The devotees begin the festival by cleaning their homes and surroundings. They take a holy dip in a river, preferably in the Ganges, and bring home the sacred water to prepare food.
    Rituals: Devotees cook a simple meal consisting of rice, lentils, and pumpkin curry (Kaddu Bhaat) in earthen or brass utensils, following strict purification practices. This marks the beginning of the fast.</p>

<h2> Day 2: Kharna and Lohanda (Second Day) Significance:</h2>
<p>The second day is a day of fasting, where devotees abstain from food and water for the entire day.
    Rituals: The fast is broken in the evening after offering prayers to the Sun God with a special meal called Kharna, which consists of sweet dishes like kheer (made with jaggery, rice, and milk), puris, and bananas. After this, the main 36-hour fast begins without water.</p>

<h2> Day 3: Sandhya Arghya (Third Day) Significance:</h2>
<p>This is the most important day of Chhath Puja. Devotees gather at the riverbank in the evening to offer the first Arghya (offering) to the setting sun.
    Rituals: Devotees prepare a basket of fruits, sugarcane, and sweets. The worshippers stand in water and offer Arghya to the setting sun, praying for the well-being of their family and the fulfillment of wishes.</p>

<h2> Day 4: Paran or Suryodaya Arghya (Fourth Day) Significance:</h2>
<p> The final day of Chhath Puja involves offering prayers to the rising sun.
    Rituals: Devotees gather at the riverbank before sunrise to offer Usha Arghya (offering to the rising sun). After this, the devotees break their 36-hour fast by consuming Prasad, which marks the end of the festival.</p>

    <h2>Rituals</h2>
    <ul>
        <li>Fasting for the entire day.</li>
        <li>Gathering at riverbanks or ponds for prayer.</li>
        <li>Offering 'Thekua' and other traditional sweets to the Sun God.</li>
        <li>Performing 'Arghya' (offering of water) to the setting and rising sun.</li>
    </ul>

    <div class="image-container">
        <h2>Offering Water to the Sun</h2>
        <div class="water-drop">    
            <img src="https://media.giphy.com/media/oAG0dBPv5SNucy8o09/giphy.gif" alt="Offering Water to the Sun" />        
            <img src="https://media.giphy.com/media/sKErYb0IWKzWiKPq6c/giphy.gif" alt="Offering Water to the Sun" />
            <img src="https://media.giphy.com/media/qd1ihzDLVnYz1xlLzs/giphy.gif" alt="Offering Water to the Sun" />
        </div>
    </div>

    <div class="ravi">
        <span class="highlight">@the_ravisingh27</span>
    </div>
</div>
<footer>
    <p>Wishing you and your family a prosperous Chhath Puja!</p>
</footer>

</body>
</html>
