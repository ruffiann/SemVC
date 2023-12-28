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
    <td><img src="/cases/ori_bear_autumn.gif" alt="First GIF" style="width:100%"></td>
    <td><img src="/cases/tficon_bear_autumn.gif" alt="Second GIF" style="width:100%"></td>
    <td><img src="/cases/ours_bear_autumn.gif" alt="Third GIF" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="/cases/ori_blackswan_willow.gif" alt="First GIF" style="width:100%"></td>
    <td><img src="/cases/tficon_blackswan_willow.gif" alt="Second GIF" style="width:100%"></td>
    <td><img src="/cases/ours_blackswan_willow.gif" alt="Third GIF" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="/cases/ori_camel_desert.gif" alt="First GIF" style="width:100%"></td>
    <td><img src="/cases/tficon_camel_desert.gif" alt="Second GIF" style="width:100%"></td>
    <td><img src="/cases/ours_camel_desert.gif" alt="Third GIF" style="width:100%"></td>
  </tr>
  <tr>
    <td><img src="/cases/ori_car_street.gif" alt="First GIF" style="width:100%"></td>
    <td><img src="/cases/tficon_car_street.gif" alt="Second GIF" style="width:100%"></td>
    <td><img src="/cases/ours_car_street.gif" alt="Third GIF" style="width:100%"></td>
  </tr>
</table>
