# interactive touchscreen kiosk

This repository offers touchscreen user-interface templates for interactive kiosk displays. Please fork repository and comment/push useful changes upstream.  

## **Hardware/Software Requirements**

### ACER T272HL LCD Touchscreen Monitor

* 1920x1080
* HDMI Cable
* USB Keyboard Cable

### Chromebook 

* Lenovo 3100 2-in-1 Touchscreen (7 qty)(1366 x 768)
* Lenovo 110e (5 qty) (1366 x 768)
* Lenovo Duet Touchscreen (15 qty)(USB-C only. Requires Dongle) (1920 x 1200)

(potential local storage will depend on file size.)
[Pitt Wireless Chromebook Configuration](https://www.technology.pitt.edu/help-desk/how-to-documents/pittnetwireless-configuring-acer-and-samsung-chromebooks) 

**Powerwash Chromebook**

1. Sign out of your Chromebook.
2. Press and hold Ctrl + Alt + Shift + r.
3. Select Restart.
4. In the box that appears, select Powerwash. Continue.
5. Follow the steps that appear and sign in with your   Google Account. ...
Once you've reset your Chromebook:

###Connecting to Pitt Net

[CHECK HERE](https://www.technology.pitt.edu/help-desk/how-to-documents/pittnetwireless-configuring-acer-and-samsung-chromebooks)

1. Select WIRELESS-PITTNET.
2. In the Join Wi-Fi network window, select EAP method: **PEAP** 
3. For Phase 2 authentication, select **MSCHAPv2**
4. For Server CA certification, select **Default**
3. In the Identity box, enter your University Computing Account username. (eg. abc1)
4. In the Password box, enter your University Computing Account password.



### Kiosk Chrome App

[Kiosk Chrome App](https://chrome.google.com/webstore/detail/kiosk/afhcomalholahplbjhnmahkoekoijban)


[Instructional Video](https://youtu.be/M5US4OcVnL4) 

(Remember. Hold ctrl+a to access admin password.)

## System Considerations

Host your project online. GitHub won't host videos and you probably don't want to host them on YouTube (YouTube may provide users a kiosk exit). You can host your videos on your Pitt Linux server. 

-For our project presentations, you'll run your project on either a Lenovo Duet Touchscreen Chromebook or a Lenovo 110e. We'll profile the best projects for public viewing on a dedicated ACER T272HL display. 


## Useful Code Snippets
 
 Sorry. At the moment, image carousel requires either auto-play or user controls. See [W3 carousel tutorial](https://www.w3schools.com/howto/howto_js_slideshow.asp).  
 
 Time-out function

```
<!--Place within <HEAD></HEAD>. Refreshes index.html after 180 seconds-->
  <meta http-equiv="refresh" content="180;url=index.html"> 
```
 
 Stop video from playing in modal window. 
 
 </script>

```
 <!-- Stops video/audio from playing on modal close -->
  <script>
  $(function(){
  $("body").on('hidden.bs.modal', function (e) {
  var $iframes = $(e.target).find("iframe");
  $iframes.each(function(index, iframe){
  $(iframe).attr("src", $(iframe).attr("src"));
  });
  });
  });
  </script>
```
 

## Embeds and other tools that you might find interesting

[JS3 Timeline](https://timeline.knightlab.com/#make)

[Popular web tools that can be embedded](https://help.edublogs.org/popular-web-tools-that-can-be-embedded/)




