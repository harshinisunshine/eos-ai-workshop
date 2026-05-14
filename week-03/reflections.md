##Task A6 – Reflection



---
Which two classes does your CNN confuse most?  Why do you think that’s happening (from the images, not the model)? If you had to fix this for production, what would you try? (More data? Bigger images? Colour
photos?)

*My model gets confused the most on two classes, which are Shirts and T-shirts. This can be seen as they have the highest error counts of 121 and 105. This happens because shirts and T-shirts look almost exactly the same when they are shrunk down into tiny, low-resolution images. They also have similar shape and structure which makes it harder for the machine to distinguish between them. The pictures are also very blurry, hence it is very hard to see key distinguishing features like shirt collars or button lines. If I had to fix this for production, I would try using bigger, high-resolution images and colour photos. Adding more data would also help a lot as it would train the model better. As the images are now more clear and colourful, more features could be extracted.*

##Task B6 – Reflection


---
Where does your persona break most reliably?
 Would adding more details to the system prompt help?
 Or is the model just too small? When would you reach for GPT-4 / Claude instead?

*My persona breaks down most reliably when dealing with highly technical or historical topics, like cooking recipes or the moon landing. Instead of staying in character, it drops the grandfather voice completely and starts sounding like a cold Wikipedia page. Adding more details to the prompt would not help at all. A longer prompt would actually overwhelm the model's tiny memory window and make it forget its character even faster.The model is simply too small to hold a creative persona and process complex facts at the same time. You would need reach for huge models like GPT-4 or Claude if you were building real-world software, like customer service bots, because they can stay in character perfectly without breaking logic.*