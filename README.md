# Form for RegExp testing 
A form checking the correctness of data submitted by user (name, phone number, e-mail, URL) using the effect of Regular Expressions.

## Technologies:
HTML; CSS; RegExp;

## Filling presets:
Name:
* cyrillic symbols only;
* first letter is capitalized;
* 2 to 20 symbols allowed — this can be configured via minlength & maxlength attributes;
* double names are allowed — for example, Ann-Marie;

Email:
* latim symbols only;
* «at» @ — required symbol;
* dot . — required symbol;
* numbers, underscore, dash — allowed symbols;

Phone number:
* +7(925)900-90-90
* +7(925) 900-90-90
* +7 925-900-90-90
* +79259009090
* 89259009090

Site:
* starting with http:// or https://;
* afterwards www. — optional part;
* IP-address — 255.255.255.255 or domain name — jaderemi.ru;
* port — optional group aswell. Port starts with a colon, followed by 2 to 5 numbers. For example: :8080;
* path — a sequence of numbers, slash symbols or latin letters, having a pound at the end #;

### Link 
