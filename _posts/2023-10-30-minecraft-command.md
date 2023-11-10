---
layout: post
title: 我的世界指令
subtitle: 收集了kk键盘的我的世界指令
banner:
  loop: true
  volume: 0.25
  start_at: 8.5
  image: assets/images/minecraft.jpg
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: white"
categories: minecraft
tags: [minecraft]
---

<div align="center">
<img wight="230px" height="230px" src="../assets/images/block.jpg">

![forthebadge](https://forthebadge.com/images/badges/license-mit.svg)
</div>

# 我的世界指令语弹
我的世界指令，收录kk键盘的语弹，欢迎推送
> - 最近更新：`2023/10/28`
> - [x] 不需要下载`kk键盘`
> - [x] 直接点击`复制`按钮，你就能获取`语弹`
> - [x] `免费`无`广告`，妈妈再也不用担心太多广告了

## 目录
* [补充](#补充)
    * 有github账号
    * 没有github账号
* [使用方法](#使用方法)
* [许可证](#许可证)
* [star历史](#star历史)
* [语弹](#语弹)
    * [方块获取](#基础获取物品指令)
    * [药水buff](#药水buff效果)
    * [title文字](#title文字)
    * [表情符号](#表情符号)

## 补充
- 如果你有`github`账号你就可以`fork`到你的仓库，然后更改，最后提交分支到我的`master`
- 如果你没有`github`账号，联系我的邮箱：`huangshaoqi8888@gmail.com`,或者去西瓜视频私信补充
  
## 使用方法
- 点击指令栏右边的复制按钮复制即可（但是有些语弹要更改一些东西，请看每个语弹下方的介绍栏）

![alt](https://github.com/Github-Huangshaoqi/minecraft-code/blob/main/copy.png)

## 许可证
[MIT](https://github.com/Github-Huangshaoqi/minecraft-code/blob/master/LICENSE)

Copyright (c) 2023 Github-Huangshaoqi

## star历史
![Star History Chart](https://api.star-history.com/svg?repos=Github-Huangshaoqi/minecraft-code&type=Date)


## 语弹
> 暂时收录这么多
### 基础获取物品指令
> #### 给予自己命令方块
```python
/give @s command_block
```
> #### 给予自己结构方块
```python
/give @s stucture_block
```
> #### 给予自己屏障
```python
/give @s barrier
```
> #### 给予自己光明方块
```python
/give @s light_block
```
> #### 给予自己允许方块
```python
/give @s allow
```
> #### 给予自己拒绝方块
```python
/give @s deny
```
> #### 给予自己NPC弹
```python
/give @s spawn_egg
```
### 药水buff效果
- 如果不想要无限时间，把99999改为你要的时间(单位：秒)
> #### 夜视 (无线持续时间)
```python
/effect @s night_vision 99999
```
> #### 急迫 (无线持续时间)
```python
/effect @s haste 99999
```
> #### 力量 1 (无线持续时间)
```python
/effect @s strength 99999 10
```
> #### 力量 2 (无线持续时间)
```python
/effect @s strength 99999 20
```
> #### 力量 3 (无线持续时间)
```python
/effect @s strength 99999 100
```
> #### 速度 1 (无线持续时间)
```python
/effect @s speed 99999 10
```
> #### 速度 2 (无线持续时间)
```python
/effect @s speed 99999 5
```
> #### 瞬间治疗 (无线持续时间)
```python
/effect @s instanthealth 99999 255
```
> #### 跳跃提升 1 (无线持续时间)
```python
/effect @s jump bot 99999 3
```
> #### 跳跃提升 2 (无线持续时间)
```python
/effect @s jump bot 99999 5
```
> #### 跳跃提升 3 (无线持续时间)
```python
/effect @s jump bot 99999 10
```
> #### 跳跃提升 4 (无线持续时间)
```python
/effect @s jump bot 99999 30
```
### title文字
- 将`内容`替换为你想要的文字
- 再将`@a/@p/@r/@s`选择一个，删掉其他的和斜杠（其中@a指所有玩家，@p指最近的玩家，@r指随机玩家，@s指发送这条命令的人自己）
> #### 显示在屏幕正中间 字大 
```python
title @a/@p/@r/@s title 内容 
```
> #### 显示在屏幕中下方 字中 
```python
title @a/@p/@r/@s subtitle 内容 
```
> #### 显示在物品栏上方 字小
```python
title @a/@p/@r/@s actionbar 内容
```
### 表情符号
#### 硬币
> 由于markdown语法中有自己的emoji，不支持其他的emoji

<!--<script src="https://giscus.app/client.js"
        data-repo="Github-Huangshaoqi/Github-Huangshaoqi.github.io"
        data-repo-id="R_kgDOKmhZkg"
        data-category="Announcements"
        data-category-id="DIC_kwDOKmhZks4Caohl"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>-->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css"> 
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>  
