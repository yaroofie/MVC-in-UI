# front-end folder structure for js projects

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