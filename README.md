# Format converter for OIDv4 to XML
Contains a notebook which can convert a folder of images/annotations in OIDv4 format to the XML format required for PASCAL-VOC.

# Before you get started
- Knowledge about open images v4
- Basic knowledge about images and annotations/labels for machine learning
- Basic python knowledge (3.6.5 was used here)

# Setup
**How to obtain this repository:**
```sh
git clone https://github.com/danielc92/oidv4-to-xml.git
```
**Modules/dependencies:**
- `pillow`

Install the following dependences:
```sh
pip install pillow
```

# Tests
- Tested grabbing bounding boxes from OIDv4 .txt label file, accounting for multiple bounding boxes.
- Tested converting french fries validation set into XML files successfully

# Contributors
- Daniel Corcoran

# Sources
- [Open Image V4 Dataset](https://storage.googleapis.com/openimages/web/index.html)
