---
sidebar_position: 2
---

##  Responsive Web Design course by freeCodeCamp - Building a Cat Photp App

### Basic HTML elements

|   HTML elements| Descr/ use  |
|---|---|
|<"main"> <"/main">|Adding this tag that contains content makes html easier to read for SEO. This tag comes right after <"body"> tag.|
|<"section"> <"/section"> | Adding this tag helps organize content in html file. Each section can contain headers, text, images that relate. Also helps with SEO.  |
|<"figure"> <"/figure">  |  Adding this tag contains self-contained content such as img with caption, the <"figcaption"> tags is used inside it to insert a description. |
|<"em"> | tags is an italic styling.|
|<"strong">  |  is for bold.|
|<"footer"> <"/footer"> |... |
| <"style** <"/style"> |elements in html file can be added in the <"head"> tag.|
| <"link rel=”stylesheetName” href=”stylesheetNameWith Extension” /">  |can be used to link a stylesheet in an html file.|
| <"meta name="viewport" content="width=device-width, initial-scale=1.0" /">  |meta tag to be added in <"head"> element to ensure responsive design.| 
| <"div"> for style uses  |the <div> element can be used in body element to facilitate style selection|
|lang attribute <br> <"html lang=en>|Attribute to define the page language.|
|<"title"></"title">| Title in the <"head"> element. THis title appears in the browser tab.|
|<"!DOCTYPE html"> | All pages should begin with this special string, known as a declaration and ensures the browser tries to meet industry-wide specifications.|

 
## Creating forms in HTML

|HTML elements |Descr/ use    |
|---|---|
|<"form"> </"form">|to add forms/ surveys in html.|
| <"form action=«   » <"/form">   | **action** attribute in <"form"> tags specifies the url path to which form responses will be sent.  |
|<"input/"><br><"input type=“text”"> | This tag helps in collecting data from a form. It can have various attributes such as “type” which defines the text input/control (to upload files) fields to add passwords etc. Input element is inline- it does not appear in another line and is self-closing.  |
|<*input type=“text” name=“”> |  **name** attribute is to define the type of information collected. |
|<"input type=“text” placeholder=“”> | **Placeholder** text lets people know what input to add in a field.  |
|<"input type=“text” required> | Required empty attribute to prevent form sending without certain info entered.|
|<"button"> <"/button"> <br> <"button type=« submit » submit <"/button">|Adding a button tag under form code, directs to path added in form action line? <br> Button element is inline- it does not appear in another line. <br> Default behavior of this button is sending form but in case wanting to force the behavior even further adding “type” attribute can help.|
|<input type="radio" text  | Radio buttons for single choice.|
|<input type="checkbox"*> text| checkbox buttons for multiple choice.| | 
|<"label"> <"/label"> | Tag helps to associate text to input element-lack of specificity of clicking ( same result if clicked near and not exactly on)- Helps with accessibility (screen readers). <br> Make sure there is space between the text and the input element.  |
|Id attribute <br> Ex: <input type =« radio » <br> id=« example »| The id attribute is used to identify specific HTML elements. When elements have multiple attributes, the order of the attributes does not matter. |
|Name attribute (for single selection in radio buttons) |  To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value. <br> Also helps servers to process your web form, especially when there are multiple checkboxes.|
|Value attribute selection in radio buttons |  The value attribute helps distinguish which radio buttons were selected when submiting a form as they can share the same name. Value can be set to the id value for example.|
|fieldset element |  Used to group related inputs and labels together in a web form. fieldset elements are block-level elements, they appear on a new line. This creates some sort of a box arround the grouped elements.|
|legend element <"legend">blabla<"/legend">|  Acts as a caption for the content in the fieldset element. Gives context on what info to enter. |
|<"label for=«  » <"/label"> For attribute | Alternative to putting the whole input code in label by just putting label for=«  »surrounding the button text. |
|checked attr <br> <input id=“” type=“” name=“” value=“” checked"> |Makes a checkbox checked or radio button selected by default. |
| |

> Block level elements are elements that appear on new lines contrary to inline lements.