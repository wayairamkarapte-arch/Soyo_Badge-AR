Soyo Badge AR / 15fps sprite-sheet fix

Upload index.html and the entire assets/sheets folder to the ROOT of your existing Soyo_Badge-AR GitHub repository. Keep badge_target.mind and target_image.jpg unchanged.

The previous animated WebP image could remain frozen when drawn into a canvas on iPhone Safari. This version advances 480 individual frames explicitly at 15 fps.

Existing position adjustments in your Safari browser are preserved. The default scale for new devices is approximately 0.78, based on the screenshot, and can be fine-tuned with the gear icon.

Refresh Safari after GitHub Pages deployment. Test on your actual phone.
