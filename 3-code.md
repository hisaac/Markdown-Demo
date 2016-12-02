Inline code — `console.log('Wow Markdown!')` — is good for short snippets.

But for multi-line pieces of code, a code block is best.

```javascript
self.logIn = function(){
  auth.$signInWithPopup('google').then(function(firebaseUser){
    console.log('Firebase Authenticated user as: ', firebaseUser.user.email);
  })
  .catch(function(error){
    console.log('Authentication failed: ', error);
  });
};
```
