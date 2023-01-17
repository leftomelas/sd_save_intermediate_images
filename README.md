# Stable Diffusion Save intermediate images extension 

A custom extension for [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) that implements saving intermediate images.

<img src="images/extension.png"/>

## Installation

The extension can be installed directly from within the **Extensions** tab within the Webui.

You can also install it manually by running the following command from within the webui directory:

	git clone https://github.com/AlUlkesh/sd_save_intermediate_images/ extensions/sd_save_intermediate_images

## Limitations
Does not work with DDIM and PLMS

## Output

Once the image generation begins, the intermediate images will start saving in a directory under a new \outputs\(*txt2img or img2img*)-images\intermediates directory.

Please be aware that _Image creation progress preview mode_ in the webui's settings affects how the intermediate images are created.

You can also make a video out of the intermediate images:
<p><img src="images/13655-sample.gif"/>
<img src="images/13642-sample.gif"/>
<video src='https://user-images.githubusercontent.com/99896447/213034519-7b6ed42f-39d5-4994-a8b7-c85ec92bda84.mp4'></video>