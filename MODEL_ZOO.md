# PySOT Model Zoo

## Introduction

This file documents a large collection of baselines trained with pysot. All configurations for these baselines are located in the `experiments` directory. The tables below provide results about inference. Links to the trained models as well as their output are provided. 

## Visual Tracking Baselines

### Short-term Tracking

| <sub>Model</br>（arch+backbone+xcorr）</sub> | <sub>VOT2016</br> (EAO/A/R) </sub> | <sub>VOT2018</br> (EAO/A/R) </sub> | <sub>OTB2015</br> (AUC/Prec.) </sub> | <sub>VOT2018-LT</br>(F1)</sub> | <sub>Speed</br> (fps) </sub> | <sub>Download</sub> |
|:----------------------------------------:|:-:|:------------------------:|:--------------------:|:----------------:|:--------------:|:------------:|
|      <sub>siamrpn_alex_dwxcorr</sub>     | <sub>0.393/0.618/0.238</sub> | <sub>0.352/0.576/0.290</sub> |             -        |         -        | <sub>180</sub> | [link](https://drive.google.com/open?id=1t62x56Jl7baUzPTo0QrC4jJnwvPZm-2m) |
|    <sub>siamrpn_alex_dwxcorr_otb</sub>   |              -               |             -                | <sub>0.666/0.876</sub> |         -        | <sub>180</sub> | [link](https://drive.google.com/open?id=1gCpmR85Qno3C-naR3SLqRNpVfU7VJ2W0) |
|    <sub>siamrpn_r50_l234_dwxcorr</sub>   | <sub>0.464/0.642/0.196</sub> | <sub>0.415/0.601/0.234</sub> |             -        |         -        | <sub>35</sub>  | [link](https://drive.google.com/open?id=1Q4-1563iPwV6wSf_lBHDj5CPFiGSlEPG) |
|  <sub>siamrpn_r50_l234_dwxcorr_otb</sub> |              -               |             -                | <sub>0.696/0.914</sub> |         -        | <sub>35</sub>  | [link](https://drive.google.com/open?id=1Cx_oHu6o0gNeH7F9zZrgevfAGdyWC4D5) |
| <sub>siamrpn_mobilev2_l234_dwxcorr</sub> | <sub>0.455/0.624/0.214</sub> | <sub>0.410/0.586/0.229</sub> |             -        |         -        | <sub>75</sub>  | [link](https://drive.google.com/open?id=1JB94pZTvB1ZByU-qSJn4ZAIfjLWE5EBJ) |
|        <sub>siammask_r50_l3</sub>        | <sub>0.455/0.634/0.219</sub> | <sub>0.423/0.615/0.248</sub> |             -        |         -        | <sub>56</sub>  | [link](https://drive.google.com/open?id=1YbPUQVTYw_slAvk_DchvRY-7B6rnSXP9) |
|  <sub>siamrpn_r50_l234_dwxcorr_lt</sub>  |              -               |             -                |             -        | <sub>0.629</sub> | <sub>20</sub>  | [link](https://drive.google.com/open?id=1lOOTedwGLbGZ7MAbqJimIcET3ANJd29A) |

Note:

- speed tested on GTX-1080Ti


### Video Object Segmentation Baselines


## License

All models available for download through this document are licensed under the [Creative Commons Attribution-ShareAlike 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
