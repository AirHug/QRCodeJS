[中文说明](/README_zh.md)

# QRCodeJS
Cross-browser QRCode generator for javascript. You can add img in QRCode.
QRCode.js is javascript library for making QRCode. QRCode.js supports Cross-browser with HTML5 Canvas and table tag in DOM.
QRCode.js has no dependencies.

## Basic Usages
```
<div id="qrcode"></div>
<script type="text/javascript">
new QRCode(document.getElementById("qrcode"), "https://github.com/JianmingXia/QRCodeJS");
</script>
```

or with some options

```
<div id="qrcode"></div>
<script type="text/javascript">
var qrcode = new QRCode(document.getElementById("qrcode"), {
	text: "https://github.com/JianmingXia/QRCodeJS",
	width: 128,
	height: 128,
	colorDark : "#000000",
	colorLight : "#ffffff",
	correctLevel : QRCode.CorrectLevel.H,
	img_src: "img/user.jpg",
	img_width: 50
});
</script>
```

and you can use some methods

```
qrcode.clear(); // clear the code.
qrcode.makeCode("http://github.com"); // make another code.
```

## Browser Compatibility
IE6~10, Chrome, Firefox, Safari, Opera, Mobile Safari, Android, Windows Mobile, ETC.

## License
MIT License


# Notice
This repository is base on [qrcodejs](https://github.com/davidshimjs/qrcodejs), but now author is stop update, so I add this. If I have infringed, please tell me, I'm sorry, I will delete this.
