# <center>LEARNING SINGING FROM SPEECH</center>

<center>Liqiang Zhang, Chengzhu Yu, Heng Lu, Chao Weng, Yusong Wu, Xiang Xie, Zijin Li, Dong Yu</center>
<center>Tencent AI Lab</center>


## Abstract

<div style="text-align: justify"> We propose an algorithm that is capable of synthesizing high quality target speaker's singing voice given only their normal speech samples. The proposed algorithm first integrate speech and singing synthesis into a unified framework, and learns universal speaker embeddings that are shareable between speech and singing synthesis tasks. Specifically, the speaker embeddings learned from normal speech via the speech synthesis objective are shared with those learned from singing samples via the singing synthesis objective in the unified training framework. This makes the learned speaker embedding a transferable representation for both speaking and singing. We evaluate the proposed algorithm on singing voice conversion task where the content of original singing is covered with the timbre of another speaker's voice learned purely from their normal speech samples. Our experiments indicate that the proposed algorithm generates high-quality singing voices that sound highly similar to target speaker’s voice given only his or her normal speech samples. We believe that proposed algorithm will open up new opportunities for singing synthesis and conversion for broader users and applications. </div> 

<br>

![arch](images/DurIAN_v1-7.png)

<br>

## Sound Samples

\* <sup>Note: All samples are in Mandrin Chinese.</sup>

### 1. Singing Conversion  Speech (Sec 5.1)

<br>

Female Synthesis Voice

<table align="center">
  <thead>
    <tr>
      <th> </th>
      <th>Singer</th>
      <th>Male1</th>
      <th>Male2</th>
      <th>Female1</th>
      <th>Female2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Origin voice</th>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
    </tr>
    <tr>
      <th>Song Sample 1</th>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
    </tr>
    <tr>
      <th>Song Sample 2</th>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/test03.npy.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>
