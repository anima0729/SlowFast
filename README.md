# SlowFast

## Requirements

- Python >= 3.7
- albumentations
- pytorchvideo
- transformers
- sklearn
- numpy
- opencv2
- matplotlib

## Model

- Model : slowfast_16x8_r101_50_50   [[paper]](https://arxiv.org/pdf/1812.03982.pdf)

- Original Code : [PySlowFast](https://github.com/facebookresearch/SlowFast)

## Preprocessing Data (Training)

```
datasets/
	- Label_Folder/ (Sorted by Label & Folder Name Must Contain Label)
		- Label_Folder_mp4_event_number/ (Sorted by Event Number) (If you process Video_Preprocessing.ipynb, You can make this folder)
			- *.png
		- *.mp4
		- *.json
```
	
## Preprocessing Data (Testing)

```
datasets/
	- Label_Folder/
		- Label_Folder_mp4_event_number/ (If you process Video_Preprocessing.ipynb, You can make this folder)
			- *.png
		- *.mp4
		- *.json
```

## Model Link (Trained Model)

- [[Model Link]](https://drive.google.com/drive/folders/1bzlFKdf9zc0jKvizE63XDPIVhRraeFnp?usp=sharing)

## Reference

- [Private 1위 Slowfast](https://www.dacon.io/competitions/official/235806/codeshare/3635?page=1&dtype=recent)<br>
	- by. younggeun
	<br>
- [private 2위 slowfast](https://www.dacon.io/competitions/official/235806/codeshare/3640?page=1&dtype=recent)<br>
	- by. siwooyong
