# Step-by-Step Guide to Launching the Script and Extracting Information

Firstly, craft your script. Open the terminal and install the necessary packages:
- pip install dash
- pip install dash-bootstrap-components


Next, paste the contents of the script, save the file, and from the terminal, navigate to the folder where you saved the script. Then execute the command:</br>
· python3 amazon.py


Upon successful execution, the console will display the following IP address:</br>
· http://127.0.0.1:8050/

Visit this address, input the link you wish to scrape - for instance, "https://www.amazon.com/s?k=graphics+cards&crid=13IJRSH8S6KMP&sprefix=%2Caps%2C264&ref=nb_sb_ss_recent_1_0_recent", and click on "Fetch".

This will return a listing of all the products you're interested in. By clicking "Download", you can download the CSV file to work with.


If you encounter this error, it means that your IP address has been banned, and as a result, you are unable to continue performing Web Scraping on this website:</br>
· Error during scraping: 503 Server Error: Service Unavailable for url: https://www.amazon.com/s?k=tarjetas+gr%C3%A1ficas&crid=13IJRSH8S6KMP&sprefix=%2Caps%2C264&ref=nb_sb_ss_recent_1_0_recent
