# Adversarial-Neural-Crytography

This folder the code for the project based on <a href="https://arxiv.org/pdf/1610.06918.pdf">Adversarial Neural Cryptography</a> implemented as part of the course Statistical Methods in Artificial Intelligence offered at IIIT Hyderabad.

### Team Members :
- Rahothvarman Prithiviraj (2020114008)
- Radheshyam Thiyagarajan (2020115009)
- Sudha Tanay Doddi (2020115010)

### Project checkpoints :
- [x] Code to randomly generate plain text and secret key
- [x] Define the model architectures for Alice, Bob and Eve
- [x] Code to train the above models
- [x] Tabulate the results, findings and learnings
- [x] Implement alternate architectures (GRU)

### Intructions to train the models :
- Run the ```baseline.ipynb``` file inside ```/Train``` to train the CNN baseline model from scratch. Code takes around 8 minutes to run on a GPU.
- Run the ```gru_variant.ipynb``` file inside ```/Train``` to train the GRU version of baseline model from scratch. Code takes around 9 minutes to run on a GPU.

### Instructions to test the models :
- Import the models .pth files from the ```CNN_models``` folder for the pre-trained CNN baseline model. Run ```test_baseline.ipynb``` file inside ```/Inference``` to test the model.
- Import the models .pth files from the ```GRU_models``` folder for the pre-trained GRU version of the baseline model. Run ```test_gru_variant.ipynb``` file inside ```/Inference``` to test the model.

### Guidlines to contribute to the project : 
- Clone the repository using ```git clone <link_to_the_repo>```
- Using the Conda Package Manager, create a new environment using ```conda create --name <env_name> --file requirements.txt```
- Create a New Branch from the latest commit to push any changes.
    - ```git checkout main``` to change to the main (default) branch.
    - ```git pull origin main``` to pull the latest changes.
    - ```git checkout -b <branch_name>``` to create and shift to the new branch.
    - After making changes in the new branch, ```git add .``` and ```git commit -m "Your Message"``` them.
    - ```git push origin <branch_name>```
- Start a Pull Request to merge the new branch to the existing branch. Wait for the approval of a fellow collaborator.
- Merging to be done by another collaborator only by resolving conflicts if any.
- After your PR is merged, delete the branch.
