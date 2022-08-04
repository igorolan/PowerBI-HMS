# PowerBI-HMS_Course
Citi Bike is the largest bike-share program in the United States, with 20,000 bikes and over 1,300 pick-up stations across Manhattan, Brooklyn, Queens, the Bronx, and Jersey City.
Through the Citi Bike app, they can gather loads of useful data which, when analyzed, reveals great insights into things like user demographics and behavior.
So, my mission is to analyze data collected by Citi Bike
and help to make data-driven decisions based on the insights my uncover.

# מסימה מס' 1
צור טבלת
Dim Date
על פי הסקריפט, שלמדנו במסגרת הקורס.
הגדר את השנים הרלוונטיות כפרמטר .


![image](https://user-images.githubusercontent.com/82092425/182763678-ba9597f3-a04f-4424-8464-281363f4a156.png)
 

ייבא לתוך 
Power Bi 
את הטבלאות שבשני הגיליונות דלעיל.

 
![image](https://user-images.githubusercontent.com/82092425/182763864-542d4955-025b-4583-84dd-6810538d47df.png)

צור קשרי גומלין בין הטבלאות על בסיס מודל כוכב.


![image](https://user-images.githubusercontent.com/82092425/182763980-a0143e53-92c2-449a-a8c7-535a56b44a92.png)

 
בטבלת הוצאות שיובאה, הוסף באמצעות עמודה מחושבת נוסחה ב
DAX
אשר תחשבת את העלות בשקלים. עצב ללא ספרות אחרי הנקודה. הגדר שם לעמודה
NIS"

 
![image](https://user-images.githubusercontent.com/82092425/182764079-be6741ef-7679-4f69-8a26-6689f5991e39.png)


צור עמוד חדש בשם FirstReport באופן הבא :
ויזואליזציה ראשונה תהיה מסוג
Pie Chart
אשר תציג את סכום ההוצאות בשקלים, פר סניף .

 
![image](https://user-images.githubusercontent.com/82092425/182764212-4a570013-161a-42db-bad3-c47d06bec24d.png)
 
ויזואליזציה שניה תהיה מסוג
Donut
אשר תציג את סכום ההוצאות בשקלים,לפי מטבע מקור .

 
![image](https://user-images.githubusercontent.com/82092425/182764526-1574f0cf-4de7-4608-b6b8-11741f5abb4d.png)


באותו עמוד הוסיפו ויזואליזציה מסוג
Stacked Column Chart
המציג את חציון
ההוצאות בש"ח לכל סעיף ההוצאה.

 ![image](https://user-images.githubusercontent.com/82092425/182764658-7d459e0d-f401-485b-a1c8-32d0fab01824.png)


באותו העמוד, הוסיפו ויזואליזציה מסוג
Slicer
של התאריך. סננו את ה
Slicer 
לטווח התאריכים מטה :


![image](https://user-images.githubusercontent.com/82092425/182764749-8795b5a3-acbd-4b98-95f6-4f70c5f17b99.png)


באותו העמוד, הוסיפו ויזואליזציה מסוג סלייסר של מטבע. הציגו את האפשרויות בסלייסר ללא מטבע
CAD
וללא 
BLANK

השתמש ב
Filter Pane – Filter OnThis Visual
כך שהסלייסר ייראה כך :


![image](https://user-images.githubusercontent.com/82092425/182764977-b24746d5-f814-4c47-ab40-21700ec4f8ef.png)


באותו עמוד, הוסיפו ויזואליזציה מסוג סלייסר של סעיף ההוצאה


![image](https://user-images.githubusercontent.com/82092425/182765288-9cc2813c-0129-41d1-ba2f-ccf21c7d93c2.png)

 
 
# מסימה מס' 2

צור עמוד חדש בשם SecondReport באופן הבא :

וויזואליזציה חדשה תהיה מסוג Clustered Column Chart ותציג את הערך המינימלי, הממוצע והערך המקסימלי של ההוצאות בש"ח, עבור כל סעיף הוצאה

 

ויזואליזציה חדשה מסוג Area Chart של העלות בש"ח לפי התאריך (חודש בלבד(

 
באותו העמוד הוסיפו ויזואליזציה מסוג AreaChart של העלות בש"ח לפי התאריך.

 
 
באותו העמוד הוסיפו ויזואליזציה מסוג סלייסר של הסניף. הציגו את הסלייסר ללא  " " UK 












 
 
# מסימה מס' 3

צור עמוד חדש בשם " ThirdReport " באופן הבא :
ויזואליזציה מסוג Matrix אשר תציג את הסכום, ממוצע והחציון של ההוצאות(עלות בש"ח) בכל סניף.

 

הוסיפו מדד חדש בשם MyTarget שהוא פי 60 מהממוצע של העלות בש"ח.

 

הוסיפו את המדד הנ"ל לוויזואליזציה שבסעיף א'.

 
 
באותו העמוד, יש להוסיף ויזואליזציה מסוג KPI .
ב Indicator יש להגדיר את השדה של עלות בש"ח
ב Target Goal יש להגדיר את המדד שהגדרתם בסעיף ג .
ב Trend Axis יש להגדיר את שדה הסניף.
באזור Format בשדה Color Coding שנו את ה Direction ל LOW IS GOOD

 
 
# מסימה מס' 4

בעמוד חדש הציגו ניתוח של הנתונים בעזרת 4 וויזואליזציות שלא השתמשתם בהם בסעיפים הקודמים אשר יציגו את אותם KPI שהגדרתם .
 


 
