# creating_dataset_TFRecord

This repo is part of my [capstone project](https://github.com/DanWang1230/Capstone_Programming_A_Self_Driving_Car) in Udacity's nano degree of self-driving car. The goal is to create my own dataset using images from the simulator and real site. The created dataset is then used for [model training](https://github.com/DanWang1230/model_training_object_deteciton_API/blob/main/README.md).

I found [Repo 1](https://github.com/josehoras/Self-Driving-Car-Nanodegree-Capstone), [Repo 2](https://github.com/vatsl/TrafficLight_Detection-TensorFlowAPI), and [this](https://medium.com/@WuStangDan/step-by-step-tensorflow-object-detection-api-tutorial-part-2-converting-dataset-to-tfrecord-47f24be9248d) instruction very helpful.

---

## Pipeline

### Dataset
I used [this dataset](https://drive.google.com/file/d/0B-Eiyn-CUQtxdUZWMkFfQzdObUE/view).

### Creating the TFRecord File

```
python data_conversion_udacity_sim.py --output_path sim_data.record
```

```
python data_conversion_udacity_real.py --output_path real_data.record
```
