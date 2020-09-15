# Forms
## Form Structure: < form >
### Form controls live inside a < form > element. This element should always carry the action attribute and will usually have a method and id attribute too.
## action
### Every < form > element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
## method
### Forms can be sent using one of two methods: 
* get :  With the get method, the values from the form are added to the end of the URL specified in the action attribute. The get method is ideal for :

1- short forms (such as search boxes).

2- when you are just retrieving data from the web server

* post: With the post method the values are sent in what are known as HTTP headers. As a rule of thumb you should use the post method if your form:

1- allows users to upload a file.

2- is very long

3- contains sensitive data (e.g. passwords)

4- adds information to, or deletes information from, a database
### Defult method for form is *get*


## Text input: < input > 
### The < input > element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.

* type="text": When the type attribute has a value of text, it creates a singleline text input

* name: The value of this attribute identifies the form control and is sent along with the information they enter to the server.

* size: The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input 

* maxlength: You can use the maxlength attribute to limit the number of characters a user may enter into the text field.
