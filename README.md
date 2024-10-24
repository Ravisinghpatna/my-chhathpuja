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
            text-align: center;
            padding: 20px;
            background-color: #ffcc00;
            border-radius: 10px;
            animation: fadeIn 1s ease-in;
        }
        h1 {
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
            width: 100%;
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
      font-size: 50px;
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
  </style>


</head>
<body>

<header>
    <h1 class="chhath_puja">Happy Chhath Puja!</h1>
    <h2>Bihar Most Awaited Chhath Puja Festival</h2>
    <p>Celebrate the festival of Chhath with joy and devotion.</p>
</header>

<div class="content">
    <h2>About Chhath Puja</h2>
    <p>Chhath Puja is an ancient Hindu festival dedicated to the Sun God (Surya) and Chhathi Maiya. It is primarily celebrated in the Indian states of Bihar, Jharkhand, Uttar Pradesh, and by the diaspora worldwide. The festival lasts for four days and involves various rituals, including fasting, offering prayers, and making offerings of traditional food to the Sun.</p>

    <h2>Significance</h2>
    <p>The festival is a time for families to come together and express gratitude for the blessings of health, wealth, and prosperity. Devotees believe that worshiping the Sun God during this festival brings happiness and prosperity to their lives.</p>

    <div class="image-container">
        <!-- <img src="./project-2/img/Chhath Puja Celebration.jpg" alt="">
        <img src="./project-2/img/Chhath Puja Celebration1.jpg" alt="">  -->   
    </div>

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
        <span class="highlight">@Ravi Singh</span>
    </div>
</div>

<script>
    // Trigger the animation after the page loads
    window.onload = function() {
        document.querySelector('.ravi').style.opacity = 1; // Make it visible
    };
</script>

<footer>
    <p>Wishing you and your family a prosperous Chhath Puja!</p>
</footer>

</body>
</html>
