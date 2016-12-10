# wechat-css3-animate
css3动画兼容微信
```css
@-webkit-keyframes pulse {
    to {
        opacity: 0;
        -webkit-transform: scale(1);
        transform: scale(1);
    }
}

.member-photo-img::before,
.member-photo-img::after {
    -webkit-transform: scale(0.5);
    -ms-transform: scale(0.5);
    -o-transform: scale(0.5);
    transform: scale(0.5);
    -webkit-animation: pulse 2s linear infinite;
    animation: pulse 2s linear infinite;
    border: #fff solid 8px;
    border-radius: 9999px;
    box-sizing: border-box;
    content: ' ';
    height: 140%;
    left: -20%;
    opacity: .4;
    position: absolute;
    top: -20%;
    width: 140%;
    z-index: 1;
}
```
