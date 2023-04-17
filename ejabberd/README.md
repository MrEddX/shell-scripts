# CAPTCHA Six Digit Random Pale Color Generator

This is a modified version of the [original](https://github.com/processone/ejabberd/blob/master/tools/captcha.sh) script.
It takes the text to recognize in the captcha image as a parameter and returns the image binary as a result.

The difference is that the six digit code is generated in random color, but only in the pale color range.

ejabberd supports PNG, JPEG and GIF.

The whole idea of the captcha script is to let server admins adapt it to their own needs. The goal is to be able to make the captcha generation as unique as possible, to make the captcha challenge difficult to bypass by a bot.
Server admins are thus supposed to write and use their own captcha generators.

> This script relies on ImageMagick.
> It is NOT compliant with ImageMagick forks like GraphicsMagick.
