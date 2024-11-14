# What is this?

This is a simple tool to visualize base64 encoded polylines on Google Maps

# How to use?

1. Git clone this repository
   `git clone git@github.com:venu-ion/google-map-polyline-simulator.git`
3. Open the `polyline.html` file in your browser
4. Generate a google maps api key if you haven't already [^1]
5. Paste the (secret) google maps api key and click `load map`
6. Paste the *(base64) decoded*[^2] polyline string and click `update map`

If everything went well, you should see be able to see the polyline rendered on the world map in red. 

![image](https://github.com/user-attachments/assets/4b5c99b6-7189-429b-861d-1bd18a98916e)
|:--:|
A screenshot of polyline render in action


[^1]: One should be able to generate an api key using [the developers guide](https://developers.google.com/maps/documentation/javascript/get-api-key) 
[^2]: To quickly decode a base64 encoded polyline string, use https://smolkit.com/decode/base64/ for free in your browser.
