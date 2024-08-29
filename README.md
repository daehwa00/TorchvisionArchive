# TorchvisionArchive

TorchvisionArchive is a repository that helps you to manage and visualize various pretrained models from the Torchvision library. This repository includes scripts to convert CSV files into well-formatted HTML tables with customizable styles.

## Features

- **Model Management**: Easily manage and reference pretrained models from the Torchvision library.


<table>
  <tr>
    <th>Model Name</th>
    <th>Top-1 Accuracy (%)</th>
    <th>Top-5 Accuracy (%)</th>
    <th>Minimum Image Size</th>
    <th>Number of Parameters</th>
    <th>GFLOPs</th>
    <th>Model Size (MB)</th>
    <th>Preprocessing Pipeline</th>
  </tr>
  <tr>
    <td>resnet18</td>
    <td>69.758</td>
    <td>89.078</td>
    <td>(1, 1)</td>
    <td>11689512</td>
    <td>1.814</td>
    <td>44.661</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnet34</td>
    <td>73.314</td>
    <td>91.42</td>
    <td>(1, 1)</td>
    <td>21797672</td>
    <td>3.664</td>
    <td>83.275</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnet50</td>
    <td>80.858</td>
    <td>95.434</td>
    <td>(1, 1)</td>
    <td>25557032</td>
    <td>4.089</td>
    <td>97.79</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnet101</td>
    <td>81.886</td>
    <td>95.78</td>
    <td>(1, 1)</td>
    <td>44549160</td>
    <td>7.801</td>
    <td>170.53</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnet152</td>
    <td>82.284</td>
    <td>96.002</td>
    <td>(1, 1)</td>
    <td>60192808</td>
    <td>11.514</td>
    <td>230.474</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>alexnet</td>
    <td>56.522</td>
    <td>79.066</td>
    <td>(63, 63)</td>
    <td>61100840</td>
    <td>0.714</td>
    <td>233.087</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg11</td>
    <td>69.02</td>
    <td>88.628</td>
    <td>(32, 32)</td>
    <td>132863336</td>
    <td>7.609</td>
    <td>506.84</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg11_bn</td>
    <td>70.37</td>
    <td>89.81</td>
    <td>(32, 32)</td>
    <td>132868840</td>
    <td>7.609</td>
    <td>506.881</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg13</td>
    <td>69.928</td>
    <td>89.246</td>
    <td>(32, 32)</td>
    <td>133047848</td>
    <td>11.308</td>
    <td>507.545</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg13_bn</td>
    <td>71.586</td>
    <td>90.374</td>
    <td>(32, 32)</td>
    <td>133053736</td>
    <td>11.308</td>
    <td>507.59</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg16</td>
    <td>71.592</td>
    <td>90.382</td>
    <td>(32, 32)</td>
    <td>138357544</td>
    <td>15.47</td>
    <td>527.796</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg16_bn</td>
    <td>73.36</td>
    <td>91.516</td>
    <td>(32, 32)</td>
    <td>138365992</td>
    <td>15.47</td>
    <td>527.866</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg19</td>
    <td>72.376</td>
    <td>90.876</td>
    <td>(32, 32)</td>
    <td>143667240</td>
    <td>19.632</td>
    <td>548.051</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vgg19_bn</td>
    <td>74.218</td>
    <td>91.842</td>
    <td>(32, 32)</td>
    <td>143678248</td>
    <td>19.632</td>
    <td>548.143</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>squeezenet1_0</td>
    <td>58.092</td>
    <td>80.42</td>
    <td>(21, 21)</td>
    <td>1248424</td>
    <td>0.819</td>
    <td>4.778</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>squeezenet1_1</td>
    <td>58.178</td>
    <td>80.624</td>
    <td>(17, 17)</td>
    <td>1235496</td>
    <td>0.349</td>
    <td>4.729</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>densenet121</td>
    <td>74.434</td>
    <td>91.972</td>
    <td>(29, 29)</td>
    <td>7978856</td>
    <td>2.834</td>
    <td>30.845</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>densenet161</td>
    <td>77.138</td>
    <td>93.56</td>
    <td>(29, 29)</td>
    <td>28681000</td>
    <td>7.728</td>
    <td>110.369</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>densenet169</td>
    <td>75.6</td>
    <td>92.806</td>
    <td>(29, 29)</td>
    <td>14149480</td>
    <td>3.36</td>
    <td>54.708</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>densenet201</td>
    <td>76.896</td>
    <td>93.37</td>
    <td>(29, 29)</td>
    <td>20013928</td>
    <td>4.291</td>
    <td>77.373</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>inception_v3</td>
    <td>77.294</td>
    <td>93.45</td>
    <td>(75, 75)</td>
    <td>27161264</td>
    <td>5.713</td>
    <td>103.903</td>
    <td><pre>ImageClassification(
    crop_size=[299]
    resize_size=[342]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>googlenet</td>
    <td>69.778</td>
    <td>89.53</td>
    <td>(15, 15)</td>
    <td>6624904</td>
    <td>1.498</td>
    <td>49.731</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>shufflenet_v2_x0_5</td>
    <td>60.552</td>
    <td>81.746</td>
    <td>(1, 1)</td>
    <td>1366792</td>
    <td>0.04</td>
    <td>5.282</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>shufflenet_v2_x1_0</td>
    <td>69.362</td>
    <td>88.316</td>
    <td>(1, 1)</td>
    <td>2278604</td>
    <td>0.145</td>
    <td>8.791</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>shufflenet_v2_x1_5</td>
    <td>72.996</td>
    <td>91.086</td>
    <td>(1, 1)</td>
    <td>3503624</td>
    <td>0.296</td>
    <td>13.557</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>shufflenet_v2_x2_0</td>
    <td>76.23</td>
    <td>93.006</td>
    <td>(1, 1)</td>
    <td>7393996</td>
    <td>0.583</td>
    <td>28.433</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mobilenet_v2</td>
    <td>72.154</td>
    <td>90.822</td>
    <td>(1, 1)</td>
    <td>3504872</td>
    <td>0.301</td>
    <td>13.598</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mobilenet_v3_large</td>
    <td>75.274</td>
    <td>92.566</td>
    <td>(1, 1)</td>
    <td>5483032</td>
    <td>0.217</td>
    <td>21.107</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mobilenet_v3_small</td>
    <td>67.668</td>
    <td>87.402</td>
    <td>(1, 1)</td>
    <td>2542856</td>
    <td>0.057</td>
    <td>9.829</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnext50_32x4d</td>
    <td>81.198</td>
    <td>95.34</td>
    <td>(1, 1)</td>
    <td>25028904</td>
    <td>4.23</td>
    <td>95.833</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnext101_32x8d</td>
    <td>82.834</td>
    <td>96.228</td>
    <td>(1, 1)</td>
    <td>88791336</td>
    <td>16.414</td>
    <td>339.673</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>resnext101_64x4d</td>
    <td>83.246</td>
    <td>96.454</td>
    <td>(1, 1)</td>
    <td>83455272</td>
    <td>15.46</td>
    <td>319.318</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>wide_resnet50_2</td>
    <td>81.602</td>
    <td>95.758</td>
    <td>(1, 1)</td>
    <td>68883240</td>
    <td>11.398</td>
    <td>263.124</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>wide_resnet101_2</td>
    <td>82.51</td>
    <td>96.02</td>
    <td>(1, 1)</td>
    <td>126886696</td>
    <td>22.753</td>
    <td>484.747</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mnasnet0_5</td>
    <td>67.734</td>
    <td>87.49</td>
    <td>(1, 1)</td>
    <td>2218512</td>
    <td>0.104</td>
    <td>8.591</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mnasnet0_75</td>
    <td>71.18</td>
    <td>90.496</td>
    <td>(1, 1)</td>
    <td>3170208</td>
    <td>0.215</td>
    <td>12.303</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mnasnet1_0</td>
    <td>73.456</td>
    <td>91.51</td>
    <td>(1, 1)</td>
    <td>4383312</td>
    <td>0.314</td>
    <td>16.915</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>mnasnet1_3</td>
    <td>76.506</td>
    <td>93.522</td>
    <td>(1, 1)</td>
    <td>6282256</td>
    <td>0.526</td>
    <td>24.246</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b0</td>
    <td>77.692</td>
    <td>93.532</td>
    <td>(1, 1)</td>
    <td>5288548</td>
    <td>0.386</td>
    <td>20.451</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b1</td>
    <td>79.838</td>
    <td>94.934</td>
    <td>(1, 1)</td>
    <td>7794184</td>
    <td>0.687</td>
    <td>30.136</td>
    <td><pre>ImageClassification(
    crop_size=[240]
    resize_size=[255]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b2</td>
    <td>80.608</td>
    <td>95.31</td>
    <td>(1, 1)</td>
    <td>9109994</td>
    <td>1.088</td>
    <td>35.174</td>
    <td><pre>ImageClassification(
    crop_size=[288]
    resize_size=[288]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b3</td>
    <td>82.008</td>
    <td>96.054</td>
    <td>(1, 1)</td>
    <td>12233232</td>
    <td>1.827</td>
    <td>47.184</td>
    <td><pre>ImageClassification(
    crop_size=[300]
    resize_size=[320]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b4</td>
    <td>83.384</td>
    <td>96.594</td>
    <td>(1, 1)</td>
    <td>19341616</td>
    <td>4.394</td>
    <td>74.489</td>
    <td><pre>ImageClassification(
    crop_size=[380]
    resize_size=[384]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b5</td>
    <td>83.444</td>
    <td>96.628</td>
    <td>(1, 1)</td>
    <td>30389784</td>
    <td>10.266</td>
    <td>116.864</td>
    <td><pre>ImageClassification(
    crop_size=[456]
    resize_size=[456]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b6</td>
    <td>84.008</td>
    <td>96.916</td>
    <td>(1, 1)</td>
    <td>43040704</td>
    <td>19.068</td>
    <td>165.362</td>
    <td><pre>ImageClassification(
    crop_size=[528]
    resize_size=[528]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_b7</td>
    <td>84.122</td>
    <td>96.908</td>
    <td>(1, 1)</td>
    <td>66347960</td>
    <td>37.746</td>
    <td>254.675</td>
    <td><pre>ImageClassification(
    crop_size=[600]
    resize_size=[600]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_v2_s</td>
    <td>84.228</td>
    <td>96.878</td>
    <td>(33, 33)</td>
    <td>21458488</td>
    <td>8.366</td>
    <td>82.704</td>
    <td><pre>ImageClassification(
    crop_size=[384]
    resize_size=[384]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_v2_m</td>
    <td>85.112</td>
    <td>97.156</td>
    <td>(33, 33)</td>
    <td>54139356</td>
    <td>24.582</td>
    <td>208.01</td>
    <td><pre>ImageClassification(
    crop_size=[480]
    resize_size=[480]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>efficientnet_v2_l</td>
    <td>85.808</td>
    <td>97.788</td>
    <td>(33, 33)</td>
    <td>118515272</td>
    <td>56.08</td>
    <td>454.573</td>
    <td><pre>ImageClassification(
    crop_size=[480]
    resize_size=[480]
    mean=[0.5, 0.5, 0.5]
    std=[0.5, 0.5, 0.5]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_400mf</td>
    <td>75.804</td>
    <td>92.742</td>
    <td>(1, 1)</td>
    <td>4344144</td>
    <td>0.402</td>
    <td>16.806</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_800mf</td>
    <td>78.828</td>
    <td>94.502</td>
    <td>(1, 1)</td>
    <td>6432512</td>
    <td>0.834</td>
    <td>24.774</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_1_6gf</td>
    <td>80.876</td>
    <td>95.444</td>
    <td>(1, 1)</td>
    <td>11202430</td>
    <td>1.612</td>
    <td>43.152</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_3_2gf</td>
    <td>81.982</td>
    <td>95.972</td>
    <td>(1, 1)</td>
    <td>19436338</td>
    <td>3.176</td>
    <td>74.567</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_8gf</td>
    <td>82.828</td>
    <td>96.33</td>
    <td>(1, 1)</td>
    <td>39381472</td>
    <td>8.473</td>
    <td>150.701</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_16gf</td>
    <td>82.886</td>
    <td>96.328</td>
    <td>(1, 1)</td>
    <td>83590140</td>
    <td>15.912</td>
    <td>319.49</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_32gf</td>
    <td>83.368</td>
    <td>96.498</td>
    <td>(1, 1)</td>
    <td>145046770</td>
    <td>32.28</td>
    <td>554.076</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_400mf</td>
    <td>74.864</td>
    <td>92.322</td>
    <td>(1, 1)</td>
    <td>5495976</td>
    <td>0.414</td>
    <td>21.257</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_800mf</td>
    <td>77.522</td>
    <td>93.826</td>
    <td>(1, 1)</td>
    <td>7259656</td>
    <td>0.8</td>
    <td>27.945</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_1_6gf</td>
    <td>79.668</td>
    <td>94.922</td>
    <td>(1, 1)</td>
    <td>9190136</td>
    <td>1.603</td>
    <td>35.339</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_3_2gf</td>
    <td>81.196</td>
    <td>95.43</td>
    <td>(1, 1)</td>
    <td>15296552</td>
    <td>3.177</td>
    <td>58.756</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_8gf</td>
    <td>81.682</td>
    <td>95.678</td>
    <td>(1, 1)</td>
    <td>39572648</td>
    <td>7.995</td>
    <td>151.456</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_16gf</td>
    <td>82.716</td>
    <td>96.196</td>
    <td>(1, 1)</td>
    <td>54278536</td>
    <td>15.941</td>
    <td>207.627</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_x_32gf</td>
    <td>83.014</td>
    <td>96.288</td>
    <td>(1, 1)</td>
    <td>107811560</td>
    <td>31.736</td>
    <td>412.039</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>regnet_y_128gf</td>
    <td>88.228</td>
    <td>98.682</td>
    <td>(1, 1)</td>
    <td>644812894</td>
    <td>374.57</td>
    <td>2461.564</td>
    <td><pre>ImageClassification(
    crop_size=[384]
    resize_size=[384]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>vit_b_16</td>
    <td>81.072</td>
    <td>95.318</td>
    <td>(224, 224)</td>
    <td>86567656</td>
    <td>17.564</td>
    <td>330.285</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vit_b_32</td>
    <td>75.912</td>
    <td>92.466</td>
    <td>(224, 224)</td>
    <td>88224232</td>
    <td>4.409</td>
    <td>336.604</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vit_l_16</td>
    <td>79.662</td>
    <td>94.638</td>
    <td>(224, 224)</td>
    <td>304326632</td>
    <td>61.555</td>
    <td>1161.023</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[242]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vit_l_32</td>
    <td>76.972</td>
    <td>93.07</td>
    <td>(224, 224)</td>
    <td>306535400</td>
    <td>15.378</td>
    <td>1169.449</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[256]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>vit_h_14</td>
    <td>88.552</td>
    <td>98.694</td>
    <td>(518, 518)</td>
    <td>633470440</td>
    <td>1016.717</td>
    <td>2416.643</td>
    <td><pre>ImageClassification(
    crop_size=[518]
    resize_size=[518]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>convnext_tiny</td>
    <td>82.52</td>
    <td>96.146</td>
    <td>(32, 32)</td>
    <td>28589128</td>
    <td>4.456</td>
    <td>109.119</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[236]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>convnext_small</td>
    <td>83.616</td>
    <td>96.65</td>
    <td>(32, 32)</td>
    <td>50223688</td>
    <td>8.684</td>
    <td>191.703</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[230]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>convnext_base</td>
    <td>84.062</td>
    <td>96.87</td>
    <td>(32, 32)</td>
    <td>88591464</td>
    <td>15.355</td>
    <td>338.064</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>convnext_large</td>
    <td>84.414</td>
    <td>96.976</td>
    <td>(32, 32)</td>
    <td>197767336</td>
    <td>34.361</td>
    <td>754.537</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BILINEAR
)</pre></td>
  </tr>
  <tr>
    <td>swin_t</td>
    <td>81.474</td>
    <td>95.776</td>
    <td>(224, 224)</td>
    <td>28288354</td>
    <td>4.491</td>
    <td>108.19</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[232]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>swin_s</td>
    <td>83.196</td>
    <td>96.36</td>
    <td>(224, 224)</td>
    <td>49606258</td>
    <td>8.741</td>
    <td>189.786</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[246]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>swin_b</td>
    <td>83.582</td>
    <td>96.64</td>
    <td>(224, 224)</td>
    <td>87768224</td>
    <td>15.431</td>
    <td>335.364</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[238]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>swin_v2_t</td>
    <td>82.072</td>
    <td>96.132</td>
    <td>(256, 256)</td>
    <td>28351570</td>
    <td>5.94</td>
    <td>108.626</td>
    <td><pre>ImageClassification(
    crop_size=[256]
    resize_size=[260]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>swin_v2_s</td>
    <td>83.712</td>
    <td>96.816</td>
    <td>(256, 256)</td>
    <td>49737442</td>
    <td>11.546</td>
    <td>190.675</td>
    <td><pre>ImageClassification(
    crop_size=[256]
    resize_size=[260]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>swin_v2_b</td>
    <td>84.112</td>
    <td>96.864</td>
    <td>(256, 256)</td>
    <td>87930848</td>
    <td>20.325</td>
    <td>336.372</td>
    <td><pre>ImageClassification(
    crop_size=[256]
    resize_size=[272]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
  <tr>
    <td>maxvit_t</td>
    <td>83.7</td>
    <td>96.722</td>
    <td>(224, 224)</td>
    <td>30919624</td>
    <td>5.558</td>
    <td>118.769</td>
    <td><pre>ImageClassification(
    crop_size=[224]
    resize_size=[224]
    mean=[0.485, 0.456, 0.406]
    std=[0.229, 0.224, 0.225]
    interpolation=InterpolationMode.BICUBIC
)</pre></td>
  </tr>
</table>
