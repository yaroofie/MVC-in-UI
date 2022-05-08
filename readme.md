# MVC pattern in UI

the use of MVC pattern will help you have a solid and clean folder structure 
in your front-end development and every one will understand your project flow
better.

## Models

write your classes and stores in this folder

## Views

use the atomic design structure to manage your components in this folder

## Controllers

write all of your global functionality in this folder as controllers like 

```
import FormValidationController from "@controllers/FormValidationController.js"
let validator = new FormValidationController()
if(validator.check(this,['email_field'])) {
   // do something
}
```
