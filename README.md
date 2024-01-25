# GraphParsingTool
 Graph Parsing Tool for CROCS 2024

 ## usage
 Tool Name: ssml_parser.py
    
 ```python
 usage: [-h] [-input INPUT] [-img_prefix IMG_PREFIX] [-output OUTPUT] [-num_workers NUM_WORKERS]

optional arguments:
  -h, --help            show this help message and exit
  -input INPUT
  -img_prefix IMG_PREFIX
  -output OUTPUT
 ```
 __input__: the lab file or result file. Details of file format can be seen in CROCS 2024 Homepage(https://crocs-ifly-ustc.github.io/crocs/data.html)

 __img_prefix__: the directory of all images

 __output__: the output directory. For each sample, the tool will save a jpeg file and a json file with same name to this directory. The jpeg file contains the raw image and visual results of chemical structures in its label or result string. The json file records the __graph data__ of all chemical structures parsed from label or result string. See __train_48095.jpg__ and __train_48095.json__ for example. 




