## GitHub Flavored Markdown Code

Inline code is console.log('very useful') for short snippets.

But for multi-line pieces of code, a code block is best.

self.logIn = function(){
  auth.$signInWithPopup('google').then(function(firebaseUser){
    console.log('Firebase Authenticated user as: ', firebaseUser.user.email);
  })
  .catch(function(error){
    console.log('Authentication failed: ', error);
  });
};
