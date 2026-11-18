# desk-object-sorter-ai  for a school project if you are not my instructor/teacher please ignore 
## Project Description
This project uses Google's Teachable Machine to classify objects found that would be found on a desk, I used 30 images for each one 
## Classes Identified
List the objects your model was trained to identify:

* Class 1 Pencils
* Class 2 Keys
* Class 3 Pens

#Discussion & Reflection

1. Model Performance & Iteration:
  * How accurate was your first trained model?- it was accurate half of the time,  it did good with generic the generic type of items like a key a yellow pencil pens but had trouble with more different types items like multi pens, different colored pencils, and car keys.
  
  * What steps did you take to iterate and improve its performance? (e.g., added more images, diversified image types for a specific class).- I added more images with the different types of items (like car keys, multi pens and different colored pencils)
 
  * How did these changes affect the model’s accuracy and confidence scores?- it affected the accuracy and scores positively

2. Challenges & Observations:
  * Which objects were the easiest for your model to learn and distinguish? Why do you think that was?- The easiest object was the keys due to there being more less variations. and shapes than the Pencils and Pens were the Pencils and Pens and the due to it having the least variations and similar enough shapes.
 
  * Which objects were the most challenging? What made them difficult (e.g., similar shapes, variable appearances)?- The most challenging was Pencils and Pens due to them having similar shapes and more color to come in.
 
  * What happened when you showed the model an object it wasn’t trained on? How did the confidence scores behave, and why is this significant?- It caught a look at my mouse and mistook it for a car key it was significant because I didn’t have enough images of car keys

3. Bias in AI:
 * If you only trained your “mug” class with images of your specific mug (and didn’t vary color, shape, etc.), how well do you think it would recognize other students’ significantly different mugs? How does this illustrate the concept of bias being introduced through training data?-If I was training it on mugs and only trained it on plan mugs then it would have a bias for plan mugs and have a hard time recognizing more unique mugs like the one in the shape of a charterers face.
 
  * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?- I feel like it would have the least trouble with keys and would have a hard time differing between pens and pencils this relates to the robustness and potential biases of AI models because unlike humans you need to be specific with the right lighting.

4. Model Limitations & Usefulness:
 * What are some key limitations of the model you created?- It can only identity pencils, keys, and pens, it still some times mistakes pens for pencils and vice versa.
  
  * Why is it useful to be able to download your trained model files (like model.json, weights.bin) and share them (e.g., via GitHub)? What does this enable?- It enables the ability to make edits and make sure there isn’t any bugs.

5. Real-World Applications & Ethics:
  * Brainstorm 2-3 real-world applications where a similar image classification model could be useful.-finding something you lost track of, potentially identifying what color something is if you are color blind.

  * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).-Something to consider is that not everyone would be okay with this I used my own images but in the future a verity of images from a verity of people might used and they might not be okay with that
