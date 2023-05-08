Download Link: https://assignmentchef.com/product/solved-s670-problem-set-3
<br>
High systolic blood pressure is a strong predictor of heart attacks and strokes. A health researcher wants to know how average systolic blood pressure varies with:

<ul>

 <li>Age</li>

 <li>Height</li>

 <li>Weight</li>

</ul>

For ease of interpretation, she does not wish to transform systolic blood pressure, but she is willing to consider interpretable transformations of the explanatory variables. She thinks the trends should be relatively smooth, but not necessarily linear. She suspects that for at least some of these variables, the trends may be different for men and women. In addition to estimating the trends, she wants to know how close observations typically are to the trend and whether the models might have any explanatory value. However, she is not interested in making predictions for individuals. She is not interested in formal inference right now, though she may be in the future. She knows some R, so you may include R code in your report, but she can’t read your mind, so label your graphs.

<h1>The questions</h1>

Use the NHANES data in the NHANES package to explore the researcher’s questions. The relevant variables are:

<ul>

 <li>BPSysAve (the average of three measurements of systolic blood pressure)</li>

 <li>Age (in years; 80 or older is recorded as 80)</li>

 <li>Weight (in kilograms)</li>

 <li>Height (in centimeters)</li>

 <li>Gender (male or female)</li>

</ul>

1

Write a document in three sections, giving the relationship of average systolic blood pressure with age, height, and weight respectively. (You can also include an introduction and conclusion if you really want to.) Each section should include approximately TWO graphs (a set of faceted plots counts as one graph) examining the trend and the residuals. Including many more graphs than this may be penalized. In each section, include a brief justification of your modeling choices (type of model, transformations or lack of transformations) and a verbal description of the differences you see between men and women. Some (sensibly rounded) quantitative measures will probably be useful, but you do not (and should not) list every single statistic you can think of.

<h1>Tips</h1>

<ul>

 <li>A safe approach would be to fit separate models for men and women for each explanatory variable (though other approaches are possible.)</li>

 <li>The group and color arguments within aes() can be used to distinguish between men and women.</li>

 <li>Because there’s a lot of data, you might have to play around with the plot settings to get legible graphs. Google the help pages for the individuals geoms (e.g. geom point()) to learn about aesthetic arguments for those functions.</li>

 <li>If the default axis limits don’t look nice, you can choose them with + xlim() and + ylim().</li>

 <li>If you see any weird results, try to explain them.</li>

</ul>