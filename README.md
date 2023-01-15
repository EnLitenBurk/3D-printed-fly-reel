# 3D-printed-fly-reel
I designed and printed a fly fishing reel in order to teach myself about CAD and 3D printing. I'm quite happy with the end result


## Introduction
I've designed a 3D-printable fly reel. Feel free to print one for yourself! I used it for a 5-weight line but it was pretty big for that, 6 or 7 might make more sense.

## Background
I recently started a new job in a, to me, new work sector - engineering. At my new workplace there was a 3D printer available, but sparsely used. And since I have neer done any CAD or 3D printing of my own I thought I'd take the chance to learn some basics. I figured a fly reel was a reasonable difficulty level as they are a relatively easy design - essentially a spool that rotates freely in one direction and with some, preferably adjustable, resistance in the other direction.

## Method
I used blender 2.93 (latest at the time) because I had once installed it on my computer and I liked the look of it. The printer at work is a Prusa i3 MK3S and all slicing was done using prusaSlicer 2.3.3. All parts were printed in PETG, as it has a low risk of breaking and ageing. It can be somewhat tricky to print with stringing and such but I think it turned out well. I also printed a few parts using colorfabb's carbon fiber/petg filament, xt-cf20. It's a little sturdier, than regular petg but slow and troublesome to print.

Naturally, there is nothing new under the sun and I am not the first person to think of this so there was some available information online from which I freely took some inspiration. These are mentioned under Acknowledgments.

## Result
### Materials list
If you would like to print your own reel, you need a few more things on top the access to a 3D-printer and some printer filament. These are the materials currently being used in my 3D-printed reel:
* M6 hex bolt 50mm
* M6 bolt, self tightening
* M6 Penny Washer
* One way bearing 16x22x16 mm, found [here](https://www.kullagergrossisten.se/en/product/hf1616-envagslager)
* Bearing 6x13x5, found [here](https://www.kullagergrossisten.se/en/product/kullager-686-2rsc-6x13x5-gummitat-keramisk-hybrid) (probably not necessary)
* Cork disk - 4mm thick with a diameter of 45mm
* Super Glue, make sure it works with your filament type. I used "Loctite all plastics"

### Design walkthrough
The main issue with a homemade fly reel is the drag system. Making gears and "click and paw"-systems in a 3D-printer, using a plastic material does not feel like a great solution and will still require you to cup the reel and break using your hand. Instead, I've gone with a cork disc brake like the old classic fly reels. Cork provides a lot of friction and the harder you push against this disc the stronger the drag becomes. Modern disc brakes use a variety of materials to make the brake smooth, so there is room for improvement here.

Another issue comes from using plastic instead of metal, the construction is simply never going to be as sturdy or will have to be much bulkier to achieve the same sturdiness. There are harder and softer materials one can use when 3D-printing which brings their own distinct advantages and disadvantages. For the first fully functioning version of the reel, I used prusament PETG for all part but after breaking the spool by dropping the reel on a rock I had a good reason to re-print the spool using colorfabb xt-cf20, a PETG with 20% carbon fibres. I much prefer the stiffness and look of that material and might eventually reprint the frame in this material as well. 

Basically this reel has three parts. The spool, with a handle and piece in the middle where the One-way bearing is located. The One-way bearing sits on a "spindle" with a flat disk which pushes on the cork disc. The cork disk is squeezed between the real frame and the spindle. The tighter the cork disk is squeezed the harder the drag will be - the One-way bearing locks up in this direction and the spindle will turn. In the other direction the bearing can spin freely and the spool should be easy to turn. Pretty simple really. 
![PXL_20211030_151645275](https://user-images.githubusercontent.com/17005243/212564209-4826d94a-ee08-4402-80c1-62b17abdced1.jpg)
![PXL_20211030_151713432](https://user-images.githubusercontent.com/17005243/212564233-6a6b570e-9bcd-48b7-85ac-8d886f6205f0.jpg)


### Assembly
Here are some images to explain how the reel is put together:

![PXL_20211030_151806045](https://user-images.githubusercontent.com/17005243/212564182-25023b52-06d0-490b-9f56-b387691bfb04.jpg)

![PXL_20211030_151752117](https://user-images.githubusercontent.com/17005243/212564193-8fed45d4-6d0f-4bc6-9c3d-eec291076e11.jpg)
![PXL_20211030_151825155](https://user-images.githubusercontent.com/17005243/212564198-5104964d-74f3-404f-ae9d-fb6f572f9db7.jpg)
![PXL_20211030_151831536](https://user-images.githubusercontent.com/17005243/212564201-a1abf5b6-3172-4b3c-a105-9b606930a3ec.jpg)



### Live testing and subsequent improvements. 
Here are some images of the reel in action!!
![PXL_20211009_145816036](https://user-images.githubusercontent.com/17005243/212564215-9abe50ac-3cd8-44f9-930d-f83f51dfb00b.jpg)
![PXL_20211009_145852787](https://user-images.githubusercontent.com/17005243/212564218-d275fec8-619b-4835-92d8-1c9da6c52704.jpg)
![reel,crakced](https://user-images.githubusercontent.com/17005243/212564222-f6e25121-908d-4036-b9ee-0d70bab1e0cb.jpg)

### Design flaws and future improvements
The drag works well but the small adjustment of the drag results in a large difference in resistance. This could be improved.

The handle is definitely the weakest point of the design. I was working on printing a washer into the reel side to strengthen it but never finished.

## Acknowledgement
I borrowed ideas and designs from these links:

https://www.thingiverse.com/thing:2719928

https://cults3d.com/en/3d-model/home/bouton-de-serrage-pour-un-ecrou-m8

https://www.hendog-blog.com/projects/fly-reel

https://www.thingiverse.com/thing:4846834
