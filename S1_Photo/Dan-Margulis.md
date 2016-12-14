
<!-- toc orderedList:1 depthFrom:1 depthTo:6 -->

1. [About the Author](#about-the-author)
1. [Professional Photoshop: The Classic Guide to Color Correction (5th Edition)](#professional-photoshop-the-classic-guide-to-color-correction-5th-edition)
	1. [Basic Information](#basic-information)
	1. [Review by RoamWonder](#review-by-roamwonder)
1. [Photoshop LAB Color: The Canyon Conundrum and Other Adventures in the Most Powerful Colorspace （Revised Edition）](#photoshop-lab-color-the-canyon-conundrum-and-other-adventures-in-the-most-powerful-colorspace-revised-edition)
	1. [Basic Information](#basic-information-1)
	1. [Review by RoamWonder](#review-by-roamwonder-1)
1. [Modern Photoshop Color Workflow: The Quartertone Quandary, the PPW, and Other Ideas for Speedy Image Enhancement](#modern-photoshop-color-workflow-the-quartertone-quandary-the-ppw-and-other-ideas-for-speedy-image-enhancement)
	1. [Basic Information](#basic-information-2)
	1. [Review by RoamWonder](#review-by-roamwonder-2)
	1. [Generally Retouch Workflow](#generally-retouch-workflow)
	1. [PPW Workflow](#ppw-workflow)
	1. [PPW Action](#ppw-action)
	1. [ACR and PS](#acr-and-ps)
1. [Reference Standard Color Values](#reference-standard-color-values)

<!-- tocstop -->

# About the Author

# Professional Photoshop: The Classic Guide to Color Correction (5th Edition)
## Basic Information
><https://books.google.com/books/about/Professional_Photoshop.html?id=r8BFmKYZlIQC>

**Publish**:
+ English: Peachpit Press, Nov 20, 2006
+ Chinese:


## Review by RoamWonder
**Recommendation**: ⭐⭐⭐⭐⭐

# Photoshop LAB Color: The Canyon Conundrum and Other Adventures in the Most Powerful Colorspace （Revised Edition）
## Basic Information
><https://books.google.com/books?id=54RRAAAAMAAJ&q=Photoshop+LAB+Color&dq=Photoshop+LAB+Color&hl=en&sa=X&ved=0ahUKEwihlqjqovHQAhXJjVQKHcUkC0sQ6AEIKjAA>

**Publish**
+ English: Peachpit Press, 2006
+ Chinese:


## Review by RoamWonder
**Recommendation**: ⭐⭐⭐⭐⭐


# Modern Photoshop Color Workflow: The Quartertone Quandary, the PPW, and Other Ideas for Speedy Image Enhancement

## Basic Information
><https://books.google.com/books?id=LTLRlgEACAAJ&dq=Modern+Photoshop+Color+Workflow&hl=en&sa=X&ved=0ahUKEwj0yo2Mo_HQAhWphVQKHWaWCAkQ6AEIHDAA>

**Publish**
+ English: Feb 24, 2013
+ Chinese:

## Review by RoamWonder
**Recommendation**: ⭐⭐⭐⭐⭐🌟


## Generally Retouch Workflow
One retouch job can be comprehended as a **"Retouch Workflow"**, and this workflow can be divide into some levels:

1. _**Workflow Node**_:
2. _**Workflow Goal**_: The _**Workflow Goal**_ is an **abstract** level which means you can not
3. _**Workflow Action**_: "Action" here is similar to PS's "Action". Both "Action" here and PS's "Action" is consist of some command, but "Action" here is a abstract conception which means "Action" here is beyond PS's "Action"

## PPW Workflow
PPW's **"Decompositio Philosophy"** is process _**"Luminosity"**_ and _**"Color"**_ **separately** mostly through the time.


1. Color
    1. Color Correction：
        - RGB `Curve Adjustment Layer` in _`RGB`_ mode **--->** CH3
    4. Color Range Define
        - Define **"Black Point"** and **"White Point"** in _`RGB`_ mode **--->** CH3\&CH4
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
        - PS **_"Mark"_** **--->** ALL-CH?
        - PS **_"Opacity"_** **--->** ALL-CH?
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
    1. Input：Color balance and non color shift globally
    2. Process：`Curve Adjustment Layer` in _`LAB`_ mode
    2. Output：
2. HK：“Helmholtz-Kohlrausch”
    3. Input：
    4. Process：
    5. Output：Darken **"Neutral"** or **"Near Neutral"** Color between 1/4 and middle color tone.
6. RGB曲线校色[^not-in-lab]：
    1. Input：Image with color shift which at least has one characters list below: ( The right color value can see the [Reference Standard Color Values](#reference-standard-color-values) )
        1. Neutral color in nature. example: gray wall.
        2. Impossible or ugly color in nature. example: sky with red color

[^not-in-lab]: Color correction in "RGB" mode

## ACR and PS


# Reference Standard Color Values
|Name|RGB|CMYK|LAB|HSB|
|--|--|--|--|--|
|Asian Skin Tone|rgb(213,172,129)|cmyk(17%,32%,53%,3%)|--|--|
