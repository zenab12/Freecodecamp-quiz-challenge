# [Live Demo](https://zenab12.github.io/Freecodecamp-quiz-challenge/)
## few tips i learned while coding this task :
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

- The `address` element does not have to contain a physical geographical location. It can be used to provide a link to the subject.

- On the topic of visual accessibility, contrast between elements is a key factor. For example, the contrast between the text and the background of a heading should be at least 4.5:1.

- Certain types of motion-based animations can cause discomfort for some users. In particular, people with vestibular disorders have sensitivity to certain motion triggers.

The @media at-rule has a media feature called `prefers-reduced-motion` to set CSS based on the user's preferences. It can take one of the following values:

```
reduce
no-preference
```
    
```
@media (feature: value) {
  selector {
    styles
  }
}
```

- the navigation accessibility can be improved by providing keyboard shortcuts.

- The accesskey attribute accepts a space-separated list of access keys. For example:

```
<button type="submit" accesskey="s">Submit</button>
```
