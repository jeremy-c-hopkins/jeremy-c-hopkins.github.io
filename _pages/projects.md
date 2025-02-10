---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from:
  - /projects.html
---

<div class="projects">
    <div class="card">
        <details>
            <summary>Stock Data Analysis & Collection</summary>
            <p markdown="1">
                With the large availability of **free data** related to the stock market, it's becoming much easier for **retail investors** to have access to the information they need. However, **return on investment** on average is **lower** than it has ever been for these same individuals. This is theorized to be due to all the extra "information" that is being published. With **media** more focused on **click rates** and **retention**, the quality of information may have decreased. 
                <br>
                <br>
                My goal is to **numerically assess** the value of an **equity**, and publish the **code** base and **data** used to come to this calculation for **public** use. This may eventually be wrapped into one code **package**, however, the current focus is on **accuracy** and low **computation time**. Outside of generally producing quality predictions and collecting useful data, I also hope to develop a solid method of passing data between spreadsheets and code to utilize the strengths of both styles of research. 🚀 
            </p>

            <a href="https://github.com/jeremy-c-hopkins/Stock-Data">
                <img src="https://github-link-card.s3.ap-northeast-1.amazonaws.com/jeremy-c-hopkins/Stock-Data.png" width="460px">
            </a>

        </details>
    </div>

    <br>

    <div class="card2">
        <details>
            <summary>Astrodynamics</summary>
            <p markdown="1">
                Text
            </p>

            <a href="https://github.com/jeremy-c-hopkins/StockData">
                <img src="https://github-link-card.s3.ap-northeast-1.amazonaws.com/jeremy-c-hopkins/StockData.png" width="360px">
            </a> 

        </details>
    </div>
</div>

<style>
details {
  border-radius: 13px;
  overflow: hidden;
}

.card a{
    display: block;
    text-align: center;
    margin: 10px auto;
}

.card2 a{
    display: block;
    text-align: center;
    margin: 10px auto;
}

summary {
  font-size: 1.2rem;
  font-weight: bold;
  cursor: pointer;
  padding: 15px 15px 15px 15px; 
  background-image: linear-gradient(to right,rgb(162, 207, 251),rgb(113, 255, 250));
  color: #494E52;
  /* transition: background 0.6s ease-in-out; */
  position: relative;
  list-style: none;
}

summary:hover {
    background:rgb(207, 207, 207);
}

summary::marker, summary::-webkit-details-marker {
  display: none;
}

summary::after {
  content: "";
  position: absolute;
  right: 15px;
  top: 50%;
  width: 16px;
  height: 16px;
  background: url('/images/arrow.svg') no-repeat center center;
  background-size: contain;
  transform: translateY(-50%) rotate(0deg); /* Initially pointing right */
  transition: transform 0.3s ease;
}

details[open] summary::after {
  transform: translateY(-50%) rotate(90deg); /* Pointing downward */
}

p{
    padding: 30px 30px 30px 30px;
}
</style>
