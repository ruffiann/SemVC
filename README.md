# Semantic-Video-Composition

[![report](https://img.shields.io/badge/arxiv-report-red)](https://arxiv.org/abs/2401.09195)

This repository is a brief introduction and case study of the paper "Training-Free Semantic Video Composition via Pre-trained Diffusion Model" in ICME 2024 **(Oral)**.

## 😁Introduction

The video composition task aims to integrate specified foregrounds and backgrounds from different videos into a harmonious composite. Current approaches, predominantly trained on videos with adjusted foreground color and lighting, struggle to address deep semantic disparities beyond superficial adjustments, such as domain gaps. Therefore, we propose a training-free pipeline employing a pre-trained diffusion model imbued with semantic prior knowledge, which can process composite videos with broader semantic disparities.

## 🤯Method

Using the pretrained Stable Diffusion V2-1 as our backbone, we leverage its robust semantic understanding capabilities to propose an training-free video compositing pipeline.

<div align=center><img src="cases/method.png/" style="width:100%"></div>

## 🔆Comparison

<table>
  <tr>
    <th>input</th>
    <th>TF-ICON</th>
    <th>Ours</th>
  </tr>
  <tr>
    <td><img src="/cases/ori_bear_autumn.gif" alt="ori_bear_autumn.gif" style="width:100%"></td>
    <td><img src="/cases/tficon_bear_autumn.gif" alt="tficon_bear_autumn.gif" style="width:100%"></td>
    <td><img src="/cases/ours_bear_autumn.gif" alt="ours_bear_autumn.gif" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="/cases/ori_blackswan_willow.gif" alt="ori_blackswan_willow.gif" style="width:100%"></td>
    <td><img src="/cases/tficon_blackswan_willow.gif" alt="tficon_blackswan_willow.gif" style="width:100%"></td>
    <td><img src="/cases/ours_blackswan_willow.gif" alt="ours_blackswan_willow.gif" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="/cases/ori_camel_desert.gif" alt="ori_camel_desert.gif" style="width:100%"></td>
    <td><img src="/cases/tficon_camel_desert.gif" alt="tficon_camel_desert.gif" style="width:100%"></td>
    <td><img src="/cases/ours_camel_desert.gif" alt="ours_camel_desert.gif" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="/cases/ori_car_street.gif" alt="ori_car_street.gif" style="width:100%"></td>
    <td><img src="/cases/tficon_car_street.gif" alt="tficon_car_street.gif" style="width:100%"></td>
    <td><img src="/cases/ours_car_street.gif" alt="ours_car_street.gif" style="width:100%"></td>
  </tr>
</table>

## 🎞More Cases
![morecases.png](/cases/morecases.png)
