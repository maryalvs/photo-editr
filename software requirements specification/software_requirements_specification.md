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
The Select Photo Interface shall allow the user to select a photo to edit. Once a photo is selected, the 
Edit Photo Interface will be displayed using that photo.
#### 5.2.1.1  The Select Photo Interface shall provide a menu system to select a photo.
The application shall display the Select Photo Interface when initially opened by the user.
This interface will allow the user to select a photo to edit by either (1) uploading a photo
from the phone's library, (2) taking a new photo with the phone's camera, or (3) selecting a photo from
the application's photo library.
#### 5.2.1.2  The Select Photo Interface shall provide a set of buttons to select a photo in the 3 ways possible.
The three buttons shall allow the user to select a photo by (1) uploading a photo
from the phone's library, (2) opening the phone's camera, or (3) displaying the application's Photo Library Interface.
#### 5.2.2 Edit Photo Interface
The Edit Photo Interface shall allow the user to edit a single photo by applying various transformations.
#### 5.2.1.1  The Edit Photo Interface shall provide a menu system to transform the photo.
The Edit Photo Interface shall provide a menu system that has icons for each transformation that can be applied
to the photo.
#### 5.2.1.2 The Edit Photo Interface shall provide a button to save the photo.
The interface shall provide a button that saves the edited photo to the phone's library as well as the application's photo library.
#### 5.2.1.3 The Edit Photo Interface shall provide a button to discard the edited photo.
The interface shall provide a button that brings the user back to the Select Photo Interface without saving the transformations of
the currently selected photo.
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
