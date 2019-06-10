[![Build Status](https://travis-ci.org/tylergrinn/big-ridge-outdoor-kitchens-modules.svg?branch=master)](https://travis-ci.org/tylergrinn/big-ridge-outdoor-kitchens-modules)

# Big Ridge Outdoor Kitchens Configurator

# Adding a new module

1. To add a new module, open a sketchup file and click `File -> Export -> 3D Model`
2. In the dialog box that opens up, click `options` and make sure the options match with the picture below\
![Export Options](docs/export-options.PNG "Export Options")
3. Navigate in this repository to the folder you'd like to use and upload the resulting .obj file from the last step using the `Upload files` button. You'll need to add a message describing the additions and then click `Commit changes`.
4. Navigate to the root directory and click the file `config.yaml`
5. Click the ![Edit](docs/edit.PNG "Edit") button just above the start of the file and to the right. 
6. Copy and paste one of the existing modules. Each module starts with `- name: NAME` and ends with a blank line. Edit it to match the name and location of the file you uploaded.
