# A Demonstration of Showing Integrated Scenario combining IBM Rational Rhapsody and Unreal Engine</br>
# Acknowledge</br>
I would like to express my sincere appreciation and thanks to my friend Jiajing Wang, for building animation in Unreal Engine and providing technical support. I would also like to thank others for their support, effort, and kindness.</br>
</br>
Demonstration of Showing Integrated Scenario Using IBM Rhapsody and Unreal Engine by [Zhentao Lu](https://github.com/lvzt) is licensed under [CC BY-NC-ND 4.0](http://creativecommons.org/licenses/by-nc-nd/4.0/?ref=chooser-v1).</br>
![](/image/CC_BY-NC-ND.png)</br>
</br>
Any questions, problems or suggestions are welcome and can be sent by [email](<lvzht@hotmail.com>) to the author – Mr. Zhentao Lu.</br>
# Links</br>
Video is posted on [YouTube](https://youtu.be/wCWwo6dum1E).</br>
</br>
大陆地区用户可以前往[bilibili网站](https://www.bilibili.com/video/BV1cH4y1S7YH/) 进行浏览。</br>
</br>
The demonstration about how to build DoDAF models in IBM Rhapsody can be found on [Demonstration](http://www.).</br>
# Detailed description</br>
This is a demonstration showing the integration of DoDAF models built in IBM Rhapsody with Unreal Engine models via UDP protocol.

The DoDAF models built in IBM Rhapsody are modified to add functions of sending and receiving commands through UDP protocol. The compiling environment is changed from Cygwin to Visual Studio.</br>
![](/image/people.bmp)</br>
![](/image/ground_transportation.bmp)</br>
![](/image/aerial_transportation.bmp)</br>
![](/image/railway_transportation.bmp)</br>
</br></br>
Before executing the animation, both models are activated.</br>
On Unreal Engine side, IP addresses and ports of local and target are typed in. Then scenario in Unreal Engine is initialized and activated.</br>
![](/image/UE4_01.jpg)</br>
![](/image/UE4_02.jpg)</br>
</br></br>
On IBM Rhapsody side, the model is in animation environment.</br>
![](/image/Rha_04.jpg)</br>
</br></br>
The animation starts from the DoDAF model in IBM Rhapsody. After the Go button is clicked, all states in DoDAF model are initialized and activated. Then a command is sent to the animation in Unreal Engine model through UDP protocol. Then the corresponding characters are acting according to the command.</br>
![](/image/Rha_01.jpg)</br>
![](/image/Rha_03.jpg)</br>
![](/image/UE4_03.jpg)</br>
![](/image/UE4_04.jpg)</br>
![](/image/UE4_08.jpg)</br>
![](/image/UE4_10.jpg)</br>
</br></br>
# Further work</br>
Till now, the animation is built and completed in Unreal Engine 4.23. Another animation is developing in Unreal Engine 5.</br>
