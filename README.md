# Kindergarten-Gan-Shaked- 
### 1. הפרויקט שלפניך שונה מפרויקט רגיל מאחר ואין בו איפיון (חסרון)
מצד שני יש לנו מערכת עובדת (האתר עצמו) מה שאומר שניתן לבצע בדיקות דינמיות.
באתר אינטרנט כשאין איפיון מסודר נהוג להכין או לבקש מפת האתר כדי להבין מה
הפונקציות שהאתר מכיל ומה רמת המורכבות שלו.
* משימה ראשונה: הכן מפת אתר לאתר שבחרת, יש לכלול את הלשוניות הראשיות ותתי
האפשרויות שמסתתרים תחתן.
### 2. במסגרת הבדיקה אנחנו לא נבצע TEST CASES כפי שלמדנו, אלא נעבוד ב-2 צורות ידועות
ונפוצות כאשר לא קיים איפיון:
* בדיקה שמבוססת על רשימת תיוג בנויה מראש (CHECK LIST) שאותה אתם
מקבלים ממני וממלאים בהתאם למה שאתם מוצאים.
* מה שלא רלוונטי יסומן כ- N/A (באנגלית: NOT APPLICABLE)
* מה שמצאתם אתם מציינים ליד כל שורת בדיקה את התייחסותכם בהתאם למה
שנבדק.
* בדיקה חופשית לפי האינטואיציה האישית שלכם EXPLORATORY TESTING
מתאים מאוד כשאין מסמכים מסודרים כשיש חוסר בזמן או בכ&quot;א.

### 3. יש לבחון אתר חינמי שיאפשר לכם להכניס לשם את התקלות, חשוב להכיר כמה שיותר
ולבחון את הכי ידידותי עבורכם, בתעשייה הנפוצים ביותר הם : 
* JIRA מבית מיקרוסופרט

* הערה: הבאג צריך לכלול את כל החלקים כפי שלמדנו איך פתוחים תקלה, חשוב
מאוד לדרג נכון את עוצמת הבעיה לפי הפרמטרים שלמדנו
(CRITICAL / HIGH / MEDIUM / LOW )
* לדאוג שהתיאור יכיל את 3 הנושאים: מה קרה? איפה קרה? איך קרה?
ולא לשכוח להוסיף צילום מסך ערוך!

### 4. יש להגיש את מסמך ה-STR לפי הטמפלייט שהעברתי לכם.
חשוב מאוד שהמסמך יכיל את הדברים הבאים:
* לפחות 5-6 סטטיסטיקות מעניינות לשיקולכם, להלן המלצות שלי אפשר גם לחשוב
על דברים נוספים,
* כמות תקלות ורמת חומרה / כמות תקלות ושם הבודק שמצא / כמות תקלות ובאיזה
* מודול/לשונית הן נמצאו / כמות תקלות שנמצאו לפי סוג בדיקות

ניתן ורצוי להוסיף בחלק של התוצאות SPR (SOFTWARE PROBLEM REPORT)
שהוא קובץ שמכיל את 10-12 הבאגים הכי קריטיים שעדיין פתוחים ועליהם נרצה
לשוחח במעמד ישיבת הצוות בוא מוצג ה-STR.
יש לדאוג שהבאגים יהיו מסודרים לפי רמת חומרה בסדר יורד, דוגמא מ-AXOSOFT
שם זה מדורג לפי PRIORITY כיון שאין בתוכנה SEVIRITY

lowMediumHighCritical
0
5
10
15
20
25
30
35
40

מספר תקלות

 יש לבחון ולתאר במסמך מה סוג האתר שנבחר (ממשלתי, קניות, רשת חברתית
וכו&#39;) ומה עושים אתו? מי הם משתמשי הקצה הפוטנציאליים.
 חשוב לציין בהתאם מה נבדק ומה לא,
באתרים בדרך כלל GUI ו-FUNCTONALITY
זה חובה לצד בדיקות COMPATIBILITY על 3 הדפדפנים המובילים.
חשוב לוודא נגישות (זה חוק במדינת ישראל, ואם האתר לא מכיל לפחות 12
אופציות זה כבר באג, בהנחה שהנגישות בכלל קיימת)
נושאים נוספים שתמיד ניתן לבדוק באתר: שרידות והתאוששות כתוצאה מאיבוד
רשת או קריסת אתר, זמני תגובה (לא יותר מ-2 שניות למסך אחרת זאת תקלה)
נושאים נוספים: עומסים אין לנו יכולת לבדוק כרגע, תחזוקתיות אלא אם כן בדקתם
את הקוד וכו&#39;&#39;.
 מסקנות והמלצות:
יש לציין באופן ברור מה ההמלצה שלכם לגבי המוצר, האם הוא ראוי להיות באוויר
או שכדאי להוריד אותו לשלב של תחזוקה ושיפורים.
ההמלצה חייבת להיות ברורה ולהישען על הסטטיסטיקה שהצגתם.
מסקנות יכולות להירשם גם על המוצר וגם על הפרויקט עצמו, למשל: מבחינת
הפרויקט התעכבנו כי לא היה לנו איפיון מסודר. מבחינת הפרויקט נחלנו הצלחה
בשימוש במוצר כזה או אחר שבחרנו לתיעוד התקלות והוכח כיעיל.
מבחינת מוצר: חווית המשתמש הייתה נעימה לכלל הבודקים וכד&#39;.
יש להשוות את האתר ל-2 אתרים בארץ ו-2 אתרים בחו&quot;ל.
בארץ: אתר אחד מתחרה ישיר ואתר אחד שנמצא בענף או קטגוריה שונה.
בחו&quot;ל: אתרים באותה קטגוריה ממדינות שונות, אחד באותה רמה ואחד בליגה של
הגבוהים.
למשל: אם בדקתי את האתר של מועדון הספורט מכבי נתניה.
עליי להשוות אותו למועדון כדורגל באותו סדר במדינה (למשל הפועל ת&quot;א)
להשוות אותו לאתר זהה בענף אחר, למשל: מועדון כדורעף מכבי ת&quot;א
או מועדון ספורט טניס רמת השרון.
מעבר לזה עליי להשוות את האתר למועדון כדורגל בינוני במדינה אחרת.
ולמועדון כדורגל גדול עתיר ניסיון ומשאבים
(ליברפול, יובנטוס, באיירן מינכן).
דוגמא נוספת: אם בדקתי אתר רכישת מזון: שופרסל אונליין.
בארץ: אבדוק את האתר של יינות ביתן / אבדוק את אתר הקניות של מחסני חשמל
בחו&quot;ל: אבדוק אתר קניות בינוני באנגליה / אבדוק אתר קניות גדול בארה&quot;ב (TESCO)

בונוסים:
ניתן להפיק בונוס על יצירת משוב חווית משתמש ובו מס&#39; שאלות פתוחות ומס&#39; שאלות סגורות
שניתן לייצר ב-GOOGLE DOCS ולהעביר ל-20 עד 40 איש במייל למילוי.
את התוצאות ניתן לשלב במסגרת המסקנות והסטטיסטיקות ולהתייחס לנושא של UX

ניתן להציג את הפרויקט בקובץ PPTX לפני הכיתה, לקחת בעיקר את עיקרי הדברים מהדוח ולהציג
לפני הקהל תוך התייחסות לסטטיסטיקות לניתוחים ולהמלצות.
