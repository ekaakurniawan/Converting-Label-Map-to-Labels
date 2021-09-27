# Converting Label Map to Label Names

Notebook to convert label map to label names for object detection.

## Setup and Run
- Launch Intel® DevCloud remote development environment for OpenVINO with TensorFlow integration from [this link](https://software.intel.com/content/www/us/en/develop/offsite/devcloud-edge/openvino-integration-with-tensorflow.html).
- Go to `File` and click `Open...`.
- In the new `Files` window, drop down `New` button and click `Terminal`.
- Run the following commands on the terminal.
```
$ cd Reference-samples/iot-devcloud/openvino-dev-latest/developer-samples/python/Openvino_Tensorflow/classification-python
$ git clone https://github.com/ekaakurniawan/Converting-Label-Map-to-Labels.git
```
- Go back to the `Files` window and go inside `Converting-Label-Map-to-Labels` directory.
- Upload your label map file you want to convert into `input` directory.
- Run `convert_label_map_to_labels.ipynb`.
- Modify the notebook accordingly and save the label files into `output` directory.
