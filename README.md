# desk-object-sorter-ai

## Project Description
"This project uses Google's Teachable Machine to classify common objects found on my desk. These objects include a pencil, pen, and paper."

## Classes Identified
List the objects your model was trained to identify:
* Class 1 (Pencil)
* Class 2 (Paper)
* Class 3 (Pen)

## Discussion & Reflection
*(Please answer the following questions thoughtfully)*

1.  **Model Performance & Iteration:**
    * How accurate was your first trained model? Not that accurate, several errors.
    * What steps did you take to iterate and improve its performance? Add more photos.
    * How did these changes affect the model's accuracy and confidence scores? Drastically changed, it was able to find the correct object.

2.  **Challenges & Observations:**
    * Which objects were the easiest for your model to learn and distinguish? Paper. Why do you think that was? Because it is unique in size and shape.
    * Which objects were the most challenging? Pencil. What made them difficult? Similar to pen in size and shape.
    * What happened when you showed the model an object it wasn't trained on? After seond iteration, it was able to tell me what the object was accurately. How did the confidence scores behave, and why is this significant? Yes it grew with the addition of new pictures.

3.  **Bias in AI:**
    * If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? Probably not well. How does this illustrate the concept of bias being introduced through training data? It shows that you need a lot of data for the model to predict correctly.
    * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? it probably would not do well. How does this relate to the robustness and potential biases of AI models? They would need a lot of data to be more accurate.

4.  **Model Limitations & Usefulness:**
    * What are some key limitations of the model you created? The more images you have of different objects in different lighting will improve the models ability.
    * Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable? This enables others to be able to improve a mdoel that is already written or get new ideas.

5.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful. This could be usufel in a situation where sorting items was needed for example warehouse. It could also be useful in inventory management when an item is running short it can notify the owner.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse). I think the biggest issue would be privacy, since there is background images.

## (Optional) Challenges Faced / Interesting Discoveries
* Add any other specific challenges you encountered or interesting things you discovered during this lab. None.

## (Optional) Screenshot
* You can embed a screenshot of your Teachable Machine interface here if you like.
