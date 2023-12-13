# DeepLearning

This is a project for creating a skin of Valorant's weapons skin from prompt texts.

The dataset that will be used is the images of the skins of one type of Valorant's weapon from various angles of view.

The deep learning model used in this project is the Stable Diffusion model v2.

## Training Model Steps
1. Train the model with the object dataset filled with images of the one type of Valorant's weapon, without skin, from various angles of view.
2. Train the model with the style dataset filled with images of the skins of one type of Valorant's weapon from various angles of view.

Notest: 
1. To run the TrainingTesting_code, you must create huggingface.co account and create the token
2. Hugging Face Token link: https://huggingface.co/settings/tokens
3. Don't forget to change the training image path to your personal training image path on your device
