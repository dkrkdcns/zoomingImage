# 이미지 확대 기능
이미지에 `mouseover` 하면 이미지가 확대됩니다.

![](https://github.com/dkrkdcns/zoomingImage/blob/master/public%20(%EC%A4%91%EA%B8%89%EB%B0%98)/img/md.png)

```js
$(function () {
    var zoom = new Zoom(선택자, 확대, 속도);
    // 선택자: String ex:('.zoom')
    // 확대: Number ex:(1.4)
    // 속도: Number ex:(400)
});
```

- 작성자 : 이세진
- 저작권 : MIT