# AR Museum Experience Setup

## How to make the AR work:

1. **Create your target images**: You need images that the AR can recognize. These should be high-contrast images with unique features.

2. **Generate targets.mind file**: 
   - Go to https://mindartechnology.github.io/mind-ar-js-doc/target-images/
   - Upload your images (up to 30)
   - Download the generated `.mind` file
   - Save it as `targets.mind` in your project folder

3. **For testing**: The current code uses MindAR's demo image target, so you can test with their example card image.

4. **Print test image**: Download and print this image to test: https://cdn.jsdelivr.net/gh/hiukim/mind-ar-js@1.2.3/examples/image-tracking/assets/card-example/card.png

## Current status:
- The AR experience is now configured to work with a demo target
- Point your camera at the demo card image and you should see a spinning duck model
- The label will show "Mona Lisa" when the target is detected

## Next steps:
1. Replace the demo target with your own museum artifacts
2. Update the labels array with your artifact names
3. Replace the duck model with museum-appropriate 3D content