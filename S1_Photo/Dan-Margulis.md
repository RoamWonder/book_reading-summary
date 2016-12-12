
<!-- toc orderedList:1 depthFrom:1 depthTo:6 -->

1. [Professional Photoshop](#professional-photoshop)
1. [Photoshop LAB](#photoshop-lab)
1. [Modern Photoshop Color Workflow](#modern-photoshop-color-workflow)
	1. [Retouch Workflow](#retouch-workflow)
	1. [PPW Workflow](#ppw-workflow)
	1. [PPW Action](#ppw-action)
	1. [ACR and PS](#acr-and-ps)
1. [Reference Standard Color Values](#reference-standard-color-values)

<!-- tocstop -->
# Professional Photoshop

# Photoshop LAB

# Modern Photoshop Color Workflow
## Retouch Workflow
One retouch job can be comprehended as a **"Retouch Workflow"**, and this workflow can be divide into some levels:

1. _**Workflow Node**_:
2. _**Workflow Goal**_: The _**Workflow Goal**_ is an **abstract** level which means you can not
3. _**Workflow Action**_: "Action" here is similar to PS's "Action". Both "Action" here and PS's "Action" is consist of some command, but "Action" here is a abstract conception which means "Action" here is beyond PS's "Action"

## PPW Workflow
PPW's **"Decompositio Philosophy"** is process _**"Luminosity"**_ and _**"Color"**_ **separately** mostly through the time.


1. Color
    1. Color Correction：
        - RGB `Curve Adjustment Layer` in **_"RGB"_** **--->** CH3
    4. Color Range Define
        - Define **"Black Point"** and **"White Point"** in "RGB Color Space" **--->** CH3\&CH4
2. Luminosity
    1. Luminosity Reallocation
        - Luminosity layer by **"Channel Mix"** (`Apply Image` or `Calculation`) **--->** CH4
		- Luminosity `Curve Adjustment Layer`
    3. Contrast Boost
        - Luminosity `Curve Adjustment Layer` **--->** CH4
    5. Extract Detail of Shadow \& Highlight
        - PS `Shadows/Hightlights`
		- PPW `S/H+OK` **--->** CH7
        - PPW `Bigger Hammer` **--->** CH10
    7. Strengthen Specific Things
        - PPW `Darken Sky SC` and `Darken Sky B` **--->** CH8
    8. Extend Luminocity Range
        - `Screen` and `Multiply` **--->** CH12
3. Color Again
    1. ??
        - PPW `H-K` **--->** CH13
    5. Skin Color Retouch
		- PPW `Skin Desaturation` **--->** CH9
    7. Color Boost
        - PPW `CB` **--->** CH5
        - PPW `MMM` **--->** CH6
    10. Define Color **"Black Point"** and **"White Point"**
        - ?? **--->** ALL-CH?
    11. Color ease
        - PS **"Mark"** **--->** ALL-CH?
        - PS **"Opacity"** **--->** ALL-CH?
4. Sharpen
	1. Sharpen
		- PS `USM Sharpen`
		- PS `Smart Sharpen`
		- PPW `sharpen 2015`
		- PPW `Sharpen old`
5. Ending
    1. Versions Blending
        - Layer blending mode **--->** CH2
		- Layer opacity
		- Layer blend if
		- Layer mask
    8. Color Space match
        - Color transfer

## PPW Action
1. CB："Color Boost"
    1. Input：整体色彩均衡（无色偏）
    2. Process：LAB模式下的曲线调整图层**--->**
    2. Output：
2. HK：“Helmholtz-Kohlrausch”
    3. Input：
    4. Process：
    5. Output：1/4色调～中间色调的中性色和近中性色被压暗
6. RGB曲线校色[^not-in-lab]：
    1. Input：有色偏的图像，此图像应具备以下至少一个特征（可参考[Reference Standard Color Values](#reference-standard-color-values)）
        1. 有明显理应为中性灰的物体：如灰墙
        2. 有明显不正确色彩的物体：如红色的天空

[^not-in-lab]: Color correction in "RGB" mode

## ACR and PS


# Reference Standard Color Values
|Name|RGB|CMYK|LAB|HSB|
|--|--|--|--|--|
|Asian Skin Tone|rgb(213,172,129)|cmyk(17%,32%,53%,3%)|--|--|
