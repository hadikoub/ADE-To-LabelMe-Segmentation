# ADE Segmentation JSON To Labelme Segmentation Format

This repository allow you to convert ADE dataset Json format for segmentation to LabelMe Json format 



## Requirements:

- Pydantic

## Usage



Place Json files into **Input** Folder and run the script. Results will be placed in **Output** Folder

You can adjust input and output folder by changing the following params inside `ade_format_2_labelme.py`:

```
ADE_FOLDER='./Input/'
OUTPUT_FOLDER='./Output/'
```

## RUN 

```bash
python3 ./ade_format_2_labelme.py 
```



## Acknowledgment 

```bibtex
    @inproceedings{zhou2017scene,
        title={Scene Parsing through ADE20K Dataset},
        author={Zhou, Bolei and Zhao, Hang and Puig, Xavier and Fidler, Sanja and Barriuso, Adela and Torralba, Antonio},
        booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
        year={2017}
    }
```

