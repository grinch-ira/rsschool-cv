1. **name**: *Hryniuk Iryna*
1. **contact information:** *mobile phone* ***+375259260633***, *email:* ***grinch.ira@gmail.com***
1. **information about yourself:** I am a student of the last year of the bntu, diligent, always striving to learn something new, purposeful
1. **skills:** *basic knowledge of python, django framework, c++, mssql*
1. **code examples:** 
 ```
var isAnagram = function(test, original) {
    const charCount = new Map()
    for(const c of test.toLowerCase().split("")){
      charCount.set(c,(charCount.get(c)||0)+1)
    }
    for(const c of original.toLowerCase().split("")){
      if(!charCount.has(c))
      return false
      charCount.set(c,charCount.get(c)-1)
    }
  return Array.from(charCount.values()).every(v=>v===0)
  };
  ```
1. **work experience:** *performing laboratory tasks at the university*
1. **education:** *I am a student of the last year of the bntu*
1. **English**: *beginner level*
