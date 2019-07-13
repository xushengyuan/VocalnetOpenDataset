# VocalnetOpenDataset(In progress)
一个开源的中文歌声合成数据集。An open-source Chinese singing synthesizing dataset.

## 协议
本数据集以[Creative Commons Attribution Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)协议共享。
即：
- 你可以使用本数据集进行训练，并将模型以相同方式发布，并且可用于商业用途。
- 你可以将使用由本数据集训练产生的模型所合成的音频以相同的形式发布，并可将音频用于商业用途。
但都必须对本数据集进行署名。
（以协议文本为准）

## 音频

- 32000Hz采样率，16bit，单声道，录音室级音质，已经过噪声门处理。
- 每首歌曲可能由多条音轨组成
- 包括经营在内的时长：
- 去除静音后的时长：

## 内容

本数据集分为主数据集和用于训练nn-vocoder的零散音频两部分。

#### 主数据集
主数据集中包含有 首完整或部分歌曲，共 条轨道。

歌曲名称如下表所示，由于版权问题，故不提供相关歌词，需要自行收集。
曲风整体偏向国风类音乐，但数据集内曲风差异仍可能较大。
部分歌曲含有戏腔唱段，若不需要可以自行去除。

#### 零散数据集
去除静音后总时长为：

已拼合为单个音频文件，需要者可自行切割。
内容可能会有一定的重复，未经过人工处理。

## 预训练的waveglow模型

## 标注
作者时间有限，仅完成了部分的手工对齐和句子划分。
剩余标记及音符音高的标注还在制作中。

现在使用Praat的TextGrid格式提供。
将来会进行完善并提供其他格式

## 正在进行中的工作
作者时间有限，希望能有其他志愿者帮助完成标注工作，欢迎贡献至此repo。

版权所有©2019 xushengyuan,wenren。 保留部分权利
Copyright©2019 xushengyuan,wenren. Some rights reserved

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。
