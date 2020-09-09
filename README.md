# ErrorSpeech-CCExtension
A Extension for Cocos Creator
* Translate and speech errors to vietnamese (option)
* Rewrite cc.error fo this feature.



## Installation
* cd ./error-speech
* npm install
* copy error-speech to [CocosCreator Project]/packages
* Open CocosCreator and test.

## Example
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

## Version
Cocos Creator 2.4.2
Node 12.18.3
