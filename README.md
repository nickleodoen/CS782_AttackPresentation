# CS782_AttackPresentation
Attack Presentation Demo files for CS 782 Computer Security and Privacy

The repository contains 3 files - ```checking.html```, ```social_media.html```, and ```clickjacking.html```.

- ```checking.html``` is to check whether a given website is vulnerable to clickjacking. Just paste the url of the website into the iframe in the HTML file and see it the website loads.
- ```social_media.html``` is a mock social media website for demonstration purposes. It contains a post and a like button. Upon clicking the like button, an alert is displayed to the user.
- ```clickjacking.html``` is the actual clickjacking demo webpage. It's a fake webpage that contains a button enticing the user to click it to win prizes. The iframe containing ```social_media.html``` is embedded into the webpage. Change the opacity of the iframe for the demo.

To run this, in the terminal, change your directory ```cd CS782_AttackPresentation```. Then run a python HTTP local server by running the ```python3 -m http.server``` inside this directory. You then should be able to go to ```https://localhost:8000``` and click on the webpage your want to view.
