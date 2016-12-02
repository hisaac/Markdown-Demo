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
