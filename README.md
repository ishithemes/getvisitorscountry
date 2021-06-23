# Get Website Visitor's Country Information
This is a simple JavaScript code that helps you get the country of the visitor on your website and use it to block or redirect visitors based on your requirement. The script basically is an AJAX code to cloudflare's API which shares information about the visitor from which we just extract the country code and use it for our purpose!

## Usage on a website
* Copy the <script> part of the [HTML](index.html) and paste it just before the **end of** HEAD tag of your website.
* Create a DIV element with id=countrycode-container as <div id="countrycode-container"></div> and place it anywhere on the HTML document where you want to show the country code
* Great! Now use the script to redirect / hide the content for visitors from some countries.
