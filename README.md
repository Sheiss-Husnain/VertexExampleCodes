# Vertex Pipeline Starter Notebooks

Adding Notebooks to Vertex AI workbench and tailoring them to specific datasets and projects to streamline work

AutoMLpipeline: Using kubeflow to train model (classification in this case) and evaluate model before deployment using a threshold.  Note - ignore the emoji stuff, it's just a reminder on how component outputs are used as inputs for the next pipeline step

CustomeModelpipeline: This version allows me to write my own model for the training component and then perform batch prediction.  See train.py for example file (uses DecisionTreeClassifier).

Run the following commands in terminal to build terminal and push to Container Register on Cloud Console:

> docker build ./ -t $IMAGE_URI
> docker push $IMAGE_URI
