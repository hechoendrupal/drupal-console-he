
# drupal-console-he
DrupalConsole Hebrew Language / בעברית

# גרסה בעברית

## Usage -  אופן השימוש
<div dir="rtl" align="right" style="direction:rtl;text-align:right;">
הדרופל קונסול מותקן באופן דיפולטי עבור כל אתר דרופל 8  בשפה האנגלית.

על מנת להתקין את הדרופל קונסול בשפה אחרת יש לבדוק האם קיימת גרסא או חבילה ב[https://packagist.org](https://packagist.org)
</div>

### Install Drupal Console - התקנה על ידי שימוש בטרמינל
<div dir="rtl" align="right" style="direction:rtl;text-align:right;">
על מנת לוודא איזו גרסת דרופל קונסול תואמת לגרסת הדרופל המותקנת אצלך יש להריץ את הפקודה הרשומה מטה
</div>
```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher - התקנה בעזרת אשף התקנות
<div dir="rtl" align="right" style="direction:rtl;text-align:right;">
בכדי למנוע התנגשויות בין גרסאות דרופל כאשר גרסת הדרופל היא גרסת ביניים (בין גרסא מינורית לגרסא מג׳ורית)נוצר אשף הגרסאות.
 וגרסאות דרופל קונסול
In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal,  a Drupal Console launcher was created. In order to facilitate to load the Drupal Console commands available to each
Drupal 8 website,

To install Drupal Console launcher globally follow the instruction below.
</div>
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

<div dir="rtl" align="right" style="direction:rtl;text-align:right;">
<strong>כיצד ניתן לתרום </strong>

למעוניינים לתרום לתרגום הפרוייקט הזה , יש לבצע את השלבים הרשומים מטה על מנת ליצור את סביבת העבודה.


- [דרישות הפרייקט](https://docs.drupalconsole.com/en/contributing/project-requirements.html)
- [הורדת הפרוייקט](https://docs.drupalconsole.com/en/contributing/getting-the-project.html)
- [הרצת הפרוייקט](https://docs.drupalconsole.com/en/contributing/running-the-project.html)

 נ.ב. : יש לדחוף את השינויים מהעותק שלך לפרוייקט ממנו יצאת על ידי הפקודה הרשומה מטה
 על מנת להמנע מקונפליקטים עם תורמי קוד אחרים.
 ```PR (= Pull request)```
</div>
