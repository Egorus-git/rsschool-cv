# **Egor Kozitskiy: University student**

***

## Information about me:

#### Location: Moscow, Russia
#### E-mail: vizart532@mail.ru
#### GitHub: https://github.com/Egorus-git
#### Discord: Egorus#8605
#### Codewars: https://www.codewars.com/users/Egorus-git

***

## Resume:

 ##### I can work c++ and c# up to object oriented programming. I also know puthonat a basic level. I know how to make simple websites and work with figma. I'm currently learning Javascript and HTML/CSS because I love it and want to develop in it.

***

## My skills:

#### 1. Javascript
#### 2. HTML + CSS
#### 3. Git
#### 4. Figma
#### 5. DOM

***

## Code example:

##### The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.

```
function duplicateEncode(word){
  let result = '';
  word = word.toLowerCase();
  for (let char of word){
    word.split(char).length - 1 != 1 ? result += ')' : result += '('
  }
  return result;
}
```