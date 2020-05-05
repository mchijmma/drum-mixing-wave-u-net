[Audio examples](https://mchijmma.github.io/drum-mixing-wave-u-net/) for the [paper](https://link.to.paper):

[Martínez Ramírez M. A.](http://m-marco.com), [Stoller, D.](https://dans.world/) and [Moffat, D.](http://davemoffat.com/wp/), “A Deep Learning Approach to Intelligent Drum Mixing with the Wave-U-Net” submitted to the Journal of the Audio Engineering Society, May 2020.

[View the source code.](https://github.com/f90/Mix-Wave-U-Net/)


### plate
<div id="contentBox" style="margin:0px auto; width:250%">
<div id="column1" style="float:left; margin:0; width:22%;">
- input <br />
<audio controls="controls">
    <source src="audio/plate/Plate_30_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_18_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_27_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_28_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
</div>

<div id="column2" style="float:left; margin:0;width:22%;">
- target <br />
<audio controls="controls">
    <source src="audio/plate/Plate_30_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_18_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_27_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_28_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
</div>

<div id="column3" style="float:left; margin:0;width:22%">
- model-1 <br />
<audio controls="controls">
    <source src="audio/plate/Plate_30_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_18_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_27_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_28_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
</div>

<div id="column4" style="float:left; margin:0;width:10%">
- model-2 <br />
<audio controls="controls">
    <source src="audio/plate/Plate_30_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_18_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_27_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/plate/Plate_28_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
</div>
</div>

&nbsp;
### spring
<div id="contentBox" style="margin:0px auto; width:250%">
<div id="column1" style="float:left; margin:0; width:22%;">
- input <br />
<audio controls="controls">
    <source src="audio/spring/Spring_56_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_34_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_16_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_12_AET_CRNN_23_input.mp3" type="audio/mp3" />
</audio>
</div>

<div id="column2" style="float:left; margin:0;width:22%;">
- target <br />
<audio controls="controls">
    <source src="audio/spring/Spring_56_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_34_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_16_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_12_AET_CRNN_23_target.mp3" type="audio/mp3" />
</audio>
</div>

<div id="column3" style="float:left; margin:0;width:22%">
- model-1 <br />
<audio controls="controls">
    <source src="audio/spring/Spring_56_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_34_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_16_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_12_AET_Convolution_21_output.mp3" type="audio/mp3" />
</audio>
</div>

<div id="column4" style="float:left; margin:0;width:10%">
- model-2 <br />
<audio controls="controls">
    <source src="audio/spring/Spring_56_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_34_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_16_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
<audio controls="controls">
    <source src="audio/spring/Spring_12_AET_CRNN_23_output.mp3" type="audio/mp3" />
</audio>
</div>
</div>


&nbsp;
### Model

<br>Block diagram of the proposed model; adaptive front-end, latent-space and synthesis back-end:

<center>
<embed src="docs/AET.jpg" width="1000" >
</center>

<br>Detailed architecture of adaptive front-end:
<center>
<embed src="docs/front-end.jpg" width="300" >
</center>
Input frame size of 4096 samples and &plusmn;4 context frames.

<br>Block diagram of the latent-space:
<center>
<embed src="docs/SFIR.png" width="500" >
</center>

<br>Detailed architecture of the latent-space:
<center>
<embed src="docs/SFIR-table.png" width="500" >
</center>

<br>Block diagram of the synthesis back-end:
<center>
<embed src="docs/DNN-SAAF-SE-LSTM.png" width="700" >
</center>

<br>Detailed architecture of the synthesis back-end:
<center>
<embed src="docs/DNN-SAAF-SE-LSTM-table.png" width="400" >
</center>

Output frame size of 4096 samples.

<br>Plate and Spring settings:
<center>
<embed src="docs/fx-settings.png" width="600" >
</center>


&nbsp;
### Citation
>@inproceedings{martinez2020mix-wave-u-net,<br />
>   title={Modeling plate and spring reverberation using a {DSP}-informed deep neural network},<br />
>   author={Mart\'{i}nez Ram\'{i}rez, Marco A and Benetos, Emmanouil and Reiss, Joshua D},<br />
>   booktitle={IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)},<br />
>   month = {May},<br />
>   year = {2020},<br />
>   location = {Barcelona, Spain}<br />
>}<br />
