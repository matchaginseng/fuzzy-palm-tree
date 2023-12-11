# Classification Data

Images taken from [COCO 2017 Dataset](https://cocodataset.org/). 

* [cats](https://huggingface.co/datasets/huggingface/cats-image)
* [sandwich](https://farm8.staticflickr.com/7390/8860478142_d1743aa5bc_z.jpg)
* [soup and sandwich](https://farm6.staticflickr.com/5116/5802860677_4d18a7b259_z.jpg)
* [sheep](http://farm9.staticflickr.com/8094/8404835886_68a69089da_z.jpg)
* [oranges in bowl](http://farm9.staticflickr.com/8380/8462074646_e655e38ee9_z.jpg)
* [plate of pasta](http://farm4.staticflickr.com/3244/2815056162_8a1612ff20_z.jpg) -- this had been [labeled](http://cocodataset.org/#explore?id=321713) as "broccoli" and "carrot" in COCO but surprisingly not "pasta"
* [girl with sheep](http://farm3.staticflickr.com/2343/3544344028_c2cd3d736f_z.jpg) -- another one of those hard-to-figure-out what to classify as examples. the dataset had this [under](https://cocodataset.org/#explore?id=401436) "person," "carrot," and "sheep"
* [messy desk](http://farm4.staticflickr.com/3101/3237159405_2530304691_z.jpg) -- this one had been [labeled](http://cocodataset.org/#explore?id=237853) with a lot of things -- "bottle," "teddy bear," "computer," "laptop," "mouse," "remote," "keyboard," "phone," "book". but here, the model seems to focus on the "big picture" details rather than the more specific aspects in the final prediction, which isn't always what it does (for instance, with the plate of pasta)
* [eating cats](http://farm1.staticflickr.com/43/87305087_a9d38069db_z.jpg)