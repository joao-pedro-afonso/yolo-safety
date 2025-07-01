# Security Equipment Detector and Analytics

This project aims to use YOLO, an Object Detection Model, in order to detect if the workers at the factory are using the adequate security equipment and extract metrics that can help to evaluate and discuss the security of that factory.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Installation

```bash
# Clone the repository
git clone https://github.com/joao-pedro-afonso/yolo-safety.git
cd yolo-safety

# Install dependencies
pip install -r requirements.txt
```

## Usage

By following the notebook you can train and apply the model to different use cases.

The dataset can be accessed in https://universe.roboflow.com/wyhil-ru2ds/workers-safety-equipment-z1mra.


## Resultss

The notebook shows how the model was successfully trained and applied to different images, not only to the test set, but also to a different video. The results of the video inference can be seen in result_videos/ .

![VIDEO](./result_videos/image.png)

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

João Afonso - [jpcdma@gmail.com](mailto:jpcdma@gmail.com)
