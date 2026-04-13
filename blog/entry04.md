# Entry 4
##### 3/9/26
## Context
When working on a big project, you really want some help with certain stuff to make your life a lot easier. In this entry, Ill talk about how I plan to use the my tool, [Bulma](https://bulma.io/) to help me when working on my freedom project. Bulma is an open source CSS Framework that lets you use premade code and implement them into your own website. Being new to this, first I had to learn how to use my tool which has us start tinkering around with our tools to get a grasp of what we can really do. Some examples are:

### *[Progress Bar.](https://bulma.io/documentation/elements/progress/)*
A progress bar is used to show the progress made by something through how full a bar is. As shown below:
<img width="1449" height="264" alt="image" src="https://github.com/user-attachments/assets/e7489dae-d9e8-42fd-b5d7-f0baa4e86a58" /><br>
The code snippet used to make one is: 
``` html
 
<progress class="progress is-link" value="15" max="100">
  15%
</progress>
```
I tinkered with it by adjusting the `value' which seems to dictate how full the bar is based on its maximum. Although progress is built already in html, Bulma gives it a more clean look through "progress". You can also adjust the color of the bar with Bulma's built in classes, such as "is-danger" being red and the one above, "is-primary" making it green.

Another cool thing I learned about the progress bar is its properties regarding the value. If the value is empty, it gives a more vivid look with the bar actually look likes it loading as shown below:<br>
<img width="512" height="91" alt="image" src="https://github.com/user-attachments/assets/e461b033-5a96-4a55-9e93-8c3bd9bf5b01" />
<br> 
``` html
 
<progress class="progress is-danger" value="" max="100">
  15%
</progress>
```
### *[Tables](https://bulma.io/documentation/elements/table/)*
Another part of Bulma I tinkered with was with how to make a table. A table showcases rows and columm that holds data in its cells. A table like the progress bar is already present in normal html but bulma does make it look cleaner by giving its the class "table". You can see a table below:<br>
<img width="137" height="90" alt="image" src="https://github.com/user-attachments/assets/40eb6df0-41f0-4359-a4e8-1e200662acdd" /><br>
Though small, it takes quite a bit of code to make:
``` html
  <table class="table">
    <tr>
      <th> Hi</th>
      <th> People</th>
    </tr>
    <tr>
      <td> No</td>
      <td> Way</td>
    </tr>
  </table>
```
The `<table>` makes a table, `<tr` stands for the rows which we can see there are two, `<th>` stands for heading which can signify what the that columm is about if used properly (I didn't). `<td>`, like `<th>` is in a row but instead standing for each cell, which is the makeup for the stuff below the headers. You can tweak and tinker with the table by adding more rows, columms, or cells.
## Skills
1. Attention to Detail, I believe that I have developed this skill because it was what allowed me to learn some cool things about each element. At first, the progress was just copy n pastsed, without looking at its makeup which was later what helped me learn how it truly worked. I learned that its "value" and "max" played a big part in how it ended up looking.
2. How to read. I believe that I developed this skill because it was what allowed me to utilize the table properly. At first, I was trying to base my own table off of an example which was way too advanced because it had a lot of data so the code was smore difficult to read. Instead, I altered to learn what each part did beforehand and then was successfully able to make my own table.
## Conclusion
As I continue learning about Bulma, Im excited on not only learning how to use Bulma but also new elements/components. Since bulma adds css to existing html elements, I can not only learn how to decorate those properties but those properties in general. Going into this, I didn't know about <table> or <progress> inside of html.
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
