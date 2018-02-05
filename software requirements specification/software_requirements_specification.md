# Software Requirements Specification

#### 5.1   Introduction
The photoEditr application will be an Android application that will allow users to upload their own photos and then
edit them with all of the above listed actions. The application will allow the user to save the edited image to 
the application’s native photo library or export it to the user’s phone’s photo library. The application will allow
the user to adjust contrast, saturation, brightness and temperature. It will have filters that can be applied to the
image in various strengths. It will have the capability to copy and paste selections of images onto each other, and
it will have the capability to pinch and stretch areas of the image. It will have a brush action that will allow the
user to “paint on” color to the photo, and it will have an eraser action that will allow the user to erase pixels.     

[UML DIAGRAM HERE]

The remainder of this document is structured as follows:         
Section 5.2 contains the functional requirements of the application.              
Section 5.3 contains the performance requirements of the application.               
Section 5.4 contains the evironmental requirements of the application.             
                 
#### 5.2 Functional Requirements
#### 5.2.1 Select Photo Interface
The Graphical User Interface for the application provides the user with a way to select the desired
function from those which are available in the application.  Users may optionally use several methods
for selection, all of which are considered synonymous to the application's operation.
#### 5.2.1.1  The Select Photo Interface shall provide a menu system to select a photo.
Application functions will include, but not be limited to, the following functions:
                        * upload photo from phone library
                        * choose photo from application photo library
                        * take a new photo using the camera

#### 5.2.1.2  The GUI shall provide a set of button widgets to access all functions of the application.
Application functions accessed by the buttons are the same as in requirement 5.2.1.1 above.
#### 5.2.2 Edit Photo Interface
#### 5.2.3 Photo Library Interface

#### 5.3   Performance Requirements
#### 5.3.1 Application Boot Time
#### 5.3.1.1  
The application shall open the inital interface within 5 seconds of the application being clicked on 
by the user.      
#### 5.3.2 Apply Transformations to Photo Time
#### 5.3.2.1
Each transformation of the photo must be applied in under 2 seconds.           
#### 5.3.3 Save Photo Time
#### 5.3.3.1
A photo must be saved to the phone's photo library in under 5 seconds after "Save" is clicked by
the user.
#### 5.3.3.2 
A photo must be saved to the application's photo library in under 5 seconds after "Save" is clicked by
the user.             
              
#### 5.4   Environment Requirements
An Android phone is required for this project. The application will be written in Java using an Android Software
Development Kit (SDK) and will not be tested with any platform other than Android phones.    
      
#### 5.4.1 Development Environment Requirements
The application will be developed using an Android SDK using the Java language. Android Studio allows Android applications
to be tested and run using an emulator, so an actual Android phone is not needed for the development of this project.    
         
#### 5.4.2 Execution Environment Requirements
The application can and will only be executed on Android phones that can download applications. Internet connection
is not necessary to use the application once it has been downloaded by the device.
