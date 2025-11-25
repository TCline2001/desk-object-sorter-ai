# AI Desk Object Sorter

## Project Description
This project uses Google’s Teachable Machine to create an image classification model that identifies three common desk objects: a pen, a calculator, and a water bottle. The goal of this lab was to understand supervised learning, collect training data, evaluate model performance, refine the model, and explore real-world implications such as bias in AI.

## Classes Identified
* Pen  
* Calculator  
* Water Bottle  

## Discussion & Reflection

### 1. Model Performance & Iteration
The first version of my model performed surprisingly well, showing high confidence levels even during initial testing. To improve the model further, I added additional images pulled from Google, including pictures of people holding different versions of the objects. This introduced more variation in angles, lighting, and object types. Even with these new images, the model consistently predicted the correct class with confidence in the high 90% range. This showed that the model generalized well from the start and improved slightly as I expanded the training data.

### 2. Challenges & Observations
The pen and water bottle were the easiest objects for the model to learn because they have simple shapes and clear outlines. The calculator was slightly more challenging due to its more complex appearance and the wide variety of calculator designs. When I showed the model random objects it had never seen before, it still tried to classify them as one of the three categories, but with noticeably lower confidence. This demonstrated how the model attempts to fit unknown objects into familiar classes, highlighting limitations of supervised models.

### 3. Bias in AI
If I had only trained the “water bottle” class using images of my specific bottle, the model would likely struggle to identify other bottles with different colors, shapes, or textures. The accuracy and confidence would drop, showing how bias can be introduced through limited training data. Similarly, if all images were taken in bright lighting, the model might perform poorly in dim environments or heavy shadows. Both examples show how narrow training conditions can reduce a model’s fairness, accuracy, and robustness.

### 4. Model Limitations & Usefulness
The biggest limitation of my model is that it cannot recognize all variations of an object. For example, a dramatically different calculator design might confuse it. The model also forces every input into one of the known classes, even if the object is unrelated. Being able to download and share the model files (model.json, weights.bin, metadata.json) is useful because it allows easy collaboration, version control, and reuse of the trained model across different devices or projects—especially for people who may not have technical experience.

### 5. Real-World Applications & Ethics
Models like this could be used for auto shop parts organization, construction material inventory, or separating small items like LEGO bricks or toys. However, ethical considerations are critical. One major concern is fairness and bias. If an image recognition model is trained on limited or non-diverse data, it may misidentify or ignore items that look different from the examples it learned from. In real-world applications—especially those involving people—biased models can create unfair or harmful outcomes. Developers must ensure diverse training data and responsible use.

## (Optional) Challenges / Interesting Discoveries
I was surprised by how well the model performed even with minimal iteration. It handled different angles, lighting conditions, and even Google images of similar—but not identical—objects with very high confidence.


