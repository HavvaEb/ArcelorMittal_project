# Predicting width constrictions during hot rolling

- Type of challenge: Learning
- Duration: `2 weeks`
- Deadline : `21/04/22 4:30 PM`
- Team challenge: Group project

## Mission objectives

- Be able to work and process data 
- Find insights from data, build hypothesis and define conclusions
- Build machine learning models for predictive classification and/or regression
- Select the right performance metrics for your model
- Be able to identify underfitting or overfitting that might exist on the model
- Tuning parameters of the model for better performance
- Select the model with better performance and following your
  customer's requirements
- Define the strengths and limitations of the model

## The Mission

Hot rolling is among the key processes that convert
cast or semi-finished steel into finished products.
This process is used to create shapes with the desired geometrical dimensions and material properties while maintaining the same volume of metal. The hot metal is passed between two rolls to flatten it, lengthen it, reduce the cross-sectional area and obtain a uniform thickness. 

![hot-rolling-process](https://ars.els-cdn.com/content/image/1-s2.0-S0924013604013056-gr1.jpg)


Since the rolling operation is often the last process step, the scrap at rolling stage is very costly and hence the quality control of rolling process is very important since they could cause catastrophy failure in a product use. Therefore, it is highly desired to detect, reduce, and eventually eliminate
any defects if possible.

One challenge occurs when the strip is picked up by the downcoiler. Tension is put on the metal strip, potentially lowering its cross-section which can lead to **width constriction**.


Your mission is to build a machine learning model in order to predict the risk of the width constriction during hot-rolling. Prediction can be binary (risk or no risk), but may also be a scale (regression).

![rolling (GIF)](https://upload.wikimedia.org/wikipedia/commons/4/4f/Hydraulic_Piston_driving_BU_Roll_correction.gif)

### Additional resources:
- [Behind the screens: New stands at hot strip mill (ArcelorMittal)](https://youtu.be/PC7eCrgsIMY)

- [Hot Strip Mills Production Process. Down Coiler](https://youtu.be/MFLKfV93Lcs)

### Must-have features

- Explanatory graphics of insights found in data.
- Implementation of machine learning models according to the client's requirements.
- The performance metrics of the model must be clearly defined.
- Evaluation of the model's performance and definition of its limitations.

### Miscellaneous information
Note: Data for this client should remain private. 

The dataset can be downloaded on the following link: 


* **Coil:** unique identification: no input
* **Furnace number:** used reheating furnace.  Preferably not used as input, but interesting if the model can be improved with it.
* **Analyse:** identifier of material type. Categorical, first 3 digits = main group, last digit = subgroup.
* **Hardness:** two quantifications of hardness: dimensionless numbers and width: average width in mm.
* **Temperature** before and after finishing mill: in °C
* **Thickness:** thickness after finishing mill, in mm
* **Thickness profile:** information on the shape of the cross section of the strip after finishing. preferably not used as input, but interesting if the model can be improved with it
* **c, mn, si,…. :** chemical composition in parts per million

### Constraints

- Create **functions**, do **not** create a single huge script
- Each **function** has to be typed
- Your code should be **commented**
- Your code should be **cleaned of any commented unused code**.

## Deliverables

1. Publish your source code on a private GitHub repository.
2. **Small presentation (15 minutes + 5 minutes Q&A) about your findings**
3. Dashboard representative of data insights
4. Pimp up the README file:
   - Description
   - Installation
   - Usage
   - ⚠️ **DATA SOURCES** (can describe insights but not name features, if made public.)
   - (Visuals)
   - (Contributors)
   - (Timeline)
   - (Personal situation)

## Evaluation criteria

### Technical

- Publish clean and readable code on GitHub.
- README has the format specified in the #Deliverables section.
- An EDA (Exploratory Data Analysis) was performed.
- The data was cleaned and preprocessed.
- The choice of performance metrics can be explained.
- The choice of model can be explained.
- The results and limitations of the model can be explained.
- The effects of overfitting or underfitting were studied and corrected.

### Soft-skills

- Communication with the client was prioritized to understand his needs.
- Project steps were enumerated and tasks were dispatched.
- Time available was managed well.
- Each member of the team worked towards project completeness.
- Constant communication within the team was achieved.

### Final presentation

- Slides are not too cluttered.
- The text on the slides is not read out loud.
- Presentation is tailored to the audience.
- Every group member understood each part of the project.
- Body language and intonation were professional.

## A final note of encouragement

"Attempts to create thinking machines will be a great help to discovering how we think ourselves."

![Let's do it(GIF)](https://media.giphy.com/media/efPA2YD9BFWS30GJ5v/giphy.gif)