---
layout: post
Title: "multi-lingual"
date: 2019-07-15 15:40:40 -0400
categories: xinapse TTS
---
character embedding + attention 수정 !!

<h3>본 샘플들은 연구용입니다.</h3>
<hr>
<h3 align="left">1. Original language</h3>
  1-1. Eng<br>
   <I><span style="color:#92B3B7">Text: We present a multispeaker, multilingual text-to-speech synthesis model based on Tacotron.</span></I>
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
    <td align="center">Cross </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/LJ_Baseline_Eng.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/LJ_New_Eng.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/LJ_Cross_Eng.wav" controls=""></audio></td>
  </tr>
</table>
  1-2. Kor<br>
  <I><span style="color:#92B3B7">Text: 제가 이번에 국내 최고 수준의 인공지능 스타트업 자이냅스를 방문했는데요?</span></I>
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
     <td align="center">Cross </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/KSS_Baseline_Kor.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/KSS_New_Kor.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/KSS_Cross_Kor.wav" controls=""></audio></td>
  </tr>
</table>
<h3 align="left">2. Transfer language</h3>
  2-1. Eng to Kor<br>
    <I><span style="color:#92B3B7">Text: 제가 이번에 국내 최고 수준의 인공지능 스타트업 자이냅스를 방문했는데요?</span></I>
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
    <td align="center">Cross </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/LJ_Baseline_Kor.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/LJ_New_Kor2.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/LJ_Cross_Kor.wav" controls=""></audio></td>
  </tr>
</table>

  2-2. Kor to Eng<br>
    <I><span style="color:#92B3B7">Text: We present a multispeaker, multilingual text-to-speech synthesis model based on Tacotron.</span></I><br>
  KSS datasets
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
     <td align="center">Cross </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/KSS_Baseline_Eng.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/KSS_New_Eng2.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/KSS_Cross_Eng.wav" controls=""></audio></td>
  </tr>
</table>
  박원순 시장님 + Vocoder
<table>
  <tr>      
    <td align="center">Baseline </td>
    <td align="center">Advanced </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/PARK_Baseline_Eng2.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/PARK_New_Eng.wav" controls=""></audio></td>
  </tr>
</table>
  버그 발생!!
<table>
  <tr>      
    <td align="center">Bug</td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/Bug issue.wav" controls=""></audio></td>
  </tr>
</table>

  네오사피엔스 샘플 
<table>
  <tr>      
    <td align="center">Neo</td>
    <td align="center">xinapse </td>
  </tr>
  <tr>
    <td align="center"><audio src="/audio_samples/Neo_trump.wav" controls=""></audio></td>
    <td align="center"><audio src="/audio_samples/xinapse_LJ.wav" controls=""></audio></td>
  </tr>
</table>
