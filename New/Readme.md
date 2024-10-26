The HTML Form Element is used to create HTML froms

It is a container that can contain different types of input elements like
- Text Fields
- Checkboxes
 and many more

Why Form Element
- Form has special Event (submit Event)
- submit event will e triggered on pressing Enter key


The prevent Default() method prevents the occurrence of default action normally

Here in the form, it prevents the default behavior of submit event



A form Event is an Event that can occur within a form

Form Events:
- blur
- focus
- change
Blur Event: The blur event happens when an element has lost focus


The HTML Select Element is used to create a drop-down list
- Each menu options of the drop-down list is defined by the Option Element
- The text content of the Option Element is used as a label
- Every Option should contain a value attribute
- It specifies the value of the given Input Element
- Every option should contain a value atttribute
- It specifies the value of the given Input Element



For those attributes, we only specify the name of the attribute

The presence of a boolean attribute represents the true value and the absence represents the false value
- selected
- checked
- disabled
- readonly
- default

        <select id="status" class="form-control">
                <option value="Active" selected>Active</option>
                <option value="Inactive">Inactive</option>
            </select>

The selected attribute specifies that an option should be pre-selected when the page loads


A radio button is used to select one option among a list of given options

<input type="radio" value="Male" name="gender" />
The HTML name attribute specifies a name for an HTML Element
All the radio buttons with same name collectively called as a radio group

Within a group only one radio button will be selected at a time



The checked attribute specifies that a input element should be pre-selected(checked) when the page loads