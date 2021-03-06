---
description: 'How to capture tours, useful checklists...'
---

# Shooting

{% hint style="warning" %}
[**The Trek Pack v2 is now available \(June 2020\). Click here for more information.**](https://app.gitbook.com/@dgreenwood-trekview/s/trek-view/~/drafts/-MGZS3QJdkKSR1bua7Ub/trek-pack/v2)**​**​
{% endhint %}

### Perform a test run

If not extended, extend the monopod so that you can just reach the start / stop button on the camera.

Turn the camera on, ensuring it is in the correct shooting mode and setting \(usually time-lapse\).

Put the pack on, and secure the straps to keep it from moving around too much. These straps also help compensate for the load of the pack too.

![](https://lh6.googleusercontent.com/6_GrFvmCW70HSL050kL4NEbvHbxJJHEP-o4YgofreBUq3FB3BoPclVWhAVvJ5KaOwQUbjMVsnBcc6RXhGO4ypft-CfrcmqZih__Rv6Bkn4rlcMKr8i_Tpa3ajTB4liRziFdwuftV)

Reach up and press the start button \(red circle outline\) and walk around your house / garden / neighbourhood.

After a few minutes, stop the filming by pressing the start button again. The camera should show a number \(the number of photos taken on your test tour. Note, this number is cumulative and will show number of photos taken in total\).

Turn off the camera, and remove one of the micro SD cards. Place the microSD card in the microSD card USB reader and insert into your computer You should see either the front or back images \(depending on which SD card you’ve inserted\).

Eject the microSD card USB reader from your computer, replace the SD Card in the camera, and do the same thing with the second microSD card.

If everything appears to be working correctly, it’s time to shoot.

### Before you Leave the House

This part is written from bitter experience -- turning up, excited to start filming, and realising I’ve forgotten something.

Now I perform the following checks before leaving home:

1. Are the batteries fully charged and is one in the camera? Have you packed a spare?
2. Do the MicroSD cards have enough free space for everything you plan to shoot? Are they both in the camera?
3. Is the monopod in/on the pack \(including GoPro mounts and screws\)?
4. Have you enabled GPS mode?
5. Is time-lapse mode on the correct interval for the type of transport you will use to shoot?
6. What is the weather like? Have you checked the best source of weather information available for the location?

You should also consider safety. Have you got the right gear for the environment? Are you prepared for changes in the weather? Are you going out with a friend? Does someone at home know your plans? Have you packed water and food?

### Capturing a Tour

Put on the pack, set the mode to time-lapse \(ensuring the settings are correct\), make sure that the GPS is locked on \(the GPS pin icon is a solid colour\), and start press the red button.

You don’t need any more instructions -- you’re now an expert on the Trek Pack. Though here are some recommendations based on personal experience:

* When shooting, try not to move your torso around too much, but remember to enjoy the environment around you too.
* The only other thing I would recommend is, when shooting in timelapse capture a series of photos in batches. Stop/start the time-lapse every 10 or 15 minutes. This means photos can processed in batches, rather than one single series, which can be useful for reasons I’ll describe in part 4 \(hint: software crashes\).
* Be prepared for questions. Many people will be intrigued by your Trek Pack. We encourage Trekkers to share what they’re doing with others, and why. Many people will, rightly, be concerned about their privacy. Be prepared to tell them how your photos will be used.
* Make sure you comply with local laws around public photography too. Generally don’t shoot on private property or around children, but make sure you know what is and isn’t allowed beforehand.

### Processing Your Photos

#### 0. Download GoPro Fusion Studio

To process photos, you’ll need to download a piece of software called GoPro Fusion Studio, available here:

[https://gopro.com/en/gb/shop/softwareandapp/gopro-fusion-studio-app/fusion-studio.html](https://gopro.com/en/gb/shop/softwareandapp/gopro-fusion-studio-app/fusion-studio.html)

#### 1. Import and prepare your raw photos

After shooting, copy the front and back files for each segment of the tour onto your computer using the MicroSD USB card reader.

Have a look at the photos captured. 

In my case, often the first and last 20 photos will be me setting up the camera or stopping. Occasionally I am also disturbed mid-tour \(usually by animals\).

![](https://lh5.googleusercontent.com/8HSxsUm45Ut6Vvzt-XjlS8Lvq0lQZFNu9rABOkev7GdovfbBPiVdBOAPWMl6ZhQaNeuuj1V_UCuWQ2YLGGrqrMebhUEG4QeifiXORJpl4ahxes4Fs-Le-Q2p44jkj7kE0QtJ5W3-)

Before adding to GoPro Fusion I’ll then delete these photos on my machine. Before you do this, first make sure you have a copy of the images on the MicroSD card just incase the worst should happen. Then, start deleting photo pairs \(e.g. GF023401.jpg and GB023401.jpg\). If you have an uneven number of photos GoPro Fusion Studio will not load the photos and show an error.

**1.0.1 A note on filename format**

* GF023401.jpg and GB023401.jpg: GF = front image \(hold GPS info\) / GB = back image
* GF023401.jpg and GB023401.jpg: The series. This will increase by 1 each time you start a new timelapse capture.
* GF023401.jpg and GB023401.jpg: Photo number. Increases by 1 with each photo taken.

This can be useful information to know when organising tours. For example, you might shoot different timelapses in different locations. In this case, the series number will help you easily identify the break-points \(GoPro Fusion will also break photos like this\).

#### 2. Add raw files to GoPro Fusion

Now you have a folder of front and back images on your computer, you can add them to GoPro Fusion.

![](https://lh6.googleusercontent.com/HO3xobMZt0D79CJpQZnnckRbCowYsHjqVQhePKVKB3k4ksuuWlRWFBUGD24I3vmgKPT6IAGege8kkOJCt8Q7RVBvm8TOcXaWu8cFP9DDVTxYtxqmk1UiJ08g7rMUQ9RgkJ6z--3Q)

Open GoPro Fusion and select “Add Media”, and then select the location of your files.

#### 3. Adjusting photos before stitching

**3.1. Filename Settings**

Before stitching the front and back photos to create a final panoramic photo, GoPro Fusion Studio allows you to modify some of the settings for each group of photos.

You’ll notice each timelapse sequence you captured is separated by GoPro Fusion Studio \(MULTISHOT\_x, MULTISHOT\_y, etc.\).

You can modify the prefix, but generally don’t recommend this. It makes it easier to identify/match the photos if you stick to the default, should ever need to re-render them.

_**3.1.1 Filename format**_

GoPro Fusion Studio will automatically name each timelapse sequence using the last 4 digits of the first photo in the timelapse.

For example, let’s assume the first photos in the timelapse have the filename GF023401.jpg / GB023401.jpg. In this example, that timelapse sequence will have the prefix MULTISHOT\_3401 for all the photos generated \(e.g. MULTISHOT\_3401\_000001.jpg, MULTISHOT\_3401\_000002.jpg, etc.\)

**3.2 Roll, Yaw, Pitch Settings**

Once you’re photos are loaded, have a play with some of the settings.

The key ones I tend to modify are:

* Yaw: rotation around the front-to-back axis \(use if camera facing left or right\)
* Pitch: rotation around the side-to-side axis \(use if camera facing up or down\)
* Roll: rotation around the vertical axis \(use if camera tilted to left or right\)

![](https://lh5.googleusercontent.com/OBDiMkgazQzfK68Xq7Iged49OjJSysuXDomB5fbj_QRWg-3vEeCJVsmYkLEdEyZQVMYx9FTqFFlKPP8UBg82jjFpCYvV185RS9stZFT0bLxtBZTfjHDlv_5zZfAPac1_8VlwbgE_)

In GoPro Fusion Studio use the sliders to try and line up the horizon and make sure the centre of the photos is straight ahead.

![](https://lh6.googleusercontent.com/6DU8J4JIATpVIJFH1v1KKJtt-AzropAFCWfMsCqr_9Jgw8Wbh4TUZUlpuKEkbqkZ5k2dC1mJL6gl2pD3q2dEPdaR4rxm_2gp2unYokE5p10US81H8J8WxkzIUlmpbZusmGyoOXLc)

Make sure to move the time selector to different points to see if your settings look good. You might have the odd photo that was taken at a wonky angle \(I have many like this where I’ve bent down or slipped\) which is why checking against a larger number of photos is advisable.

The “grab a 360 photo” tool is also useful to test your modifications. It allows you to grab a single panorama of the photo currently selected.

![](https://lh3.googleusercontent.com/4lBOWzIlcOoFlo_UngjkcAGCug7F56XMz9pMQRgJPnjATaBVQvH6Pl7-uDIexnXBP2ZDOq977PZYdb-EVK3BRewVQGeCwexchBKW7s1_0isB-2Zyzok2K85eIhXi2aRNn4i5rkGP)

Selecting this option will create a new entry on the left hand side for you to render. To get the single panoramic photo, you still need to render it \(described in 3.3\).

![](https://lh3.googleusercontent.com/dLjX47p_ZaW2RJok98lmkWFVqEVC2SUJzu3KV5wMplbbLrHXcslGXxj1NzF1NCknjbEnoBCy4iTQK8acerWEqxRRCz20wPz0xw43-hEqYji8HpOsGRLJyhz__HSVh9RZzDAzNGCr)

Using a panoramic photo viewer \(e.g. [Insta360 Player](https://www.insta360.com/download)\) you’ll be able to see if everything is level and as expected.

You might notice GoPro Fusion Studio does not stitch a 100% true panoramic photo due to small blind-spots between the two GoPro Fusion lenses. These blind-spots are virtually unnoticeable in the stitched photos, and in fact work as an advantage to ensure the photo does capture monopod stand.

![](https://lh6.googleusercontent.com/WDfAP_NpSD8MAiuaqW5et3j7XvhSwTWEyTgjPy7kdDa9kYMzY3pOXDBTDys9eUAN6nZFiridmNwN1l-Z8BdX-pqzYF2s4D00VWtX0WXVMokwSgrBb4sjxW1DM52s75l0rg87QpCI)

Once you’re happy, select all the tours you want to render and add them to the render queue.

**3.2.1 Colour / other settings**

Don’t mess around with the colour settings too much, if at all. If you plan to upload to Google Street View, images where colouration has been significantly modified \(think Instagram filters\) will be rejected by Google.

#### 3.3 Rendering Settings

Before stitching, you can also edit how GoPro Fusion Studio will output the photos.

![](https://lh6.googleusercontent.com/MTY8a8qevteuLpCG0A5v4LE18BJEphkFaK-5M8pFdSYNn75YG894xo5lH0nsU6U1XhZzW_gVVmJ9AoLgGgctSim5tBPjhbI0EtXa452z8JLqAIHbWIvrZ9mUizh_Kt5qqolNBmEG)

For each tour in the queue, make sure to select the highest resolution possible if you plan to upload to Street View \(they must be at least 4K\). You can do this by clicking on each tour in the render queue.

![](https://lh6.googleusercontent.com/6EAYNtXQaby7BYJD6R3TEbwgVxy-UtdON0IrPNmyyiSynmxo64IWK__3_FssBwXk89ebo_vOg9Pb9boP7kDff18wV-DcpdeEh53sM3_ojH-AYjeKv3QCLnFLDc1yZZoj7GTl5rCp)

If you shot in time-lapse mode, make sure set the video codec to JPEG OR TIFF. This will produce individual photos.

![](https://lh3.googleusercontent.com/YFP4CQGvcJBiu7onmDGSVtgd7N_siqJNSf7bucZ4upVyOleeEHRkImY9-ZEqbmJp8DRmA6j9alkl95HW6G2RfvliZaQQxZ-qXO32074AVvpiJ8sDzOKZCa1ZXm2lksinWNpH9UiV)

Before rendering, check the output location on your machine for stitched photos is correct. You can view or modify this location under “Preferences”.

**3.3.1 Video codecs**

You can stitch time-lapse photos to video files using GoPro Fusion Studio, however, I have found these are incompatible with Google Street View with Google rejecting the video file. You must therefore record in video mode on the GoPro Fusion to produce a Street View compatible movie output using GoPro Fusion Studio. As mentioned earlier, we won’t cover video in this doc for reasons described.

**3.3.2 Render performance**

Rendering in GoPro Fusion Studio is memory intensive. I use a MacBook Pro with a good CPU \(i7 processor\) and 16GB of RAM. Whilst fairly powerful, the rendering process will make my computer unusable until the process completes. As a rough estimate, on my computer it takes 10 minutes for every 1GB of photo output.

### Publishing

You can use the [Map the Paths Desktop Uploader](http://mtp.trekview.org/uploader) to process and publish the images to various online services.

[Read the Map the Paths Desktop Uploader documentation here.](../../mtp-desktop-uploader/overview.md)

