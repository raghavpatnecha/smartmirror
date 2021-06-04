# Smart-Mirror-AI 🪞
Smart Mirror implementation using Artificial Intelligence 🤖

Watch the video on [here](https://www.youtube.com/watch?v=FZ486L4r7Bs)

# Setup 🖥️

## Open Source 🍊

1) [MichMich MagicMirror](https://magicmirror.builders/)
2) Follow the guide on [HackerHouseYT](https://github.com/HackerHouseYT/AI-Smart-Mirror) for basic setup. 

### Code Requirements 🦄
The example code is in Python ([version 2.7](https://www.python.org/download/releases/2.7/) or higher will work). 

 Copy the folders in `smartmirror/magic_mirror` to `MagicMirror` respective folders.

## Artificial Intelligence 🤖
 
We are using [wit.ai](https://wit.ai/) for generating intents out of the text.
You need to generate an access id using which, you can send GET requests to get intents.
Upload the ```models/Smart-Mirror.zip``` to wit.ai
Once you upload this data to wit.ai you can use the commands given below. You can also add your own custom commands to wit.ai.

## Weather ❄️

For weather we are using [darksky.net](https://darksky.net/).
You have to create your own developer account and get the API key.
- What's the weather forecast?

## Youtube 📺
For enabling youTube, you need to get the youTube secret Key from the Google's developer Console.
Add the key in the code.
- Can you play me a video of Eminem?

## Maps 🌏

For map, we are using Google maps. Types of map we support right now are :
1) Normal
2) Hybrid
3) Satellite
4) Terrain
- Can you show me map of India?

## News 📰

For news, we use Google news and the location has been set to IN (INDIA).
You can change it according o your country to get the latest news.
- Can you show me the latest news?

## Uber 🚕

You can directly book an uber and get the arrival map using this module.
You need to get the API Key, Client Secret, Oauth Key and paste it in the code.
- Can you book me an uber pool/go from Vimaan Nagar to Baner?

## Zomato 🍕

For zomato, you need to get the API key from zomato's dev site.
And paste it in the code. 
You can view the list of available restaurants in a region.
- Can you show me restaurants in Pune?

## SoundHound 🔊

For various other tasks, we have used soundhound's api. The soundhound service is quite effective and fast. Operations that could be done using soundhound:
1) Solving Mathematical equations. What are the roots for x^2-x+1
2) Stock Market :What are the stock prices and market cap of Google, Apple and Microsoft.
3) Hotel Enquiries : Can you show me hotels in New York that have a swimming pool for next Monday?
4) Wikipedia : Who's Sachine Tendulkar?

### Open and Close Module.
   #### Example command for opening and closing module.
   1) Can you open the bitcoin module.
   2) Can you close the mail module.


## API 💳

Different APIs have been used for different services. You are required to create an account and get the respective keys from the providers.
You have to place the keys in the code.
The instructions for the same are given in the code.


## Starting Up 🎫
 
Navigate to the smartmirror folder
```shell
cd smartmirror
```

Make sure MagicMirror is running, then start the AI
```shell
python bot.py
```

## Contribute 🦮
Feel free to contribute.Although I have tried to added most of the apis including youtube,uber,zomato,hound but I would appreciate if someone add a spotify or soundcloud api for music player integration. Also, if someone could add a pause & play command for the youtube videos.

## Results 📊

<img src="https://github.com/akshaybahadur21/Smart_Mirror/blob/master/smart_mirror.gif">



 
