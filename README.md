# 漫画/图片翻译器免安装一键启动整合包

manga-image-translator是一款热门强大的图片漫画文字翻译软件，可以一键批量将图片文字翻译成指定语言文字，我基于当前最新版本制作了免安装一键启动整合包，方便大家快速上手体验。

![](https://raw.githubusercontent.com/aidayang/manga-image-translator-OneClick/refs/heads/main/UI.jpg)

## 效果演示

The following examples may not be frequently updated and may not represent the effect of the current main branch version.

<table>
  <thead>
    <tr>
      <th align="center" width="50%">Original Image</th>
      <th align="center" width="50%">Translated Image</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232265329-6a560438-e887-4f7f-b6a1-a61b8648f781.png">
          <img alt="佐藤さんは知っていた - 猫麦" src="https://user-images.githubusercontent.com/31543482/232265329-6a560438-e887-4f7f-b6a1-a61b8648f781.png" />
        </a>
        <br />
        <a href="https://twitter.com/09ra_19ra/status/1647079591109103617/photo/1">(Source @09ra_19ra)</a>
      </td>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232265339-514c843a-0541-4a24-b3bc-1efa6915f757.png">
          <img alt="Output" src="https://user-images.githubusercontent.com/31543482/232265339-514c843a-0541-4a24-b3bc-1efa6915f757.png" />
        </a>
        <br />
        <a href="https://user-images.githubusercontent.com/31543482/232265376-01a4557d-8120-4b6b-b062-f271df177770.png">(Mask)</a>
      </td>
    </tr>
    <tr>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232265479-a15c43b5-0f00-489c-9b04-5dfbcd48c432.png">
          <img alt="Gris finds out she's of royal blood - VERTI" src="https://user-images.githubusercontent.com/31543482/232265479-a15c43b5-0f00-489c-9b04-5dfbcd48c432.png" />
        </a>
        <br />
        <a href="https://twitter.com/VERTIGRIS_ART/status/1644365184142647300/photo/1">(Source @VERTIGRIS_ART)</a>
      </td>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232265480-f8ba7a28-846f-46e7-8041-3dcb1afe3f67.png">
          <img alt="Output" src="https://user-images.githubusercontent.com/31543482/232265480-f8ba7a28-846f-46e7-8041-3dcb1afe3f67.png" />
        </a>
        <br />
        <code>--detector ctd</code>
        <a href="https://user-images.githubusercontent.com/31543482/232265483-99ad20af-dca8-4b78-90f9-a6599eb0e70b.png">(Mask)</a>
      </td>
    </tr>
    <tr>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232264684-5a7bcf8e-707b-4925-86b0-4212382f1680.png">
          <img alt="陰キャお嬢様の新学期🏫📔🌸 (#3) - ひづき夜宵🎀💜" src="https://user-images.githubusercontent.com/31543482/232264684-5a7bcf8e-707b-4925-86b0-4212382f1680.png" />
        </a>
        <br />
        <a href="https://twitter.com/hiduki_yayoi/status/1645186427712573440/photo/2">(Source @hiduki_yayoi)</a>
      </td>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232264644-39db36c8-a8d9-4009-823d-bf85ca0609bf.png">
          <img alt="Output" src="https://user-images.githubusercontent.com/31543482/232264644-39db36c8-a8d9-4009-823d-bf85ca0609bf.png" />
        </a>
        <br />
        <code>--translator none</code>
        <a href="https://user-images.githubusercontent.com/31543482/232264671-bc8dd9d0-8675-4c6d-8f86-0d5b7a342233.png">(Mask)</a>
      </td>
    </tr>
    <tr>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232265794-5ea8a0cb-42fe-4438-80b7-3bf7eaf0ff2c.png">
          <img alt="幼なじみの高校デビューの癖がすごい (#1) - 神吉李花☪️🐧" src="https://user-images.githubusercontent.com/31543482/232265794-5ea8a0cb-42fe-4438-80b7-3bf7eaf0ff2c.png" />
        </a>
        <br />
        <a href="https://twitter.com/rikak/status/1642727617886556160/photo/1">(Source @rikak)</a>
      </td>
      <td align="center" width="50%">
        <a href="https://user-images.githubusercontent.com/31543482/232265795-4bc47589-fd97-4073-8cf4-82ae216a88bc.png">
          <img alt="Output" src="https://user-images.githubusercontent.com/31543482/232265795-4bc47589-fd97-4073-8cf4-82ae216a88bc.png" />
        </a>
        <br />
        <a href="https://user-images.githubusercontent.com/31543482/232265800-6bdc7973-41fe-4d7e-a554-98ea7ca7a137.png">(Mask)</a>
      </td>
    </tr>
  </tbody>
</table>



以前还和大家分享过另一个图片文字翻译工具<a href="https://nuowa.net/1519">《图片漫画翻译工具BallonsTranslator，支持人工校对》</a>，那个翻译工具支持人工手动修改翻译结果，适合对翻译内容准确度要求比较高的人，当前这个manga适合对翻译准确度要求不高，追求批量快速翻译的人使用。

## 漫画翻译软件manga-image-translator整合包使用说明：
首先将网盘内的软件压缩包下载到本地电脑上并解压出来。双击【启动软件.exe】运行软件

【开始】

选择单个图片文件或是文件夹，如果选择文件夹的话，路径地址后面不能有“\”,选择文件夹的话，软件会翻译处理该文件夹内的所有图片。

输出调试图：除了最终结果图片，还会输出很多中间处理图片，供调试参考使用。

跳过错误图像：遇到错误时跳过图像。

字体文件路径：想改变图片文字字体，可以自定义字体文件，路径中不要有非英文字符和空格

翻译前字典：如果有想替换的专有名词，可以在字典文档里设置，每行一对词，格式如下：


格式：源词[至少一个Tab/空格]目标词[至少一个Tab/空格][#注释 或 //注释]

翻译后字典：图片文字翻译完成后，如果有感觉不准确或是想替换的词，可以在字典里设置，格式和上面格式一致。

文本区域大小：设置文本擦除区域的卷积内核大小以完全清除文本残留，和【设置】里的卷积核大小重复了，两个参数功能一样。这里的设置可以不用管，用【设置】里的那个参数。

覆盖已翻译图像：如名字所述

跳过无文本图像：跳过没有文本的图像（不会保存）。

保存翻译文本：将翻译的文本保存到文本文件中。方便有些人查看翻译结果。

然后点击开始处理按钮，等待处理即可。处理结果会输出到项目文件夹内的result文件夹，注意这个result文件夹不能删除，否则可能会引起报错。

【设置】

翻译工具：使用哪个在线工具对识别的文字进行翻译。

翻译工具可以使用百度翻译，1分钟就可以申请下来，非常的简单，每个月有100万字符的免费额度，一般人应该够用。点击查看申请流程

《最新百度翻译api免费申请AppId和AppSecret流程，每月免费100万字符》

或是使用火爆强大的Deepseek，支持R1和V3模型，现在搞活动，新用户通过手机号注册可获得2000万 Tokens免费额度，注册链接：https://bit.ly/depsk1

翻译工具总共20多种，我只预设了5种，算是主流的，如果你想要用其它翻译工具的话可以告诉我，我给添加进去。

youdao

baidu

 deepl

papago

caiyun

 chatgpt

 none

original

 sakura

 deepseek

groq

gemini

custom_openai

  offline

  nllb

 nllb_big

sugoi

 jparacrawl

jparacrawl_big

m2m100

  m2m100_big

   mbart50

 qwen2

qwen2_big

目标语言：即为最终漫画想显示的语言，软件里我只预设了11种，其它语言简写代码如下所示：

CHS：简体中文

CHT：繁体中文

CSY：捷克语

NLD：荷兰语

ENG：英语

FRA：法语

DEU：德语

HUN：匈牙利语

ITA：意大利语

JPN：日语

KOR：韩语

PLK：波兰语

PTB：葡萄牙语（巴西）

ROM：罗马尼亚语

RUS：俄语

ESP：西班牙语

TRK：土耳其语

UKR：乌克兰语

VIN：越南语

ARA：阿拉伯语

SRP：塞尔维亚语

HRV：克罗地亚语

THA：泰语

IND：印尼语

FIL：菲律宾语（他加禄语）

渲染器：渲染从漫画翻译的文本，生成翻译后的文本图像，并进行额外的排版处理。会忽略某些其他参数选项

对齐方式：文本对齐方式（如左对齐、居中、右对齐等），影响排版美观。

字体大小：字体大小偏移量（如 +2 增大字体，-1 缩小字体），灵活调整文本尺寸，可以在输入框里手动输入其它数值。

文本方向：强制文本方向：h（水平）或 v（垂直）。适用于特定排版需求（如竖排日漫）。

字体颜色：自定义字体颜色，格式为16进制颜色代码，如 FFFFFF（前景色）或 FFFFFF:000000（前景+背景色）。用于解决原图背景干扰问题。

行距比例：行间距为字体大小 * 该值。水平文本默认为0.01，垂直文本默认为0.2，用于调整文本紧凑度。

跳过语言：若原文已是目标语言之一则跳过翻译，使用逗号分隔多个语言。例如：JPN,ENG，可节省时间。

图片放大比例：检测前应用的图像放大比例（如 2），可自行输入想要的数值，可以改善文本检测效果，但会增加显存消耗。

放大器：放大模型（如 waifu2x）。需与 upscale_ratio 配合使用。

恢复放大：翻译后将之前放大的图像缩小回原始大小(与–upscale-ratio配合使用)，节省输出文件体积。

旋转图像：旋转图像以优先检测垂直文本行。可能改善检测效果。

反色处理：反转图像颜色进行检测。可能改善检测效果

卷积核大小：设置文本擦除区域的卷积核大小，以完全清理文本残留，默认值为3

文本掩码扩展量：扩展文本遮罩以删除原始图像中剩余文本像素的程度，确保原文本完全覆盖。默认值为30

OCR模型（ocr）：使用的光学字符识别(OCR)模型，默认值为48px，可输入的值有：32px，48px，48px_ctc，mocr

【API KEY】

想用哪个翻译工具就输入哪个KEY，基本都可以免费申请使用。输入API 保存后需要重启软件，再去翻译图片，否则不会生效。

使用火爆强大的Deepseek，支持R1和V3模型，现在搞活动，新用户通过手机号注册可获得2000万 Tokens免费额度，注册链接：https://bit.ly/depsk1

点击左侧导航【API密钥】，右上角点击按钮【新建API密钥】，然后点击生成的密钥sk-s开头的这一串字符就是密钥


BASE URL为：https://api.siliconflow.cn/v1

境外用户也可以使用Google Gemini，资金充裕的也可以使用ChatGPT

视频教程及效果演示：https://www.youtube.com/watch?v=YqwcFCRDBtg

## 注意事项
英伟达显卡显存2G以上，支持RTX50系列显卡

使用前先更新英伟达显卡驱动到最新版本

软件运行路径中不要有非英文字符和空格，待处理及使用的文件同样要注意

整合包只支持Windows 10或11电脑。

## 漫画图片翻译软件manga-image-translator整合包下载：
https://pan.quark.cn/s/245c32b60069

https://pan.baidu.com/s/1nzI95pYYzdHOjjlu4CrvDg?pwd=r6rp

## 项目链接
https://github.com/zyddnys/manga-image-translator
