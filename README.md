# colab-hosting-example
The `colab-hosting-example.ipynb` Jupyter notebook contains a minimal example to expose a trained machine learning model to the web through a normal RESTful API. The Flask web server is bundled with the Jupyter notebook to minimize the tooling necessary to show off your ML models, and keep the emphasis on the model itself.

## Quickstart
1. Sign in to [Google Colab](https://colab.research.google.com/)
2. File > Upload notebook > Github: `https://github.com/ardislu/colab-hosting-example.git`
3. Select `colab-hosting-example.ipynb`
4. Runtime > Run all

That's it! Google Colab is now running a RESTful API for a machine learning model. Usage instructions and further explanation are on the notebook itself.

## Complementary front-end 
Once you've run the notebook, try out my [demo front-end](https://ardis.lu/colab-hosting) to see how an actual website would interact with such a backend.