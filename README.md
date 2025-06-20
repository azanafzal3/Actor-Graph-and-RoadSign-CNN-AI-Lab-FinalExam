
# AI Lab Final Exam - Muhammad Azan Afzal (i221741)

## Question 1: Actor Connection Finder (Graph Search)

### Problem
Inspired by the "Six Degrees of Kevin Bacon", this task involves finding the shortest connection (in terms of movie co-appearances) between two actors using graph search.

### Dataset Description
The dataset is organized in three CSV files:
- `people.csv`: Information about people (person_id, name, birth).
- `movies.csv`: Information about movies (movie_id, title, year).
- `stars.csv`: Relationships between people and movies (person_id, movie_id).

### Task
Build an AI tool that:
- Models actors and their movie appearances as a graph.
- Applies a search algorithm to find the shortest path between two actors.

### Output
- Shortest path (sequence of actor-movie-actor).
- Reasoning behind the chosen search technique (e.g., Breadth-First Search for shortest path).

---

## Question 2: Road Sign Classifier (Neural Networks)

### Objective
Develop a neural network model to classify road signs from images using supervised learning.

### Task Requirements
- Use OpenCV (`cv2`) to read and preprocess images.
- Implement `load_data(data_dir)` function:
  - Resize images to `(IMG_WIDTH, IMG_HEIGHT)`
  - Return `(images, labels)` as lists of NumPy arrays and integer labels.

### Dataset Structure
```
data_dir/
  ├── 0/
  ├── 1/
  ├── ...
  └── NUM_CATEGORIES-1/
```

### Model Specifications
- Input shape: `(IMG_WIDTH, IMG_HEIGHT, 3)`
- Output layer: `NUM_CATEGORIES` units with `softmax`
- Experiment with:
  - Conv2D, MaxPooling2D layers
  - Dense hidden layers
  - Dropout for regularization

---
###DataSet Link for this
https://drive.google.com/drive/folders/1u0KALHf6sAqh_Yn5CkxLbN5qP14fIQPC?usp=drive_link

---

## Author
**Name:** Muhammad Azan Afzal  
**Roll Number:** i221741  
**Batch:** Cyber Security 22  
