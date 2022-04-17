# Unity-Emission-Mask-Maker
Allows you to quickly create a mask from a pre-existing texture
## To Use:
Import the program into your project under an Editor folder
</br></br>
Open the program from under the Window tab, called "Mask Creator Tool"
</br></br>
Load your texture into the Texture2D entry on the right of the new window(Texture must be Read Write enabled)
</br></br>
Select the upper bound color by clicking on the black square under the "Max" label, then click on the main texture to sample that color
</br></br>
Do the same for the Min and Background, with Min being the lower bound, and background being the background color of the texture
</br></br>
Now click on the previewed texture that you sampled colors from to generate a mask
</br></br>
After this, you can output the mask by clickin the button at the bottom to create a new image, with the image being the mask

## Other Details
Sharpness - defines the tollerance in color variation(basically how far beyond or below a color could be from the Upper and Lower bound and still be included)
</br></br>
Allow Gradient - Allows the created mask to be a range from 0-1 instead of being clamped to 0 or 1
</br></br>
You can use the scroll wheel while mousing over either texture to zoom in/out for more precise control
</br></br>
On the output mask, clicking on it a single time will fill the selected area with white(aka it allows you to fill in holes so long as they are bounded by white)
</br></br>
On the output mask, click and dragging allows you to delete parts of the mask

## Final Words
If you have any ideas for stuff to add to this, let me know, either through github issues or some other way, same goes for if something is unclear or buggy or just not working, let me know so I can fix it
</br>
Thanks!
