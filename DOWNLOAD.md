Dataset **Animal Drone** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/S/4/iI/U3XmMkTsXkuD7GrbNq4lbPb8EvnKCsU6ZCZUoxK2FPEVqCMRzdThwHfl1DMU5BVdpHu86EWUVTWMkPUbQTr9w0IrhnimkKpvMub4Xi8CQ07PudjVLuvMWuHowKGd.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Animal Drone', dst_path='~/dtools/datasets/Animal Drone.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/folio3-krxsh/animal-drone-5gqre/dataset/2/download)