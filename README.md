# Semantic-Video-Composition
Training-Free Semantic Video Composition via Pre-trained Diffusion Model

## 😁Introduction

The video composition task aims to integrate specified foregrounds and backgrounds from different videos into a harmonious composite. Current approaches, predominantly trained on videos with adjusted foreground color and lighting, struggle to address deep semantic disparities beyond superficial adjustments, such as domain gaps. Therefore, we propose a training-free pipeline employing a pre-trained diffusion model imbued with semantic prior knowledge, which can process composite videos with broader semantic disparities.

## 🎞🎞More cases

<table>
  <tr>
    <th>input</th>
    <th>TF-ICON</th>
    <th>Ours</th>
  </tr>
  <tr>
    <td><img src="ori_bear_autumn.gif" alt="First GIF" style="width:100%"></td>
    <td><img src="tficon_bear_autumn.gif" alt="Second GIF" style="width:100%"></td>
    <td><img src="ours_bear_autumn.gif" alt="Third GIF" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="ori_bear_autumn.gif" alt="First GIF" style="width:100%"></td>
    <td><img src="tficon_bear_autumn.gif" alt="Second GIF" style="width:100%"></td>
    <td><img src="ours_bear_autumn.gif" alt="Third GIF" style="width:100%"></td>
  </tr>
</table>
