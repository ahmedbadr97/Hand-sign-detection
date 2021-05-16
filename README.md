# Hand-sign-detection
Hand sign segmentation form background <br />
Step 1 :User takes a picture of the hand  from(camera) <br />
Step 2 :The image is converted into gray scale <br />
Step 3 :Smoth the Image Using Median Filter <br />
Step 4 :Segment hand from background <br />
Step 5 : apply Morphological image processing (Erosion ) to separate fingers <br />
Step 6 :count objects in the image (hand + fingers) --> objects-1(hand) <br />
