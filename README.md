# 
Xcode:Xcode is an application that developers use to build apps for various Apple's different platforms such as ihone,ipad,Macs,Apple Watch and Apple Tv.
Xcode is an IDE, an Integrated Development Environment, which essentially means that Xcode includes many additional tools for development. A few examples are: a debugger, source control, device management, iPhone Simulator, profiling tools, Interface Builder, documentation, and much more.

Xcode requirments:

1.Xcode is available for Macs only.

2.it requires macOS 10.14.4 or later and 7.6GB of hard drive space.

how to download Xcode:

1.The easiest way to download Xcode for free is through the mac app store.

2.Just visit the Apple Developer Page for Xcode.

Interface:

there are mainly 5 major areasin the interface.

1.Navigator.
2.Editor.
3.UTILITY Area.
4.Toolbar.
5.Debug Area.
![ios](https://user-images.githubusercontent.com/74370444/106992896-82643b80-679f-11eb-9f1e-31a5883b9027.PNG).

Next, when we open an iOS app project in Xcode, you see like this:
![5](https://user-images.githubusercontent.com/74370444/106997458-ef300380-67a8-11eb-9526-f459a3344010.PNG)



Creating a newproject:

1.open Xcode from the applications directory.


![2](https://user-images.githubusercontent.com/74370444/106995483-04a32e80-67a5-11eb-8107-dadc55d84325.PNG)


2.in the welcome window,click create a new Xcode project.Xcode opens a new window and displays a dialog in which you chosse a template.
3.select ios at the top of the dialog.
4.in the application selection,select Single View Application and then click Next.


![3](https://user-images.githubusercontent.com/74370444/106995587-3a481780-67a5-11eb-9a2e-0c4aec9729d8.PNG)

1.navigator
The Project Navigator is where you’ll see all the files associated with your project. This is the default tab you’ll see when you create a brand new Xcode project.
2.Creating and adding new files

You can also right click on the Project Navigator and create new files or add existing files to your project. Or you can drag folders or files from your computer directly onto the Project Navigator and will popup a dialog asking how you want to add the files.
3.The Xcode Search Navigator
With the search navigator tab, you can easily look for pieces of text in your project.

4.Writing Code
The editor area is the place where we’ll probably be spending most of our time! This is where all the coding, configuration and user interface building happens.

Let’s go through the Editor Area in the context of editing code files first.
![4](https://user-images.githubusercontent.com/74370444/106997670-4b932300-67a9-11eb-8c03-8a967e6312f3.PNG)

Launchscreen.stroyboard:
1.This is first screen we see when we open an application,also called as the splsh screen.when application is loading it shows this screen called as launchscreen.storyboard.this file is automatically created.Here we can add lable,image and manymore.
![6](https://user-images.githubusercontent.com/74370444/107005760-31137680-67b6-11eb-923a-80a1e97f65a6.PNG)


2.main.storyboard:Select MainStoryboard.storyboard is where you can find single view controller. we can add one more view controllers and update the view controllers.we link many scenes together,controllers.we can connect from one scene to many scenes.
![7](https://user-images.githubusercontent.com/74370444/107005773-353f9400-67b6-11eb-9eaf-3dd89e74dde8.PNG)

3.assets.Xcassets: Instead of adding individual images to Xcode’s file organizer, you add assets neatly organized in a single catalog. Asset catalogs also include metadata, for example about image scale.


![8](https://user-images.githubusercontent.com/74370444/107005783-37a1ee00-67b6-11eb-9cbc-194804629d7f.PNG)


3.appdelegate.swift:its an application life cycle,like how an application moves from one stage to other stage.the app delegate object manages your app's shared behaviors. The app delegate is effectively the root object of your app, and it works in conjunction with UIApplication to manage some interactions with the system.

![9](https://user-images.githubusercontent.com/74370444/107005793-3cff3880-67b6-11eb-910a-695847dfcc28.PNG)

view-controller.swift:A view controller manages a single root view, which may itself contain any number of subviews. User interactions with that view hierarchy are handled by your view controller, which coordinates with other objects of your app as needed. Every app has at least one view controller whose content fills the main window.


![10](https://user-images.githubusercontent.com/74370444/107006757-a0d63100-67b7-11eb-9ed0-48dcecd77894.PNG)



Adding a component to the splashscreen. you can see the icons at right side which consists of many components like lables, controllers,text,view, sliders etc.. a label is choosen and the properties (font, style, size, color) are changed.

![Screenshot (61)](https://user-images.githubusercontent.com/75902849/107059321-aa559e00-67a3-11eb-9c4d-309dd2f5727c.png)


Specific Markers: 
1.IBoutlet: It is used to declare an attribute & make it visible in the interface. here,a variable is declared.
![Screenshot (63)](https://user-images.githubusercontent.com/75902849/107061694-79c33380-67a6-11eb-8801-693831345502.png)


2. IBAction: it is used for making specific actions.

![Screenshot (65)](https://user-images.githubusercontent.com/75902849/107063413-5c8f6480-67a8-11eb-9a29-8a5ef66051b2.png)



A label and a button with text is inserted in splash screen. The is connected with the view controller so that the text changes when the button is pressed.

![Screenshot (67)](https://user-images.githubusercontent.com/75902849/107064628-bc3a3f80-67a9-11eb-993e-1e5a7667f7f2.png)



OUTPUT: STEP1.The program has Build successfully and  displayed in emulator

![Screenshot (69)](https://user-images.githubusercontent.com/75902849/107065218-821d6d80-67aa-11eb-809f-082ff28ecb67.png)


STEP2: The page is opened with a text and button

![Screenshot (72)](https://user-images.githubusercontent.com/75902849/107065722-18ea2a00-67ab-11eb-9edb-d8f42064ec26.png)
