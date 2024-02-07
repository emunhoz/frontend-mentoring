## Challenge Title: Avatar Upload Async

### Description

You have been assigned to develop an avatar upload feature for a web application. The goal is to allow users to easily and intuitively update their profile picture.
_Feel free to use Vanilla JavaScript or utilize frameworks and external libraries. I would recommend using React or Vue :)_

### Requirements

1. **User Interface:**

   - Create a simple and user-friendly interface that allows users to select an image from their device to upload as their avatar.
   - The design is up to you. You can use some references but try to challenge yourself :)
   - Display a preview of the selected image before confirming the upload.
   - Provide a button to confirm the upload and save the new avatar photo.

2. **Upload Functionality:**

   - Implement the logic to upload the selected image to the server.
   - Use Async/Await to ensure a smooth asynchronous process during upload.
   - After successful upload, dynamically update the user's profile photo in the interface without reloading the page.
   - Some APIs have generous limits for storing and uploading images (Cloudinary, Imgur API, AWS S3, Firebase Storage).

3. **Validation:**

   - Verify that the selected file is a valid image (common formats like JPG, PNG, GIF, etc.).
   - Limit the file size to prevent excessively large uploads.
   - Provide clear feedback to the user in case of errors during the upload process.

4. **Reactivity:**
   - For Vanilla Javascript: ensure that the user interface is automatically updated whenever there are changes in the state, such as selecting a new image or completing the upload process.

### Recommendations

- Avoid using libraries for styling (e.g., MaterialUI, AntDesign, SemanticUI).
- Keep the code organized and well-commented to facilitate review.
- Semantic commits.
- Test as much as possible (Prioritize by importance of functionalities).
- Test the functionality in different browsers and devices to ensure a consistent experience for the end-user.
- Use some service from Cloudinary, Imgur API, AWS S3 or Firebase Storage to store the image, otherwise, focus on implementing as much of the requested functionality as possible, understanding end-to-end how much frontend is required for a real-world scenario.
- Deploy the solution on a platform (e.g., Vercel, Netlify, S3).

### Links

- https://developer.mozilla.org/en-US/docs/Web/API/File_API
- https://cloudinary.com/blog/guest_post/build-serverless-upload-with-cloudinary
- https://cloudinary.com/blog/upload-images-with-vercel-serverless-functions
- https://vercel.com/templates/next.js/aws-s3-image-upload-nextjs
- https://vercel.com/guides/how-to-upload-and-store-files-with-vercel

This challenge aims to assess your front-end development skills, particularly in areas such as event handling, file manipulation, asynchronous communication, and reactive user interface updates. Good luck!
