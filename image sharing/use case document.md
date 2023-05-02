# Image Sharing App - Use Case Document

## Overview

Our image sharing app allows users to upload and share their photos with friends, family, and the wider community. The app also includes a third-party integration with Pixlr, a cloud-based photo editing platform that provides users with additional editing and filtering tools.

## Actors

- User: A person who uses the image sharing app to upload and share photos.
- Admin: A person who manages the app and has access to administrative features.

## Use Cases

### Use Case 1: User Registration

**Actor**: User

**Description**: The user creates a new account in the app.

**Pre-conditions**: The user has downloaded the app and has an active internet connection.

**Post-conditions**: The user has created a new account and can now log in to the app.

**Steps**:
1. The user opens the app.
2. The user taps on the "Register" button.
3. The user enters their name, email address, and password.
4. The user taps on the "Submit" button.
5. The app displays a confirmation message that the user's account has been created.

### Use Case 2: User Login

**Actor**: User

**Description**: The user logs in to their account.

**Pre-conditions**: The user has an active account in the app.

**Post-conditions**: The user is logged in to their account and can access their profile and other features.

**Steps**:
1. The user opens the app.
2. The user taps on the "Login" button.
3. The user enters their email address and password.
4. The user taps on the "Submit" button.
5. The app verifies the user's credentials and logs the user in.

### Use Case 3: Image Upload

**Actor**: User

**Description**: The user uploads an image to the app.

**Pre-conditions**: The user is logged in to their account.

**Post-conditions**: The user's image is uploaded and visible to other users.

**Steps**:
1. The user opens the app.
2. The user taps on the "Upload" button.
3. The user selects an image from their device's photo library.
4. The app displays the selected image and prompts the user to add a title and description.
5. The user enters a title and description for the image.
6. The user taps on the "Submit" button.
7. The app uploads the image and displays a confirmation message.

### Use Case 4: Commenting and Liking Images

**Actor**: User

**Description**: The user comments on or likes an image uploaded by another user.

**Pre-conditions**: The user is logged in to their account and has navigated to an image uploaded by another user.

**Post-conditions**: The user's comment or like is visible to other users.

**Steps**:
1. The user navigates to an image uploaded by another user.
2. The user taps on the "Comment" or "Like" button.
3. The user enters a comment or confirms that they want to like the image.
4. The app adds the user's comment or like and displays a confirmation message.

### Use Case 5: Third-party Integration

**Actor**: User

**Description**: The user accesses Pixlr's editing and filtering tools through the app.

**Pre-conditions**: The user is logged in to their account and has an image that they want to edit.

**Post-conditions**: The user's edited image is saved to their device and can be uploaded to the app.

**Steps**:
1. The user selects an image that they want to edit.
2. The user clicks on the "Edit with Pixlr" button.
3. The user is able to use Pixlr's editing and filtering tools to edit the image.
4. The user saves the edited image to their device.
5. The user returns to the image sharing app.
6. The user selects the edited image from their device to upload to the app.
7. The app uploads the edited image.

**Alternate Flows:**
- If the user cancels the Pixlr editing process, they are returned to the image selection screen.
- If there is an error during the Pixlr integration process, the user is prompted to try again or contact support.