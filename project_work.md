# Proj Work

![progress](https://progress-bar.dev/71/?title=days_left_to_complete_project_21)

## Project work so far
- [x] Evaluated college data - Bad results.
- [ ] probably proceeding with RAM consumption reduction

## Project Work Tools
+ [Project Plan ML -> Notion](https://www.notion.so/Project-Plan-ML-2cf867e8ad184c1a9e1cdc716dc2d16a)
+ [Data Analysing](https://docs.google.com/spreadsheets/d/12WxnLtQtnPFIIHaeRpjMtQPJy4w857fcma15PrV85zU/edit#gid=664785351)
+ [Project_Pruning Mindmeister](https://www.mindmeister.com/1586195009?t=8wgbvnYtph)
+ [My pruning repository](https://github.com/sachinkmohan/ssd_keras)
+ [Coggle Project Exhaustive task list](https://coggle.it/diagram/YCuv81R6dWDFjAA9/t/things-to-be-done-calendar)

## Issues
+ [Quantization Issue](https://github.com/tensorflow/model-optimization/issues/620)

## Notes
+ 
+ Most used repositories 

## :bulb: Bookmarks :bulb:
- [Link](https://www.notion.so/09063076eb084708a0900084dac96f61?v=60946ada361543868c8c0dd13370d783)

## Terminal Commands

 Description | Command 
 ---|---
 Log terminal data | `script screen.log`
Nvidia-smi to log every 500ms | `nvidia-smi -lms 500`
Open in No Browser mode | `jupyter notebook --no-browser --port=8889`
Tunnelling | `ssh -NfL localhost:8888:localhost:8889 user@server_name`
Prints every 25th line, starting line is 24, for ram | `sed -n '24~25p' source_copy.log > source_copy_new.log`
Prints every 25th line, starting line is 15, for time | `sed -n '24~25p' source_copy.log > source_copy_new.log`
cut 62,63,64 characters for extracting ram | cut -c 62,63,64 filename
Adding load to the CPU on all 8 cores | `nproc | xargs seq | xargs -n1 -P8 md5sum /dev/zero`


## Current Bookmarks

Description | Type
---|---
[Post training quantization](https://www.tensorflow.org/lite/performance/post_training_float16_quant) | blog
[TF lite course coursera](https://www.coursera.org/learn/device-based-models-tensorflow/home/welcome) | Coursera Course

## Read list

Topics | Theme
---|---
[Deep Lizard - Layers](https://deeplizard.com/learn/video/FK77zZxaBoI) | Currently reading
[Robotics basics](https://allshire.org/getting-started-robotics/) | Robotics-General
[Deep Lizard Website](https://deeplizard.com/) | ML Course basics
[642% CPU used along with GPU](https://stackoverflow.com/questions/65707430/642-cpu-used-along-with-gpu-during-training-is-it-normal) | CPU utilization

## Watch List

Topics | Theme
---|---
[Inside TensorFlow: Summaries and TensorBoard](https://www.youtube.com/watch?v=OI4cskHUslQ&t=2134s) | Tensorboard

