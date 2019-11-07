# <center>DurIAN : Duration Informed Attention Network For Multimodal Synthesis</center>

<center>Chengzhu Yu, Heng Lu, Na Hu, Meng Yu, Chao Weng, Kun Xu, Peng Liu, <br>Shiyin Kang, Deyi Tuo, Guangzhi Lei, Dan Su, Dong Yu</center><br>
<center>Tencent AI Lab</center>

<br>

Paper link: *[https://arxiv.org/abs/1909.01700](https://arxiv.org/abs/1909.01700)*

<br>

## Abstract

<div style="text-align: justify"> We present a generic and robust multimodal synthesis system that produces highly natural speech and facial expression simultaneously. The key component of this system is the Duration Informed Attention Network (DurIAN), an autoregressive model in which the alignments between the input text and the output acoustic features are inferred from a duration model. This is different from the end-to-end attention mechanism used, and accounts for various unavoidable artifacts, in existing end-to-end speech synthesis systems such as Tacotron. Furthermore, DurIAN can be used to generate high quality facial expression which can be synchronized with generated speech with/without parallel speech and face data. To improve the efficiency of speech generation, we also propose a multi-band parallel generation strategy on top of the WaveRNN model. The proposed Multi-band WaveRNN effectively reduces the total computational complexity from 9.8 to 3.6 GFLOPS, and is able to generate audio that is 6 times faster than real time on a single CPU core. We show that DurIAN could generate highly natural speech that is on par with current state of the art end-to-end systems, while at the same time avoid word skipping/repeating errors in those systems. Finally, a simple yet effective approach for fine-grained control of expressiveness of speech and facial expression is introduced. </div> 

<br>

![arch](images/DurIAN_v1-7.png)

<br>

## Sound/Video Samples

\* <sup>Note: All samples are in Mandrin Chinese.</sup>

### 1. Speech Synthesis Speech (Sec 5.1)

<br>

Female Synthesis Voice

<table align="center">
  <thead>
    <tr>
      <th>DurIAN</th>
      <th>Tacotron-2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test04.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test04.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test05.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test05.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test06.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test06.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test07.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test07.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test10.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test10.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test11.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test11.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test12.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test12.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/test13.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test13.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>

Male Synthesis Voice

<table>
  <thead>
    <tr>
      <th>DurIAN</th>
      <th>Tacotron-2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_1.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/1.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/2.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_3.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/3.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_4.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/4.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_5.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/5.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_6.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/6.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_7.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/7.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_8.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/8.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_9.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/9.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_10.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/10.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>

### 2. Fine-grained Style Control (Sec 5.3)

<br>

*"现在狂铁这经济已经冠决全场啊！"*

\* <sup>Note: Generated with Griffin-lim vocoder.</sup>

<table>
  <tbody>
    <tr>
      <td>exciting x 0.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx0.0.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 1.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx1.0.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 3.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx3.0.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 5.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx5.0.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>

*"一血九九四送出去了！"*

\* <sup>Note: Generated with WaveRNN vocoder.</sup>

<table>
  <tbody>
    <tr>
      <td>exciting x 0.5</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale0.5.mel.npy.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 1.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale1.0.mel.npy.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 1.5</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale1.5.mel.npy.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 2.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale2.0.mel.npy.wav"></audio></td>
    </tr>
  </tbody>
</table>


<br>

*Left: Changing exciting levels during live Game Commentary generation*

*Right: 2006 Word Cup Jiangxiang Huang (黄健翔）commentary generation (exciting!!!)* 

<center>
<table align="center" style="width:1000px;">
  <tbody>
    <tr>
      <td colspan="2" ><img src="images/style_control.png" alt="sc" width="1000" height="400"></td>
    </tr>
  </tbody>
  <tbody>
    <tr align="center">
      <td><audio controls="" preload="auto">
            <source src="wavs/Media211.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/Media212.wav"></audio></td>
    </tr>
  </tbody>
</table>
</center>

<br>

### 3. Live Game Commentary (DurIAN + WaveRNN)

<br>

Male and Female

<iframe width="1000" height="500" src="https://www.youtube.com/embed/ohY8Lft6gD0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

---

<br>

Female

<iframe width="1000" height="500" src="https://www.youtube.com/embed/30iXxgvvlkg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

### 4. 3D Avatar Female Host

<iframe width="1000" height="500" src="https://www.youtube.com/embed/AnazWGADtnk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

### 5. Emotional Control for talking head

<br>

**Neutral**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/JtjV37OelXM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Joyful**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/UE0g34Pdxlw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Angry**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/N7X6mj-8rtU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Sad**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/pdYeiMitbkk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Live commentary**  （DurIAN + WaveRNN）

<iframe width="500" height="200" src="https://www.youtube.com/embed/PptNj5xBzHA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Passionate Live commentary**  （DurIAN + WaveRNN）

<iframe width="500" height="200" src="https://www.youtube.com/embed/flNL8kIY-TM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

