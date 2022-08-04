# PowerBI-HMS_Course
Citi Bike is the largest bike-share program in the United States, with 20,000 bikes and over 1,300 pick-up stations across Manhattan, Brooklyn, Queens, the Bronx, and Jersey City.
Through the Citi Bike app, they can gather loads of useful data which, when analyzed, reveals great insights into things like user demographics and behavior.
So, my mission is to analyze data collected by Citi Bike
and help to make data-driven decisions based on the insights my uncover.

# מסימה מס' 1
צור טבלת Dim Date על פי הסקריפט, שלמדנו במסגרת הקורס.
הגדר את השנים הרלוונטיות כפרמטר .

 

ייבא לתוך Power Bi את הטבלאות שבשני הגיליונות דלעיל.

 

צור קשרי גומלין בין הטבלאות על בסיס מודל כוכב.
 
בטבלת הוצאות שיובאה, הוסף באמצעות עמודה מחושבת נוסחה ב DAX אשר תחשבת את העלות בשקלים. עצב ללא ספרות אחרי הנקודה. הגדר שם לעמודה NIS"

 

צור עמוד חדש בשם FirstReport באופן הבא :
ויזואליזציה ראשונה תהיה מסוג Pie Chart אשר תציג את סכום ההוצאות בשקלים, פר סניף .

 
 
ויזואליזציה שניה תהיה מסוג Donut אשר תציג את סכום ההוצאות בשקלים,לפי מטבע מקור .

 

באותו עמוד הוסיפו ויזואליזציה מסוג Stacked Column Chart המציג את חציון
ההוצאות בש"ח לכל סעיף ההוצאה.

 
באותו העמוד, הוסיפו ויזואליזציה מסוג Slicer של התאריך. סננו את ה Slicerלטווח התאריכים מטה :


 

באותו העמוד, הוסיפו ויזואליזציה מסוג סלייסר של מטבע. הציגו את האפשרויות בסלייסר ללא מטבע CAD וללא BLANK 
השתמש ב Filter Pane – Filter OnThis Visual כך שהסלייסר ייראה כך :

 
 
באותו עמוד, הוסיפו ויזואליזציה מסוג סלייסר של סעיף ההוצאה
 
 
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
 


 
