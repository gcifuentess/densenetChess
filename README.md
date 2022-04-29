# DensenetChess AI Bot
![1](https://user-images.githubusercontent.com/66188250/165884288-4eb3d4eb-980a-449f-9169-50ba1784cfb4.png)

This repo contains the code of the implementation of a Deep Convolutional Neural Network Learning model, based on the Densenet121 architecture.

## Installation

The best way to implement this code is to import the ```densenetChess.ipynb``` file into a Colab Notebook and run it from there.

## Usage

If you just want to see the AI in action, upload to the Colab Session the file ```model_densenet_tf2.h5``` and run the cell with this code:

```Python
if os.path.isfile(model_path):
    model = K.models.load_model(model_path)
```
Them run all the cells under the "Playing with the AI" zone

If you want to re train the model, you need to import to de Colab Session the files ```dataset.7z``` and ```stockfish_14.1_linux_x64.zip```

When playing you can expect to see boards like this:

![10](https://user-images.githubusercontent.com/66188250/165885176-b4467035-54bf-432a-a552-5abaa2df562e.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Author
* **Gabriel Cifuentes** - [gcifuentess](https://github.com/gcifuentess)
