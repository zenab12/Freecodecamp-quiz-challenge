# few tips i learned while coding this tasks :
- role attribute is important for accessibilty as (User interface components need a role, a name and sometimes a value, to ensure that people using assistive technologies are able to use them. Examples of assistive technologies are screen readers, switch controls and speech recognition software.) about tag to screen reader with (arialabeldby) attr 
and this is link to know more about [roles in w3](https://www.w3schools.com/accessibility/accessibility_role_name_value.php).or this [roles in MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles)
- we can use this format of html structure and hide it using css to make screen readers understand what is this abbreviation 
 
 ```
 <label for="birth-date">D.O.B.<span class="sr-only">(Date of Birth).</span></label>
 ```
 
 ```
.sr-only{position: absolute;
width: 1px;
height: 1px;
padding: 0;
margin: -1px;
overflow: hidden;
clip: rect(0, 0, 0, 0);
white-space: nowrap;
border: 0;
}
```
 
- we can use `max(width in px as example, width in vw as another example) or min(width,another width) ` to change width for element automated 

