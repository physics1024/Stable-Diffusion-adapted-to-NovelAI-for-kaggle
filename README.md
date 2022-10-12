# Stable-Diffusion-adapted-to-NovelAI-for-kaggle
Use Stable Diffusion to run NovelAI anime model in kaggle
## English
The original project use Google's Colab to run the program, but as we all know, the Google's Colab is not steady. You may get interrupted while running the code.
Kaggle is a platform free to use and some performances are better than Colab, but it has some limits. So I adapted the old project to the Kaggle and fixed some issues. Have fun!
Thanks for the original author JingShing. He uses a BSD3 licence, so I attached it in the end.
## 中文
原来的项目使用谷歌的Colab，但是Colab不稳定，尤其是免费版。。。动不动就掉线。所以我用了kaggle，人家不仅免费而且稳定（P100比T4也许是好些？）。问题是kaggle的硬盘比较离谱，所以我改了几个路径。而且curl实在是太容易断了。。。我把最容易断的那个换成了aria2。为啥不全用aria2？因为硬盘写入只有20G，aria2不支持通道传递。。。反正最后就是祝大家玩的开心！
感谢原作者JingShing。原项目BSD3协议附在下文。

## LICENCE
BSD 3-Clause License

Copyright (c) 2022, JingShing
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
