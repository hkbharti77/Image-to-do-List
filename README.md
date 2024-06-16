# Image-to-do-List

Must to Use Code Structure
 Initial display
 ● Theappmust have a carousel displaying two images at the
 beginning, with a transition effect between them.
 ● Themain app interface should include a drop zone area for
 uploading images and a list to display uploaded files with their
 respective thumbnails and description boxes.
 ● The“class” of the carousel should be “carousel”.
 ● Thelength of images in the carousel should have the class
 “carousel-item” .
 Image upload functionality
 ● Users should be able to upload images by dragging and dropping
 them into the drop zone or by clicking the drop zone to browse and
 select files from their device.
 ● Thedrop zone should respond to drag over, drag leave, and drop
 events with respective visual feedback.
 ● Users should be able to upload a maximum of 5 images, and an
 alert should be displayed when trying to upload more.
 ● Thefile upload should validate that selected files are images and
 below 1 MB in size.
 ● Youshould make a div of dropzone, the “class” and “id” of the
 dropzone should be “dropzone”. Take “class” and “id” both
 otherwise your code will not get tested correctly.
 ● Theplace where you will take the input should have input “type” as
 “file” and “id” as “fileInput”.
 Image display and description
 ● Uponuploading, each image should be displayed as a thumbnail
 in a file list below the drop zone.
 ● Users should be able to add descriptions to each uploaded image
 through a textarea element.
● Next to each thumbnail and description, a delete icon should be
 present to remove the respective image from the list.
 ● Theplace where your images will append should have the “class”
 as “file-list” and “id” as “fileList”.
 Local storage
 ● Theappshould utilize local storage to save and load image data
 and descriptions across sessions.
 ● Theimage data and descriptions should be saved to local storage
 every time a new image is uploaded, a description is
 added/changed, or an image is deleted.
 ● Previously uploaded images and their descriptions should be
 displayed in the file list when the page is reloaded
