# DaVinci_Resolve_TimeKeep
TimeKeep for davinci Resolve :)


# How to use it????

1. In Davinci Resolve add Text+ in Effects --> Toolbox --> Titles, then click and hold then put it in timeline
2. On your timeline, click on Text+
3. After that, click on Inspector, Video, Title
4. Right click on empty space on the text box
5. Click on Expression
6. Almost done!
7. Click on this little long box under text space
8. Add this: string.format("%02d:%02d:%02d", math.floor((time/comp.RenderEnd)*xxxx/3600), math.floor(((time/comp.RenderEnd)*xxxx%3600)/60), math.floor((time/comp.RenderEnd)*xxxx%60))

9. Now you need to convert Lenght of video to seconds! Like from 12m:10s is 730 seconds
10. Now in this code above you need to replace xxxx to your given seconds so xxxx to 730
11. Done :D

Sorry for my poor english... if you need help, add a issue :)
