# Hand-sign-detection
Hand sign segmentation form background <br />
Step 1 :User takes a picture of the hand  from(camera) <br />
Step 2 :The image is converted into gray scale <br />
Step 3 :Smoth the Image Using Median Filter <br />
Step 4 :Segment hand from background <br />
Step 5 : apply Morphological image processing (Erosion ) to separate fingers <br />
Step 6 :count objects in the image  <br />

=> Preivew button used to preview cam to take image for your hand "like in peview image" then use take snapshot image<br />
=> enhanement button uses avg filter to smoth the image and remove distructions from background you can use it more than once to remove objects from background  <br />
=> Segmentation Button to segment your hand from background if there is any object appears from background reuse enhancment button try to remove it or take another photo <br />
=> edge photo button is optional "not used in counting algorithm"  <br />
=> determin number button to count fingers <br />
