# WEBVIEW1

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Img](#img)
- [Dependence](#dep)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)




## Background

在无人驾驶量产项目中，车身集成的各种不同类型的传感器需要经过相应的算法模块处理后显示在汽车中控屏上。这些传感器包括：激光雷达、毫米波雷达、摄像头等，模块处理后的输出包括障碍物、本车车速、车道边界等信息。将如此多的信息，以一种直观的方式呈现在中控屏上，并且要求低延时，这对前端显示是一个挑战。开发的整体工程有如下特点：
1.可在浏览器中直接运行；
2.数据通信采用mqtt协议；
3.可视化采用three.js库，按照view.proto文件接收并显示各类数据；

## Install

将整个工程部署在nginx的根目录下，然后在浏览器中打开即可。


## Usage

1. clone 项目工程至/var/www/html下，或clone至nginx的根目录html目录下
2. 在浏览器中输入localhost:port/webview1/ 即可
3. 按住 ctrl + shift + i 进入开发者模式，在刷新处采用hrad reload刷新

## Img

![Image text](https://github.com/ibertli/webview1/blob/main/source/imgs/%E6%95%88%E6%9E%9C%E6%88%AA%E5%9B%BE.png)

## Dependence

mqttws31.js
protobuf.min.js
three.js

## Maintainers

[@ibertli](https://github.com/ibertli).

## Contributing

Feel free to dive in! [Open an issue](https://github.com/RichardLitt/standard-readme/issues/new) or submit PRs.

## License

[MIT](LICENSE) © Richard Littauer
