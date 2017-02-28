# js-simple-grid
Simple javascript task 

##Challange: Create grid with users and actions

1) Create simple markup, but it should be pretty enough.
```
| #Username | #Actions        |
| John Doe  | [Edit] [Remove] |
...

[Add User]
```

2) Use alert, prompt, confirm for errors, add/edit, remove confirmation. And wrap this actions(modal windows) in Promises. For example when I call prompt to add new user: 

```javascript
dialogPrompt().then(function(data){ 
  // data is user from prompt
  addUser(data);
})

function addUser(username){
  var template = '<li>' + username + '</li>';
  table.appendChild(template);
}
```

3) You should check simple errors. For example if You put empty user anme in prompt than You should show alert with error message `Please, fill user name`. 

4) You shouldn't save users anywhere (local storage or something else) it can be dynamically. Major things are code quality and good approach with promises.

### Good luck :)
