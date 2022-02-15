# NLP Disaster 

Natural language processing framework for text analysis in social media data related to crisis management.

### Dependencies

This code uses Python 3.7.9 running after Miniconda3 environments with a GPU NVIDIA Geforce RTX 2060. The list of dependencies are described in the file _```requirements.yaml```_. To install them using Anaconda/Miniconda, simply create and activate an environment:

```
conda env create --name <cool_environment_name> --file=requirements.yaml
conda activate <cool_environment_name>
```

### Run

Once all dependencies are installed, run the main file ```disaster_response.py```

Please, ensure parameters and paths are correct to import the data. 

The function ```getDataInfo``` in the file ```utils.py``` contains a list of data files for each dataset. Be sure to load the proper file(s) and keep the target label in ```renamedColumns``` for the supervised classification approaches.

### Web Interface App

The interface is located in the subdirectory ```DisasterResponseApp```

To run the interface app in your local computer, first you need to install and update any missing/deprecated dependencies from the list described in the file _```requirements.xml```_ within this subdirectory.

Then, run the application file script ```run.py```. The web app server runs in your localhost address, port 5000 by default. You should be able to access through your browser at ```http://localhost:5000/```
