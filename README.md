# Horiseon Webpage Development - Week 1 Homework

<img src="Assets\images\horiseonlogo.JPG" alt="Horiseon Logo">

## Desciption

> Horiseon wanted updating to thier website so that it follows better accessibilty standards and is optimized for search engines. This required adding alt attributes, updating scipt, consolidating the selectors and properties for the css and organising them to follow the semantic structure of the HTML elements. 

## Portion Of Code Prior To Changes

```md
<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="hero"></div>
    <div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </div>
```

## Portion Of Code After Changes

```md
 <body>
        <header>
            <h1>Hori<span class="seo">seo</span>n</h1>
                <nav>
                    <ul>
                        <li><a href="#search-engine-optimization">Search Engine Optimization</a></li>
                        <li><a href="#online-reputation-management">Online Reputation Management</a></li>
                        <li><a href="#social-media-marketing">Social Media Marketing</a></li>
                    </ul>
                </nav>
        </header>
        <div class="hero">
        </div>
        <main>
            <div class="service" id="search-engine-optimization">
                <img src="./assets/images/search-engine-optimization.jpg" alt="Notebook with search engine optimization concepts on cover, placed on a cluttered wooden table." class="float-left" />
                <h2>Search Engine Optimization</h2>
                <p>
                    The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
                </p>
            </div>
            <div class="service" id="online-reputation-management">
                <img src="./assets/images/online-reputation-management.jpg" alt="Person checking cell phone while looking at a laptop showing a graph of increasing online reputation." class="float-right" />
                <h2>Online Reputation Management</h2>
                <p>
                    The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
                </p>
            </div>
                <div class="service" id="social-media-marketing">
                <img src="./assets/images/social-media-marketing.jpg" alt="View from above of a group of people sitting around a table cluttered with social media icons and actions such as Tweet, Share, and Like." class="float-left" />
                <h2>Social Media Marketing</h2>
                <p>
                    Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
                </p>
            </div>
        </main>
```

## Website Screen Shot

><img src="Assets\01-html-css-git-homework-demo.png" alt="Horiseon Webpage Screenshot">

## Installation

> This website doesnt require installation of any programs or software. It can be viewed on any web browser. It is now live at the following URL . We are just waiting for confirmation from the client that they are happy with the changes or to see if they would like to make any additional changes.

## Built With

> [Visual Studio Code](https://code.visualstudio.com/)

## Author

> Brenton Turnor - [https://github.com/BT134](https://github.com/BT134)

## Project Status

> Website is currently live. Waiting for client approval and notification if any changes need to be made. 

## Contact 

> Brenton Turnor [@BTurnor](https://twitter.com/BTurnor) - brenton.turnor@hotmail.com

> Project Link: [https://github.com/BT134/fuzzy-disco](https://github.com/BT134/fuzzy-disco)
