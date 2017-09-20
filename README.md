# Karabiner-Plus-Karabiner-Element
My settings for karabiner and Karabiner-Element

The purpose is to reduce hand movement, and easier to use than VI mode, (at least for me)

These are my settings on Mac, and the function are following:

个人用Karabiner & Karabiner-Element 设定, 减少右手移动

# Modification
## Variant Diamond cursor:
## 菱形指针改建
Command + i -> arrow_up

Command + k -> arrow_left

Command + l -> arrow_right

Command + m -> arrow_down

## Extra Cursor:
## 额外指针移动
Command + j -> Command + arrow_left  (hol, not equals to `home`)

Command + ; -> Command + arrow_right (eol, not equals to `end`)

Command + [ -> Page_up

Command + ] -> Page_down

## Delete Backspace
## 删除相关

Command + d -> delete_forward

Command + ' -> delete_or_backspace

## One click to Chinese Input:
## 一键切至搜狗输入法
right_option (stand alone) -> to Sougou Input


# Usage

For "Karabiner", use `private.xml` file

For "Karabiner-Element", use `KE-complex-modifications-master\docs\json\chinese.json` file and

`KE-complex-modifications-master\docs\json\sixleaveakkm_move.json` file

Or simple open `KE-complex-modifications-master\docs\index.html` and choose upper two file, and click `import` on the right side.

# 备注
Karabiner-Element版切换至搜狗输入法的方式与Karabiner版不同， Karabiner版设置了虚拟按键，

Karabiner-Element版好像虚拟按键这个功能没了，只能使用另一种方法：

在我这搜狗输入法默认是输入法中的第三位，日文输入法是第一位，英文是第二位，于是采用了先切换至英文输入法，再切到下一个输入法的方法

`lang3`这个字节被设成不能为目标的原因，只有两个输入法时可采用直接 `lang2` `lang1` 的方法。

