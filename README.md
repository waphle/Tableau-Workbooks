# InfoVis HWK3 readme

﻿<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html">
<p>My dashboard is an attempt to replicate the <a href="http://www.perceptualedge.com/blog/wp-content/uploads/2012/10/dashboard-competition-winner.png">winning submission</a> from <a href="https://www.datarevelations.com/stephen-fews-dashboard-design-competition/">Stephen Few’s dashboard design competition</a>. My dashboard shows all of the data from the data except for the Class, Other Class, School, and District Math scores data (was unable to finish them).</p>
<h3 id="issues">Issues</h3>
<p>Some parts were hard to replicate in Tableau, and some parts were downright impossible to replicate in Tableau since the program lacks certain features. For example, the winning submission displays the current, previous, and goal grades on one single axis. In Tableau, you can make two measures share an axis via the “Dual-Axis” function. However, Tableau is unable to combine more than two measures together using the “Dual-Axis” function. Since I needed to display three measures, I could only use the “Dual-Axis” function for the Previous and Goal Grades measures, and I left the Current Grade on its own axis.</p>
<h3 id="grade-comparison">Grade Comparison</h3>
<p>For the Grade Comparison Sheet, I converted the Current Grade, Goal Grade, and Previous Grade data into calculated fields (thus changing their data type to Numbers). In the calculated fields, I converted the letter grades into a corresponding numerical value. Grade A became 1, B became 2, C became 3, and so forth till grade F. I needed to do this in order to present the three Grade data using the “Dual-Axis” function. However, I did not use the Current Grade converted calculated field due to the aforementioned “Dual-Axis” issue. Finally, in order to show the letter grades in tooltip, I added the original Grade data into the row axis, and hid their headers so that they wouldn’t show up in the final visual.</p>
<h3 id="special-needs-and-english-proficiency-guide">Special Needs and English Proficiency Guide</h3>
<p><strong>Light, faded blue circle</strong> = student is does not need special needs education, and is proficient in English.</p>
<p><strong>Yellow circle</strong> = student needs special needs education.</p>
<p><strong>Dark blue circle</strong> = student not proficient in English.</p>
    
</div>
</body>

</html>
