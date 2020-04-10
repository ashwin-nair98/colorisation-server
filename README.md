# Image colorisation server

Host models to be used for colorisation of images. Please note that the size of the images uploaded should be 256 x 256. Check sample folder for images. 

This is a simple python server that uses [deeplearn.js](https://deeplearnjs.org/) and weights from a pretrained model.

## Serving

```sh
python serve.py --port 8000
```

If you open [http://localhost:8000/](http://localhost:8000/) in a browser, you should see an interactive demo.
