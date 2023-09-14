# **BloodHealthRecordSpreadsheet v. 0.30 alpha/MIT (_JustHoldYourNoseAndVoteForJoeBiden_) by Ray Arias**
  
<p> <b>BloodHealthRecordSpreadsheet v. 0.30 alpha (Codename: <i>JustHoldYourNoseAndVoteForJoeBiden</i>) released on 26 October 2020</b>: An Excel speadsheet for efficiently keeping a record of up to four blood pressure and blood glucose readings a day, plus space for notes for each reading.</p>

<p>After downloading, change "Month 20**" at the top of the first sheet and the "Month 1" tab to the month you need. For example, if you need the month to be November 2020, change both of those to read "November 2020." (This cell is datatype text, so you can put whatever you want here, but "Month YEAR" makes the most sense.) Next, clear the days you don't need at the beginning of the month. For example, if you are doing either September 2020, you should select the first two days, from Sunday to Monday on the first week (the ones that say "01 January" through "02 January", and right click and select "Clear Contents," and this will clear these unneeded days. Next, since Sunday is the first day of September, go to "01 January" and change it to "01 November." (Sorry, I still have a glitch here where the date has to be entered as an integer, a day number from approximately 1 January 1900. In the next version to get around this I can put in a formula to help figure this out without having to get the calculator app or just experiment with different integers, but for now, this is what you have to do. This should make all the dates fall into place as dates in November 2020, instead of January 2017. For now, I'll put a chart in here for the first day of each month from October 2020 to December 2021 in day number int form. The first day of November 2020 is 44136, so go to "01 January" and enter 44136 and it will change to "01 November") Finally, select "01 December", "02 December", "03 December", "04 December", and "05 December" in the final week, right click and select "Clear Contents" so that all the dates on the chart are only from November. You have just completed an empty chart ready for a single month of readings. Next, if you like, you can click on the "Month 2" tab and do the same for December 2020 and then the "Month 3" tab for January 2021. (In the case of December 2020, you need to clear out the first Sunday and Monday, since 1 December 2020 falls on a Tuesday. Also, you need to clear out "1 January" and "2 January" at the end of the month. In the case of January 2021, you need to clear out Monday through Thursday, since 1 January 2021 falls on a Friday. And, finally, make the first Sunday on the sheet into 31 January--unless you wish to place this date with February--by entering 44227. </p>

<table>
<tr> <th>Calendar Month</th>           <th>Numerical (int) Day for Excel</th> </tr>
<tr> <td></td> <td></td> </tr>
<tr> <td>October 2020</td>                              <td>44105</td> </tr>
<tr> <td>November 2020</td>                             <td>44136</td> </tr>
<tr> <td>December 2020</td>                             <td>44166</td> </tr>
<tr> <td></td> <td></td> </tr>
<tr> <td>January 2021</td>                              <td>44197</td> </tr>
<tr> <td>February 2021</td>                             <td>44228</td> </tr>
<tr> <td>March 2021</td>                                <td>44256</td> </tr>
<tr> <td>April 2021</td>                                <td>44287</td> </tr>
<tr> <td>May 2021</td>                                  <td>44317</td> </tr>
<tr> <td>June 2021</td>                                 <td>44348</td> </tr>
<tr> <td>July 2021</td>                                 <td>44378</td> </tr>
<tr> <td>August 2021</td>                               <td>44409</td> </tr>
<tr> <td>September 2021</td>                            <td>44440</td> </tr>
<tr> <td>October 2021</td>                              <td>44470</td> </tr>
<tr> <td>November 2021</td>                             <td>44501</td> </tr>
<tr> <td>December 2021</td>                             <td>44531</td> </tr>
</table>

<p> In a future version, we will introduce a function that will automatically fill in dates on all the sheets acording to entries placed on the Settings sheet. This functionality, however, has not yet been implemented. </p>


## How It Works

<p> There is now an extra sheet labeled "Settings." On it, you can change the settings of the format of all three months of sheets. The first one toggles between 24-hour time and 12-hour AM/PM time. Type in a "0" here for 24-hour time, or a "1" for 12-hour AM/PM time. You may have to go to "Conditional Formatting" and "Manage Rules" and push "Apply" for your settings to take effect. </p>

<p> The spaces for blood glucose numbers now change color and display symbols according to how high or low the blood glucose level you enter is and according to the numbers you set here. Blue background is supposed to indicate low blood glucose, white should indicate an ideal level of glucose, and red background indicates a high level of glucose. You can set your numbers here for what is low, ideal, and high for you. Further, there is a three symbol system to indicate how dangerously high the glucose is if it is high. The green circle is below the threshold of a warning for high glucose. The green circle will also come up for glucose that is too low, but you can see that the background is very blue in that case. Between the warning number and the danger number is the yellow triangle to warn you that your glucose is a bit high, but not necessarily high enough to treat. Above the danger number, a red diamond will display and this means that (unless you have just eaten a meal and haven't waited the two hours for your glucose to return to baseline levels) you may need to treat it immediately according to how your doctor prescribed, or, if it is extremely excessively high (350 or above), call 911 for an ambulance, or get to the nearest hospital emergency room as soon as possible. </p>

<p> The spaces for systolic and diastolic blood pressure readings now also change color and display symbols according to how high or low the blood pressure reading you enter is and according to the numbers you set on the "Settings" sheet. Blue background is supposed to indicate a low blood pressure, white should indicate an ideal blood pressure, and red background indicates a high blood pressure. You can set your numbers here for what is low, ideal, and high for you. Further, there is a four color circle system to indicate how dangerously high the blood pressure readings are, if they are high. The green circle is below the threshold of a warning for Stage I Hypertension. The green circle will also come up for blood pressure that is too low, but you can see that the background is very blue in that case. Between the Stage I Hypertension limit number and the Stage II Hypertension number is the yellow circle to warn you that your blood pressure is above the limit for Stage I Hypertension, but under the limit for Stage II Hypertension. Between the Stage II Hypertension limit number and the Stage III Hypertension (Dangerous Hypertension) number is the red circle to warn you that your blood pressure is above the limit for Stage II Hypertension, but still under the limit for Stage III Hypertension (Dangerous Hypertension). Above the Stage III Hypertension (Dangerous Hypertension) number, a black circle will display and this means that you may need to treat it immediately according to how your doctor prescribed, or, call 911 for an ambulance, or get to the nearest hospital emergency room as soon as possible. </p>


## Medical Disclaimer

<p> Neither this spreadsheet nor this set of instructions that come with it can replace the advice of a medical professional (such as a doctor, a nurse, a physician's assistant, a nursing assistant, etc.). Please comply with all advice you are given by your medical professional, including taking the correct medications, in the correct dosage, at the right time, and reading your blood health numbers with the recommended equipment at the recommended times each day. Be aware that the author of this spreadsheet and this set of instructions is, in no way, a medical professional, but is merely the designer of a spreadsheet that is intended to assist you in keeping records of your blood health readings. Thank you. </p>
