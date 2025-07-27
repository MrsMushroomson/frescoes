# MindAR Setup Instructions

1. Use MindAR's "mindar-image" tool to generate `targets.mind` from your 30 images.
   - Each image will have a unique index (targetIndex) and a label.
   - Place the generated `targets.mind` file next to your `ar.html`.

2. In `ar.html`, update the `labels` array with your image labels in the same order as your targets.

3. To add overlays or 3D models per image, duplicate the `<a-entity mindar-image-target="targetIndex: X">...</a-entity>` block for each target.

4. See: https://hiukim.github.io/mind-ar-js-doc/tools/compile-images/

5. Make sure to test on HTTPS and with a real camera device.
