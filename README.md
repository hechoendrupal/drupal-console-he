
# drupal-console-he
DrupalConsole Hebrew Language / בעברית

# גרסה בעברית

## Usage -  אופן השימוש

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To install Drupal Console package in other languages check the packages available at [https://packagist.org](https://packagist.org)


### Install Drupal Console - התקנה על ידי שימוש בטרמינל

To install the appropriate version of Drupal Console project for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher - התקנה בעזרת אשף התקנות

In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal,  a Drupal Console launcher was created. In order to facilitate to load the Drupal Console commands available to each
Drupal 8 website,

To install Drupal Console launcher globally follow the instruction below.

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

</span>PR (= Pull request)<span style="direction:ltr;text-align:left;"> נ.ב. : יש לדחוף את השינויים מהעותק שלך לפרוייקט ממנו יצאת על ידי פקודת
 וזאת על מנת להמנע מקונפליקטים עם תורמי קוד אחרים.
</div>
