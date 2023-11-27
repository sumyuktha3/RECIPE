### RECIPE RECOMMENDATION SYSTEM 
In the culinary world, home cooks perpetually seek inspiration to elevate their cooking domain. This  led to the conception of a groundbreaking Recipe Recommendation System, aimed at revolutionizing the way we discover and experiment with new dishes.
This innovative system, powered by a technology stack encompassed by machine learning and designed for execution in platforms like Google Colab and Jupyter Notebook, introduces a paradigm shift. 
In the process, we construct a recommendation system using the K-Nearest Neighbors (KNN) with Means model. It leverages user ratings to make informed recipe suggestions. In essence, this Recipe Recommendation System transcends the traditional culinary search paradigm.

### Hardware Requirements
The hardware requirements for the implementation of the proposed cosmetic product comparison system from handwritten images are outlined below:

### High-Performance Workstation:
A workstation with a multicore processor (e.g., Intel Core i7 or AMD Ryzen 7) for parallel processing.
Graphics Processing Unit (GPU):
A dedicated GPU (e.g., NVIDIA GeForce RTX series) for accelerated computations, especially for deep learning tasks.

### Memory (RAM):
Minimum 16GB of RAM to handle the computational demands of OCR and image processing tasks.

### Storage:
Adequate storage space (preferably SSD) to accommodate large datasets and model files.

### High-Resolution Display:
A high-resolution 5 for detailed image analysis and visualization.

### Software Requirements
The software requirements for the successful deployment of the cosmetic product comparison system are as follows:

### Operating System:
A 64-bit operating system, such as Windows 10 or Ubuntu, for compatibility with modern deep learning frameworks.

### Development Environment:
Python programming language (version 3.6 or later) for coding the OCR
system.

### Machine Learning Frameworks:
Installation of machine learning frameworks, including KNN to leverage pre-trained models and facilitate model training.

### Sklearn Libraries:
Integration of surprise libraries, such as KNN With Means, to incorporate recommendation system.

### PROJECT ARCHITECTURE :
![Minimalist Colorful Organizational Structure List Graph (1)](https://github.com/sumyuktha3/RECIPE/assets/75235818/0d0a272d-40a4-458b-86cf-e1d260dc6604)

### PROGRAM: 
### BUILDING THE MODEL 
```
         def build_recommender(user_based=False, sim_type='cosine'):
                   sim_options = {
                   "name": sim_type,
                   "user_based": user_based
                                  }
          return KNNWithMeans(sim_options=sim_options)
```
### EVALUATION
```
cross_validate(item_based_recommender, data, measures=['RMSE', 'MAE'], cv=5,
               verbose=True)
    Acorpus.append(tokens)
```
### PREDICTION
```
    i = 1
    for i in range(150):
       prediction = item_based_recommender.predict(i,167)
       print(round(prediction.est,2), end=', ')
     i = i + 1

```
### EXECUTION
```
   user_id = 2617981
   ingredient_list = 'carrot'
   table_list = set_up_rr(user_id,ingredient_list)
   table_list = table_list.to_numpy()
   test = pd.DataFrame(table_list)
   test
```
### OUTPUT :
![output](https://github.com/sumyuktha3/RECIPE/assets/75235818/b87e7f3a-17a4-42b6-a6d6-dd0b588344d8)

### RESULT:
A recipe recommendation system powered by machine learning holds great promise in transforming the way we plan, cook, and enjoy meals. It offers personalized recipe suggestions that not only simplify meal planning but also contribute to healthier dietary choices, reduced food waste, and a more diverse culinary experience. As technology continues to advance, the recipe recommendation system has the potential to play a pivotal role in promoting mindful, health-conscious, and eco-friendly cooking practices, ultimately leading to more satisfying and responsible culinary journeys for users.
