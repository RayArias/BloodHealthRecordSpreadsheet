# BloodHealthRecordSpreadsheet
An Excel speadsheet for efficiently keeping a record of up to four blood pressure and blood glucose readings a day, plus space for notes for each reading.

After downloading, change "Month 20**" at the top of the first sheet and the "Month 1" tab to the month you need. For example, if you need the month to be September 2020, change both of those to read "September 2020." (This cell is datatype text, so you can put whatever you want here, but "Month YEAR" makes the most sense.) Next, clear the days you don't need at the beginning of the month. For example, if you are doing either September 2020, you should select the first two days, from Sunday to Monday on the first week (the ones that say "01 January" through "02 January", and right click and select "Clear Contents," and this will clear these unneeded days. Next, since Tuesday is the first day of September, go to "03 January" and change it to "01 September." (Sorry, I still have a glitch here where the date has to be entered as an integer, a day number from approximately 1 January 1900. In the next version to get around this I can put in a formula to help figure this out without having to get the calculator app or just experiment with different integers, but for now, this is what you have to do. This should make all the dates fall into place as dates in September 2020, instead of January 2017. For now, I'll put a chart in here for the first day of each month from August 2020 to December 2021 in day number int form. The first day of September 2020 is 44075, so go to "03 January" and enter 44075 and it will change to "01 September") Finally, select "01 October", "02 October", and "03 October" in the final week, right click and select "Clear Contents" so that all the dates on the chart are only from September. You have just completed an empty chart ready for a single month of readings. Next, if you like, you can click on the "Month 2" tab and do the same for October 2020 and then the "Month 3" tab for November 2020.

Calendar Month                Numerical (int) Day for Excel

August 2020..............................44044
September 2020...........................44075
October 2020.............................44105
November 2020............................44136
December 2020............................44166

January 2021.............................44197
February 2021............................44228
March 2021...............................44256
April 2021...............................44287
May 2021.................................44317
June 2021................................44348
July 2021................................44378
August 2021..............................44409
September 2021...........................44440
October 2021.............................44470
November 2021............................44501
December 2021............................44531

