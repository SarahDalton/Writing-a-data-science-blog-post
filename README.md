# Writing-a-data-science-blog-post
## Project Steps and Instructions
Key Steps for the Project
Feel free to be creative with your solutions, but do follow the CRISP-DM process in finding your solutions.

Pick a dataset.

Pose at least three questions related to business or real-world applications of how the data could be used.

Create a Jupyter Notebook, using any associated packages you'd like, to:

Prepare data:
Gather necessary data to answer your questions
Handle categorical and missing data
Provide insight into the methods you chose and why you chose them
Analyze, Model, and Visualize
Provide a clear connection between your business questions and how the data answers them
Communicate your business insights:
Create a Github repository to share your code and data wrangling/modeling techniques, with a technical audience in mind
Create a blog post to share your questions and insights with a non-technical audience

## Information
The motivation for this project was to use the data sets from the Stack Overflow survey to answer 3 business questions. As I am a women who has recently had a career change into tech, I was interested in how represented women are in the survery respondants, as well as seeing whether the increase in women in tech has had an impact on the proprtion of full-time emplyed people within the industry. 
The questions I answered were:
1) Has the proportion of females increased between 2017 and 2023?
2) How has the number of full time employed changed between 2017 and 2023
3) Is there a relationship between full time employed and proportion of females?

I found that the proportion of females has actually decreased between 2017 and 2022, which means the are more under represented in the survey than they are in the industry. I also found that the proportion of full-time employed decreased in 2021 but has began to increase again in 2022 and 2023. It was speculted that this could be due to the impacts of Covid but would require further investigations to be sure. Finally, there was a positive linear relationship between the proportion of females and the proportion of full-time employed. However, there is no data to conclude whether these impact each other or whether there are other factors which may create this relationship.

The blog post can be found here: https://medium.com/@sarahdalton1988/women-in-tech-c4f7870bcd3b

The jupyter Notebook 'Writing a Data Science Blog Post.ipynb' can be found in the repository. It contains all the code involved in this investigation.

Reference
https://www.bcs.org/articles-opinion-and-research/why-we-need-more-women-in-tech/
https://www.womenintech.co.uk/women-in-tech-survey-2023#:~:text=The%20majority%20of%20people%20surveyed,are%20noticing%20the%20gender%20gap.

## Libraries Used
numpy
To install: !pip install numpy

pandas
To install: !pip install pandas

matplotlib.pyplot
To install: !pip install matplotlib

