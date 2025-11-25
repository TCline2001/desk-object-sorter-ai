# AI Desk Object Sorter

## Project Description
This project uses Google’s Teachable Machine to train an image classification model capable of identifying three common desk objects: a pen, a calculator, and a water bottle. The goal was to learn the fundamentals of supervised learning, model training, iteration, and bias.

## Classes Identified
*Pen
*Calculator
*Water Bottle

## Discussion & Reflection
*(Please answer the following questions thoughtfully)*

1.  **Model Performance & Iteration:**
    * The first trained model was very accurate from the beginning.
    * To improve I grabbed a few different pictures from google to add a little variety of the objects.
    * I could upload pictures from google of people holding these objects, not even the same exact object, and it still scored in the high 90% on confidence.

2.  **Challenges & Observations:**
    * I think the water bottle and pen were easily learned as they are simple.
    * The calculator was more difficult as its more complex and theres a lot of different variety when it comes to calculators.
    * I showed it a few random objects and it just tried to tie it to one of the objects more than the other two, but with fairly low confidence.

3.  **Bias in AI:**
    * I think it would be able to guess them to a certain degree, but the confidence would be much lower.
    * It could throw the model off especially if the coloring was very washed out or the object was harder to make out.

4.  **Model Limitations & Usefulness:**
    * Different kinds of the objects, such as the mug example, its not going to be able to be super broad and very confident.
    * Its useful to be able to download them and share them because this makes working on them between multiple people very efficient, or flat out making it for someone else thats not well trained in computers.

5.  **Real-World Applications & Ethics:**
    * Auto shop parts orginization, construction material inventory, lego or toy separation.
    * A major ethical concern is fairness and bias. If a model is trained only on a narrow set of images, it may misidentify or exclude items that differ in color, shape, or style. In real-life scenarios especially involving people, biased training data can lead to unfair or harmful outcomes. Developers must ensure data diversity and avoid reinforcing unintentional bias.
