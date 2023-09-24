# Castaway
Castaway is a diffusion model which runs on dreambooth model. It uses stable diffusion library to generate images.
This model helps you to inject yourself into AI and make any images with your face. 

## To start with:
The user needs to upload 15-20 pictures of themselves to get good results and slight modification needs to be made in terms of step size and intervals. 
We use a thumb rule that the step size needs to be 100*(the number of images) and the interval can be same as step size but not greater than step size. 
The parameters need to be updated in the code and is shown in the picture below.

<img width="783" alt="Screenshot 2023-04-28 at 2 34 59 PM" src="https://user-images.githubusercontent.com/92366213/235106096-82bcb21d-b258-4c0c-8deb-9b781db05882.png">

Once the features extraction starts it might take the model about 30 mins to train depending on the GPU. 

## Generating images :

Once the training is completed we can test the model by prompting in the code or using the gradio UI/UX to prompt and get the result 

## Examples of Images generated:

![Unknown-2](https://user-images.githubusercontent.com/92366213/235106827-fac123ed-ae9f-4ee0-8e4a-a9f32ada14a9.png)
![Unknown-3](https://user-images.githubusercontent.com/92366213/235106850-92561ce0-81dd-443f-901e-a9b657d157b6.png)
![Unknown](https://user-images.githubusercontent.com/92366213/235106855-ab31fd00-8b52-4bbc-93dd-faf839c1d3b8.png)

