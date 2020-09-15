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


## Password Input
### type="password": When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. 

### All other attributes are same.

![forms](https://user-images.githubusercontent.com/70091044/93193746-ec783780-f74f-11ea-9bfc-35e4ea36e3e1.PNG)

## Text area < textarea >
### The < textarea > element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag. Any text that appears between the opening < textarea > and closing < /textarea > tags will appear in the text box when the page loads.

## Radio Button
### type="radio": Radio buttons allow users to pick just one of a number of options.
### value: The value attribute indicates the value that is sent to the server for the selected option. The value of each of the buttons in a group should be different (so that the server knows which option the user has selected).

![radio input](https://user-images.githubusercontent.com/70091044/93194643-fbabb500-f750-11ea-88c4-f8f2e794c74d.PNG)

## Checkbox
### type="checkbox": Checkboxes allow users to select (and unselect) one or more options in answer to a question.
### value:The value attribute indicates the value sent to the server if this checkbox is checked.

## Drop Down List Box: < select >

### The < select > element is used to create a drop down list box. It contains two or more < option> elements. 

### < option >: The < option > element is used to specify the options that the user can select from. The words between the opening < option > and closing < /option > tags will be shown to the user in the drop down box.

