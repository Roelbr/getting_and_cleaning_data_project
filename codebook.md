<h1><a id="user-content-getting-and-cleaning-data---course-project-code-book" class="anchor" href="#getting-and-cleaning-data---course-project-code-book" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting and Cleaning Data - Course Project Code Book</h1>

<h2><a id="user-content-overview" class="anchor" href="#overview" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Overview</h2>

<p>This dataset is a summarization of Human Activity Recognition data collected
using the sensors in the Samsung Galaxy S II. An excerpt from the source study:</p>

<blockquote>
<p>The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.</p>
</blockquote>

<p>More information about the original data set can be found at the
<a href="http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones">UCI Machine Learning Repository</a>.</p>

<h2><a id="user-content-data-points" class="anchor" href="#data-points" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data Points</h2>

<p>The data points made available by this script are averages (as calculated over
unique combinations of the Subject and Activity) of a subset of the original
data points. The original study describes their dataset as follows:</p>

<blockquote>
<p>The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. </p>

<p>Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). </p>

<p>Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). </p>

<p>These signals were used to estimate variables of the feature vector for each pattern:<br>
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.</p>

<p>tBodyAcc-XYZ</p>

<p>tGravityAcc-XYZ</p>

<p>tBodyAccJerk-XYZ</p>

<p>tBodyGyro-XYZ</p>

<p>tBodyGyroJerk-XYZ</p>

<p>tBodyAccMag</p>

<p>tGravityAccMag</p>

<p>tBodyAccJerkMag</p>

<p>tBodyGyroMag</p>

<p>tBodyGyroJerkMag</p>

<p>fBodyAcc-XYZ</p>

<p>fBodyAccJerk-XYZ</p>

<p>fBodyGyro-XYZ</p>

<p>fBodyAccMag</p>

<p>fBodyAccJerkMag</p>

<p>fBodyGyroMag</p>

<p>fBodyGyroJerkMag</p>
</blockquote>

<p>For each of these features, the original study calculated several values. This
project only imported the mean and standard deviation calculations for each
feature.</p>

<p>The averages of those calculations were then determined for each unique
combination of Subject and Activity. These averages, along with their
corresponding Subject ID and Activity Name are what is written to the output file.</p>

<h2><a id="user-content-data-dictionary" class="anchor" href="#data-dictionary" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data Dictionary</h2>

<table><thead>
<tr>
<th>Variable</th>
<th>Class</th>
<th>Domain</th>
<th>Description</th>
</tr>
</thead><tbody>
<tr>
<td>subject</td>
<td>Categorical</td>
<td>Integer</td>
<td>An identifier that represents a single person in the study.</td>
</tr>
<tr>
<td>activity</td>
<td>Categorical</td>
<td>Character (Factor)</td>
<td>An identifier that describes the type of physical activity the measurements are associated with. Possible values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING</td>
</tr>
<tr>
<td>*</td>
<td>Quantitative</td>
<td>Real Number</td>
<td>The remaining variables in this dataset are the averages of their corresponding variables from the original study. These are all real numbers between -1 and 1.</td>
</tr>
</tbody></table>
</article>
  </div>

</div>
