# tensorrt_infer

## Build

```
cd ../build
cmake ..
make 
```


## Run the inference 
```
./infer_model ../unet_segemntation.trt <path_to_image_to_process>/img1.jpg   <path_to_image_to_save>/detected8.jpg
```

## Models ONNX and TRT

https://drive.google.com/file/d/1U0XdUONL-uLEzI_x2S4pxhLTmeXz1CS_/view?usp=sharing
