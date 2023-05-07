Download Link: https://assignmentchef.com/product/solved-msds6371-unit-5-preparing-professional-looking-reports
<br>



This class allows you to practice preparing professional looking reports. Make sure all reports are typed and all graphs (unless otherwise noted) are computer generated and copied and pasted into your report.  If you would like help with Word or Excel please don’t hesitate to ask.

<ol>

 <li>Read Chapter 4 from Statistical Sleuth and answer the conceptual problems at the end of the chapter. Note: You do not need to type these up and turn them in. The answers are at the very end of the chapter.</li>

 <li>When wildfires ravage forests, the timber industry argues that logging the burned trees enhances forest recovery; the EPA argues the opposite. The 2002 Biscuit Fire in southwest Oregon provided a test case. Researchers selected 16 fire-affected plots in 2004, before any logging was done and counted tree seedlings along a randomly located transect pattern in each plot.  They returned in 2005, after nine of the plots had been logged, and counted the tree seedlings along the same transects.  The percent of seedlings lost from 2004 to 2005 is recorded in the table below for logged (L) and unlogged (U) plots:</li>

</ol>

Test the EPA’s assertion (and thus the opposite of the logging industries assertion) that logging actually increases the percentage of seedlings lost from 2004 to 2005.

<ol>

 <li>Perform a complete analysis using a rank sum test in SAS. (Logging data).</li>

 <li>Verify the p-value and confidence interval by running the rank sum test in R (using R function Wilcox.test). (You do not need to repeat the complete analysis … simply cut and paste a screen shot of your code and the output.) You may use: <a href="https://www.r-bloggers.com/wilcoxon-mann-whitney-rank-sum-test-or-test-u/">https://www.r-bloggers.com/wilcoxon-mann-whitney-rank-sum-test-or-test-u/</a> for reference.</li>

</ol>

<ol start="3">

 <li>Conduct a Welch’s two-sample t-test on the Education Data from HW 3 (untransformed). Perform a complete analysis using SAS to test the claim that the mean income of college educated people (16 years of education) is greater than the mean of those with a high school education only (12 years of education).

  <ol>

   <li>State the problem, address the assumptions. Be sure to support with your knowledge of theory (CLT) as well as with histograms, box plots, q-q plots, etc.</li>

   <li>Show all 6 steps, including a thoughtful, thorough, yet non-technical conclusion. Include a confidence interval.</li>

   <li>Include a scope of inference at the end. (You may copy and paste this from a previous HW if you like.)</li>

   <li>Verify the Welch’s t statistic and p-value with R (using R function t.test). Simply cut and paste your R code and output.  You may use: <a href="http://rcompanion.org/rcompanion/d_02.html">http://rcompanion.org/rcompanion/d_02.html</a> for reference.</li>

   <li>Would you prefer to run the log transformed analysis you ran in HW3, or do you feel this analysis is more appropriate? Why or Why not? (Make mention of the assumptions as well as the parameters that each test provides inference on.  As you know, they are different.)</li>

  </ol></li>

 <li>

  <ol>

   <li>Chapter 4, Problem 20 from the text. Show all work.  “By hand” here means actually by hand.  Simply take a picture of your work and include it in your pdf/doc file.  Include your sorted, labeled, and ranked data; your calculations of the mean and standard deviation of the assumed distribution of the rank sum statistic under Ho; your calculation of the Z statistic with a continuity correction; your p-value, and conclusion.  (No confidence interval necessary here.)</li>

   <li>Problem 21 from the text. Take a screen capture of the SAS output in addition to your response.</li>

   <li>Write up a complete analysis using the information you have gained from A and B to test the claim that the distributions are different.

    <ol>

     <li>State the problem.</li>

     <li>State the assumptions you are making and why you are making them. Justify your decisions.  Print out any histograms, q-q plots, box plots, etc. that you use in your justification.</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>Show all 6 steps of the hypothesis test for the rank sum test of the trauma data. Use the critical values, test statistics, p-values, etc. obtained above.  Add a confidence interval from the Hodges-Lehmann procedure (from SAS).</li>

</ul>

<ol>

 <li>Also include a scope of inference statement.</li>

</ol>




<ol start="5">

 <li>A study was performed to test a new treatment for autism in children. In order to test the new method, parents of children with autism were asked to volunteer for the study in which 9 parents volunteered their children for the study.  The children were each asked to complete a 20 piece puzzle.  The time it took to complete the task was recorded in seconds.  The children then received a treatment (20 minutes of yoga) and were asked to complete a similar but different puzzle.  The data from the study is below:</li>

 <li>Calculate the statistic S for a signed rank test by hand showing the final table with the absolute differences, the signs, and the ranks. Also, show your calculation of the z-statistic (standardized S statistic).</li>

 <li>Verify your calculation in both SAS and R. Simply cut and paste your code and relevant output.</li>

 <li>Conduct the six step hypothesis test using your calculations from above to test the claim that the yoga treatment was effective in reducing the time to finish the puzzle.</li>

 <li>Use SAS to conduct a six step hypothesis test using a paired t-test to test the claim that the yoga treatment was effective in reducing the time to finish the puzzle.</li>

 <li>Verify your calculations in R. Simply cut and paste your code and relevant output.</li>

 <li>Use your data from above to construct a “complete analysis” of the test that you feel is most appropriate to test the claim that the yoga treatment was effective in reducing the time to finish the puzzle. This is simply formatting your results.  You should be able to cut and paste most of the work from above.</li>

</ol>

<strong> </strong>

<strong>BONUS (1 pt on 20 pt scale, 5pts on 100 point scale, etc.) This one is challenging and involves hard core SAS coding! </strong>Using our permutation test SAS code that we have used in prior HWs, do the following:

<ol>

 <li>Build the permutation distribution for the rank sum statistic for the Trauma data used above. Use 5000 permutations.  Use SAS to fit / overlay a normal curve to the resulting histogram.  Compare the mean and standard deviation of this normal curve that was fit to the permutation / randomization distribution to the mu and sigma you found in earlier in the homework.</li>

 <li>Compare the one-sided p-value found in this permutation distribution with the one found in prior questions.</li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="337">HINT: Don’t mind the highlight; the whole thing is the hint.  You will need to work code similar to what is to the right into the permutation test SAS code we used before (in place of Proc  ttest).  You will also have to do some research on how to get your hands on the sum of the ranks statistic (a good start is to print the outnpar data set!).</td>

   <td width="312"></td>

  </tr>

 </tbody>

</table>





