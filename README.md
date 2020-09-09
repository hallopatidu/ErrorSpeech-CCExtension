# ErrorSpeech-CCExtension
A Extension for Cocos Creator
* Translate and speech errors to vietnamese (option)
* Rewrite cc.error fo this feature.

# Installation
* npm install
* copy to [CocosCreator Project] / packages / errorspeech
* Open CocosCreator and test.

# Example
HelloWorld.js
````
....
// After scene loaded
ctor(){
     try{
         // throw new Error("Cảm ơn đã theo dõi")
         // make a misstake.
         // this.labelss.makeLoop = "hello"
     }catch(err){
         cc.error(err)
     }
},
....
````


