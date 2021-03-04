# The TW-NCU-ICIP-Lab-dataset

This is a small image dataset designed for outdoor street view segmentation in Taiwan. In order to train the Fast-SCNN from scratch using in our research, we took photos around the Taoyuan High Speed Rail by ZED2 RGB-D camera. 
The necessary categories for outdoor walking are sidewalk, crosswalk, stair, and road. Therefore, the data sets we collect are these 4 types; in order to maintain the robustness of these 4 categories, we collected image data of four seasons, daytime, and no rain. In addition, the angle of view is mainly on the sidewalk and crosswalk.

Download are available at: https://drive.google.com/file/d/1uBV5Jslml_Imvf0WVRnjZE6XPOf1ci09/view?usp=sharing


## Usage

`.\Training\image\` All the training data.<br>
`.\Training\label\` All the labeled data corresponding to training data. 8-bit image.<br>
`.\Validation\image\` All the validation data.<br>
`.\Validation\label\` All the labeled data corresponding to validation data. 8-bit image.

## License

You will be licensed under the LICENSE file in the root directory. Please cite this paper as reference if you are using our dataset in your research.


## Contact

Please feel free to contact us with any questions, suggestions or comments:

* Wen-June Wang
* wjwang@ee.ncu.edu.tw
