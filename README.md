# alexa-show-me-guest-wifi
Sample code in Home Assistant for "Alexa, show me guest WiFi" automation

Live demo video: https://fb.watch/9sDyt1P7qP/

The code goes into Home Assistant config and the Home Assistant is installed in the Raspberry Pi attached to pi-topCEED; https://shop.pi-top.com/products/pi-topceed

You need to create an image file (1920 x 1080px resolution) which contain the WiFi QR code and upload it to /config/www folder. Once you uploaded it, you should be able to view at http://[home assistant IP and port]/local.[your image filename]

You can use this site to generate your WiFi QR code; https://www.qr-code-generator.com/solutions/wifi-qr-code/

Once you have uploaded the code, you just need to add the script to Alexa. If you are using Nabu Casa, just add the script entity in the cloud configuration in your Home Assistant. Once you have done that, let Alexa rediscover the new entity.

Finally, you just need to create a new Routine in your Alexa app...

![IMG_20211123_212933](https://user-images.githubusercontent.com/94909655/143032963-e1b6a240-299f-4a1e-b3f9-cf3918ff896a.jpg)
