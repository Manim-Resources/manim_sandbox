![logo](assets/logo.png)

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](http://choosealicense.com/licenses/mit/)
![QQ](https://img.shields.io/badge/QQ-862671480-red.svg?style=flat)

manim_sandbox是由[manim-kindergarten](https://github.com/manim-kindergarten)的成员所管理维护的一个代码仓库，目的在于汇总整合各成员提供的[manim](https://github.com/3b1b/manim)代码和模块。

运行该项目中的代码需配置好[manim](https://github.com/3b1b/manim)才能运行。部分代码所用的manim版本可能在[3B1B](https://github.com/3b1b)的[manim](https://github.com/3b1b/manim)的基础上略有删改。

其中一些素材和地址等由于某些文件的移动path可能有些不对，需要修改才能运行。<br>  
由于编程水平有限，加上对Grant的代码理解有限，代码有时会出现不太好的实现方式，敬请谅解。

## 关于成员

此外，不少[manim-kindergarten](https://github.com/manim-kindergarten)的成员都是[B站](https://www.bilibili.com/)up主，项目中的不少代码可能会用到相关的[B站](https://www.bilibili.com/)视频中。<br>

以下是部分成员的[B站](https://www.bilibili.com/)主页链接和GitHub中的相关manim项目链接：

<table>
  <tr>
    <td rowspan="2">
      <a href="https://github.com/Solara570" target="_blank">
        <img src="https://avatars3.githubusercontent.com/u/21032813?s=460&u=43ba8a5a95fe1bc00bd7baedcd2c63987426faa6&v=4" alt="Solara570" width="60" height="60">
      </a>
    </td>
    <td><a href="https://space.bilibili.com/3557916/">Solara570的B站主页</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Solara570/demo-solara">GitHub中manim项目</a></td>
  </tr>
  <tr>
    <td rowspan="2">
      <a href="https://github.com/cigar666" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/37494715?s=400&u=1c0608b3aaeee0116720a5bc79bb55738ef14277&v=4" alt="cigar666" width="60"
        height="60">
      </a>
    </td>
    <td><a href="https://space.bilibili.com/66806831/">cigar666的B站主页</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/cigar666/my_manim_projects">GitHub中manim项目</a></td>
  </tr>
  <tr>
    <td rowspan="2">
      <a href="https://github.com/Tony031218" target="_blank">
        <img src="https://avatars1.githubusercontent.com/u/44120331?s=460&u=fd846e0820e2880970eb1081ea4a47f84a8708db&v=4" alt="鹤翔万里" width="60"
        height="60">
      </a>
    </td>
    <td><a href="https://space.bilibili.com/171431343/">鹤翔万里的B站主页</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Tony031218/manim-projects">GitHub中manim项目</a></td>
  </tr>
  <tr>
    <td rowspan="2">
      <a href="https://github.com/pdcxs" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/3760797?s=460&u=f410435b95a8ed363008daef04b67fbb627260ee&v=4" alt="pdcxs" width="60"
        height="60">
      </a>
    </td>
    <td><a href="https://space.bilibili.com/10707223/">pdcxs的B站主页</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/pdcxs/ManimProjects">GitHub中manim项目</a></td>
  </tr>
  <tr>
    <td rowspan="2">
      <a href="https://github.com/136108Haumea" target="_blank" alt="有一种悲伤叫颓废">
        <img src="https://avatars0.githubusercontent.com/u/61341382?s=460&u=9e467aec700e2024c2583112f2388c0234ccc3d6&v=4" alt="有一种悲伤叫颓废" width="60"
        height="60">
      </a>
    </td>
    <td><a href="https://space.bilibili.com/387821788/">有一种悲伤叫颓废的B站主页</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/136108Haumea/my-manim">GitHub中manim项目</a></td>
  </tr>
</table>

## 关于manim的学习和交流

我们有一个manim交流群（QQ群：862671480），欢迎大家加入交流。<br>
对于manim学习中可能遇到的问题，可参考[manim常见问题 v2.1](https://github.com/manim-kindergarten/manim_sandbox/blob/master/documents/manim%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98v2.1.pdf)<br>

## 关于项目中的代码规范问题

#### Ⅰ. 一些实用函数/类代码
提交到`utils`文件夹中
  1. 需要在文件头加上`# from @author`一行
  2. 需要在`utils/imports.py`中添加`import`
  3. 函数/类 需要有文档字符串(函数下的注释)
  3. 尽可能写一些注释方便学习，并要保证代码可读性
#### Ⅱ. 一些amazing的Scene代码
提交到`scenes`文件夹中
  1. 需要在文件头加上`# from @author`一行
  2. 需要在文件头部给出效果链接，或者将效果视频一并上传(文件名保持一致)
#### Ⅲ. 一些示例代码
提交到`demo`文件夹中
  1. 需要在文件头加上`# from @author`一行
  2. 示例尽可能规范，可添加注释说明以方便他人学习
#### Ⅳ. 自己视频的工程文件
提交到`videos`文件夹中
  1. 需要在文件头加上`# from @author`一行
  2. 在文件头部给出视频链接`# video address: https://......`，或将效果视频一并上传(文件名保持一致)
#### Ⅴ. 一些图片素材
提交到`assets`文件夹中
  1. 保证图片可以正常打开
#### Ⅵ. 一些对manim源码的更改
提交到旁边的[repo](https://github.com/manim-kindergarten/manim)中

## 关于代码使用的相关声明

  1. 代码主要用作大家交流学习使用，欢迎大家进行修改和补充<br>
  2. 允许使用部分相关代码进行视频创作，但如果使用代码较多请注明下出处<br>
  3. 禁止直接将该项目中的代码做简单无脑修改甚至不修改而做成视频<br>
  4. 禁止未经允许将本项目的代码用作其他商业行为<br>


最后，祝大家好运ღ( ´･ᴗ･` )
------------------
