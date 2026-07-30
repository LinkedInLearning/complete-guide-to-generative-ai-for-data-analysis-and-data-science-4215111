# Complete Guide to Generative AI for Data Analysis and Data Science
This is the repository for the LinkedIn Learning course `Complete Guide to Generative AI for Data Analysis and Data Science`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

GenAI has the potential to enable many more people to work with and analyze data, but to succeed, you need a solid foundation in data management, statistics, and machine learning. This course provides that foundation. Instructor Dan Sullivan teaches how to break down business questions and data science questions into components that can be addressed programmatically and then how to use genAI to create programs and scripts to implement a solution. This course focuses on the three pillars needed to be a successful data analyst or data scientist: problem solving skills, an understanding of statistics and machine learning, and practical experience with data management procedures.

## Instructor

Dan Sullivan

Enterprise Architect, Big Data Expert

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/dan-sullivan?u=104).

## Running the exercise files

The exercises are Jupyter notebooks grouped by chapter under `exercises/`. To run them locally:

```bash
# 1. Clone this repository
git clone https://github.com/LinkedInLearning/complete-guide-to-generative-ai-for-data-analysis-and-data-science-4215111.git
cd complete-guide-to-generative-ai-for-data-analysis-and-data-science-4215111

# 2. Create and activate a virtual environment (Python 3.12 or 3.13)
python3 -m venv .venv
source .venv/bin/activate        # On Windows: .venv\Scripts\activate

# 3. Install the dependencies
pip install -r requirements.txt

# 4. Launch Jupyter and open the notebook for the chapter you're working on
pip install jupyter
jupyter notebook
```

Each notebook reads its data from its own chapter directory, so open and run a
notebook from within its chapter folder (for example, run
`exercises/Ch13/13_04_NeuralNetModel.ipynb` from `exercises/Ch13/`) so that the
relative data-file paths resolve.


[lil-course-url]: https://www.linkedin.com/learning/complete-guide-to-generative-ai-for-data-analysis-and-data-science
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQHoNlvx8mmVQw/learning-public-crop_675_1200/learning-public-crop_675_1200/0/1727369807975?e=2147483647&v=beta&t=4OD6KVnCo_3jmU727B2xTsXFsM1GTiiCQa-S0Mp4mHs

