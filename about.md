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
            <p>Cynthia Huang is a Senior Product Manager at Borealis AI, focusing on capital markets initiatives and language model-powered products. She is also pursuing a part-time PhD in Computer Science at the University of Waterloo, under the supervision of <a href="https://cs.uwaterloo.ca/~ppoupart/">Pascal Poupart</a>. Her research explores multi-agent reinforcement learning and cooperative AI. </p>
            <p>Previously, Cynthia gained six years of experience in capital markets. She started her career as a quantitative trader, developing market-making trading strategies and portfolio risk management algorithms for equities. Later, she led a team of AI engineers and quantitative trading analysts to design and build algorithms that leverage multi-objective reinforcement learning for liquidity-seeking strategies.</p>
            <!-- Academic Publications -->
            <h4 style="text-decoration: underline;">Research Projects: </h4>
            <ul>
                <li>
                    <p>Approximating Human-Like Few-Shot Learning using GPT-based Compression, Cynthia, H. & Yuqing, X. & Zhiying, J. & Jimmy, L. & Ming, L. Aug 2023. arXiv Preprint.</p>
                </li>
                <li>
                    <p>Defensive Collaborative Learning: Protecting Objective Privacy in Data Sharing: Extended Abstract, Cynthia, H & Pascal P. May 2023. AAMAS 2023.</p>
                </li>
            </ul>
        </div>
    </div>
</body>



