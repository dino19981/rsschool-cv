# CV

__Name__: Stepanov Artem Sergeevich

__E-mail__: dino.olimp@mail.ru

__Telegram__ : dino19981

__About me__: in January 2021 I decided to change jobs and started learning programming, first I studied Html, css, then java script according to the Learn js tutorial.

__Skills__: HTML5, CSS3, JS, Git, Vue.js, Photoshop.

**Code example**:

```javascript
function runLengthEncoding(str) {
  let result = [];
  let arr = str.split('');

  for (let i = 0, count = 0, y = 0; i < arr.length; y++, i++) {
    for (let k = 0; k < arr.length; k++) {
      if (arr[i] === arr[i + k]) {
        count++;
      } else {
        break;
      }
    }

    result[y] = [];
    result[y].push(count, arr[i]);
    i += count - 1;
    count = 0;
  }
  return result;
};
```

**Education**: in 2021 he graduated from the SamGUPS Institute, Faculty of Main Transport.

**Languages**:English (B2)
