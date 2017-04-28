# \<iron-moment-validator\>

Polymer 1.x behavior that validates date and time input using momentjs and optional locale support.

## Usage

```html
<iron-moment-validator date-format="DD/MM/YYYY" validator-name="dateValidator"></iron-moment-validator>
<paper-input auto-validate label="Enter a valid date string" validator="dateValidator"></paper-input>
```

```html
<iron-moment-validator date-format="L" locale="de" validator-name="dateValidator2"></iron-moment-validator>
<paper-input auto-validate label="Enter a valid german date (DD.MM.YYYY)" validator="dateValidator2">
```

## Install 

```
bower install iron-moment-validator --save
```

## Viewing the Element

```
$ polymer serve --open
```
