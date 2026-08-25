# Video-Pixel-Brightness
  The video pixel brightness is a browser based smart video brightness player that automatically adjusts video brightness according to the lighting conditions of each scene. The project is designed to make video playback more comfortable by intelligently adapting brightness while preserving the user's selected base brightness level.
# Working of the Application
This application analyzes the visual characteristics of the video and applies a brightness multiplier relative to the user's selected base brightness.<br>

The brightness engine works approximately as follows:<br><br>
  SCENE CONDITION  :	BRIGHTNESS BEHAVIOUR
  
  *Bright Scene  :  Dims toward 0.5× the base brightness<br>
  *Balanced Scene:	Maintains approximately 1.0× the base brightness<br>
  *Dark Scene    :	Boosts toward 2.0× the base brightness<br>
**********************************************************************************************************************************************************************************
## Note
> It isn't like the mobile adaptive brightness to reduce the overall brightness without any proper logic, it's main theme is to reduce the brightness only.<br>
> But here in Video Pixel Brightness application mainly focus on sensing the current scene and calculate the majority of pixels are bright/ dark/ balanced based on that the system actually works, then it adjust the brightness levels to dim/ boost/ maintain the same brightness level. 

**********************************************************************************************************************************************************************************
The user can also control the adaptation sensitivity and transition smoothness to customize how the brightness engine behaves.

# Features
  1. Local Video Playback     -  Open a video directly from your device.<br>
  2. Adaptive Brightness      -  Automatically adjusts brightness according to the current scene.<br>
  3. Custom Base Brightness   -  Choose your preferred brightness level.<br>
  4. Adjustable Sensitivity   -  Control how strongly the brightness engine reacts to scene changes.<br>
  5. Smooth Transitions       -  Brightness changes gradually instead of changing abruptly.<br>
  6. Drag & Drop Support      -  Drop a video file directly into the player.<br>
  7. Session Playlist         -  Keep track of videos opened during the current browser session.<br>
  8. Privacy-Focused          -  Videos are processed entirely inside the browser and are not uploaded to any server.<br>
  9. No Backend Required      -  The application runs completely on the client side.<br>
# Future Improvements
  Possible future enhancements include:<br>
      ~  More advanced scene analysis<br>
      ~  Automatic contrast adjustment<br>
      ~  Automatic color-temperature adjustment<br>
      ~  Custom brightness profiles<br>
      ~  Fullscreen playback improvements<br>
      ~  Support for additional video formats<br>
      ~  Performance optimization for large video files<br>
      ~  Mobile and touch-friendly controls<br>
# Best Use-Case Scenario
    Eg: If someone watch a salaar movie, mostly of the scenes are in the dark background so the user put the base brightness high to view the dark scene clearly. Whenever the bright scene comes suddenly there a flash on the user face due to the high base brightness. To overcome this problem this Video Pixel Brightness Application is useful to reduce the brightness levels ever before the user notice when the bright scene comes suddenly.
# Author

<b>Yugandhar Jarugulla   
GitHub: @yugandharjarugulla</b>
