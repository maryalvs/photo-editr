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
The Photo Library Interface shall display every photo that has been edited using the application.
#### 5.2.3.1 The Photo Library Interface shall display a thumbnail of the actual photo.
The Photo Library shall display thumbnails of all the photos in the library.
#### 5.2.3.2 Photos displayed in the library can be selected by the user.
The user can select a photo in the library by clicking on the thumbnail. The photo should be displayed 
differently from the others if it is selected.
#### 5.2.3.3 A button shall exist to edit the selected photo.
A button exists on the Photo Library Interface when a photo is selected that will open the Edit Photo Interface
with the selected photo when clicked.
#### 5.2.3.4 A button shall exist to delete the selected photo.
A button exists on the Photo Library Interface when a photo is selected that will remove the photo from the 
application's photo library when clicked. After this, the photo should no longer be displayed on the Photo Library Interface.
