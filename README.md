# mp_program
总结小程序开发中遇到的问题

1、input输入16位卡号，每4位隔开一个空格时，当把input的type设置为number、idcard、digit时，在iOS可以，安卓上不行。把type设置为tel就兼容了，只是吊起的不是数字键盘
2、引导用户下载APP的问题：最终通过客服消息实现
