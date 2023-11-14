# **Volha Tsiareshka**
*****************************

## **Contacts**
* _Location:_ Minsk, Belarus
* _Email:_ c_h_e_r_r_y@tut.by
* _GitHub:_ Olga-Ter
* _Telegram:_ @TereshkoOI
* _Discord:_ Olga-Ter

## **About Me**
My main job is teaching. I understand that continuous learning is an integral part of development. Training will allow me to upgrade individual skills, gain new knowledge and skills, master new tools.

## **Skills**
* HTML&CSS
* JavaScript Basic
* VS Code

## **Code Example**
```
function check(str, bracketsConfig) {
  let isCheck;
  let Stack = [];
  if (!str) {
    return;
  }
  else {
    Stack.push(str[0]);
    for (let i = 1; i < str.length; i++) {
      Stack.push(str[i]);
      bracketsConfig.forEach(element => {
        if (str[i] == element[1] && Stack[Stack.length-2] == element[0]) {
          Stack.pop();
          Stack.pop();
        }
      });
    }
  } 
 
  Stack.length > 0 ? isCheck = false : isCheck = true;
  return isCheck;
}
```

## **Experience**
[cssMemeSlider](https://olga-ter.github.io/cssMemeSlider/cssMemeSlider/)
[image-galery](https://rolling-scopes-school.github.io/olga-ter-JSFEPRESCHOOL2023Q2/image-galery/)
[random-game](https://rolling-scopes-school.github.io/olga-ter-JSFEPRESCHOOL2023Q2/random-game/)

## **Education**
**_University:_**
Belarusian State University of Informatics and Radioelectronics affiliate Minsk Radio Engineering College
**_Courses:_**
RS Schools Course «JavaScript/Front-end. Stage 0»

## **English**
Intermediate

