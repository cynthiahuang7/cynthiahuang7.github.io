---
layout: base
title: About
permalink: /about/
---

<head>
    <title>About Me</title>
    <style>
        .container {
            display: flex;
            align-items: flex-start;
        }
        .profile-photo {
            margin-top: 40px;
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-right: 30px; /* Adds space between the photo and the text */
        }
        .content {
            max-width: 500px; /* Adjust the width as needed */
        }
        /* Additional styles can be added as needed */
    </style>
</head>
<body>
    <div class="container">
        <div>
            <img src="{{ site.baseurl }}/assets/images/about.jpg" alt="Your Name" class="profile-photo">
        </div>
        <div class="content">
            <p>Cynthia Huang is a Senior Product Manager at Borealis AI, focusing on capital markets initiatives and LLM-powered products. She is also pursuing a part-time PhD at the University of Waterloo, under the supervision of Pascal Poupart. Her research primarily explores multi-agent reinforcement learning and cooperative AI. </p>
            <p>Previously, Cynthia gained six years of experience in capital markets. She started her career as a quantitative trader, developing market-making trading strategies and portfolio risk management algorithms for equities. Later, she led a team of AI engineers and quantitative trading analysts to design and create algorithms for liquidity-seeking strategies, utilizing multi-objective reinforcement learning.</p>
        </div>
    </div>
</body>



