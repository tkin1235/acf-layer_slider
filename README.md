# ACF acf-layer_slider Field

1. This acf extension REQUIRES layerslider!
2. Wanna know how to use it?
<?php layerslider(get_field('layer_slider')); ?>



-----------------------

### Description

Ever tired of telling your client to use a shortcode in a wysiwyg area, or another acf field created for the sole purpose of throwing in an layerslider shortcode?
Well no longer! This extremely simple extension will query layerslider for a list of all sliders, and allow your client to select which one they want in a comfy cozy select field.
This simply queries layerslider, and puts the id of the slider selected by the user into the acf field. Then when you return your acf field with get_field('field_name'), you pass the output ID to the layerslider 'layerslider()' function.
In your template you can do something like this

<?php layerslider(get_field('acf_field_name_or_whatever_i_guess_you_called_it')); ?>

... and BAM, your front end is looking damn sexy. Now your client can go ****ing crazy adding layers and animations and sh**.

This is mostly so you can use ACF logic and stuff with layerslider. Please enjoy.

Email tkin1235@gmail.com for comments/questions

### Compatibility

This ACF field type is compatible with:
* ACF 5
* ACF 4

### Installation

1. Copy the `acf-layer_skuder` folder into your `wp-content/plugins` folder
2. Activate the layer_slider plugin via the plugins admin page
3. Create a new field via ACF and select the layer_slider type
4. Please refer to the description for more info regarding the field type settings

### Changelog
Please see `readme.txt` for changelog
