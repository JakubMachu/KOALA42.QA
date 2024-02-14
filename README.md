# KOALA42.QA

## Technical Assessment - KOALA42

### Interface Problems:

After scanning the QR code, the modal window "Permission to use the gyroscope" has distracting paws of the dog covering the text. 
Additionally, this advisory is displayed twice, once in bold and then immediately below it - unnecessary duplication. 
The "OK" button has poorly chosen contrast and needs a different color combination.

### MF-1: Save the dog:

The application allows you to save the dog in the application database. 
- However, after taking a picture of the dog and holding a finger on the captured photo, it is not possible to save it to the collection.
- Options available are: Open in a new tab, Show preview, Copy, Download, Share - missing option to save to the collection. 
- Also, the captured photo has the issue with the dog's paws mentioned in Interface Problems. 
- If the user selects "Show Preview," the problem with the paws disappears.

### MF-2: Share the dog:

The application should allow sharing the dog on the social network Facebook. 
- However, sharing via Facebook is not functional. 
- Only options available are: Set as profile picture, Channel of selected posts, Your groups, and Your story.
- In the case of sharing on the profile - this option is missing. WhatsApp or Google Drive works fine. My wife asked me what I sent her there for :D

### MF-3: Take a picture:

The application allows taking a photo of the dog and saving the photo. 
- Same problem as described above.

### MF-4: Display dog:

The application displays a 3D model of the dog in your surroundings, which wiggles and moves somehow. 
- There is an issue with moving the dog to another location. 
- When I move the phone around, dog would stay at one place. 

### MF-5: Display saved dogs:

The application should allow the user to view the list of saved dogs and their details. 
- This function cannot be tested.

### MF-6: Actions with dog:

Using the buttons, the application displays a 3D model of the dog, which wiggles and moves somehow. 
- When selecting the option "Lie down" and subsequently taking a picture, the image is not saved, and there is an icon of a camera on the preview.

### MF-7: Change dog:

The application should allow the user to view the list of saved dogs and their details. 
- Melody is added after scanning 1st QR code.
- Rest of QR codes are same dog as default.

### MF-8: Create user account:

Email and password are required. 
- During registration, when the user enters an email, the email input turns blue - the background of the password input remains white, which is inconsistent.
- The checkbox with GDPR conditions blends too much with the background of the registration form.
- After filling in the necessary data and checking the GDPR checkbox, the "Register" button changes to orange - again, a consistency issue.
- After clicking the "Register" button, a modal window with successful registration appears - there is an issue with the image of the dog and its paws covering the text.
- Also, its head cannot be seen. Login after new registration proceeds correctly, and "Your collection" is displayed.

Performance issue:
- App starts to freeze after couple of minutes while photo mode is on. Smarth phone starts to overheat.

Tested on Samsung Galaxy S22 - Android V14.



## API-Testing

### 1. Test case:
- Validate if status code is 200
- Validate if response is valid JSON
- Validate if response contains all CHARACTERS - data and properties

### 2. Test case:
- Validate if status code is 200
- Validate if response is valid JSON
- Validate if returns correct CHARACTERS - count

### 3. Test case:
- Validate if status code is 200
- Validate if response is valid JSON
- Validate if response contains all NEMESIS - data and properties

### 4. Test case:
- Validate if status code is 200
- Validate if response is valid JSON
- Validate if response contains all SECRETS - data and properties

