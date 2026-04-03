# WeatherPlotProject
# Rules
Students will complete two projects during the course. Each project takes approximately 4 weeks of work and ends with a presentation to the class.

The project will be carried out in groups of preferably two students (three-student groups are acceptable if needed); the evaluation will consider this aspect, so a project done by three must be more extensive than one done by two.  All students in each group should be part of the same class (I2A or I2B).  The group for the first project MUST be different than the groups for the second project: more specifically, any two people that are in a group together for the first project must be in different groups for the second.

The submission date will be the same for everyone and will be agreed upon with the students to avoid overlap with other deadlines. During this class, each group will present (using slides) their work and answer any questions from the class and the instructor.

Each project will focus on a different dataset for each group. The exploration of the available datasets, the selection of the dataset to use, and the type of analysis to be performed are integral parts of the project.

There will be three key moments during each project:

  1. Presentation of the chosen dataset to the class
  2. Intermediate presentation
  3. Final (graded) presentation and submission of the notebook
# Dataset Selection
The analysis of the dataset must include a part of exploratory data analysis, where some interesting attributes are analyzed in isolation and correlations between different attributes are examined, producing, where relevant, histograms, boxplots, heatmaps, scatter plots, timeseries plots, and other relevant visualizations.

The starting point is to find an interesting dataset. There will be a class where each group presents at least one dataset, explains why it is interesting, and proposes some possible analyses for the exploratory data analysis part. The choice can be revised later.

It is advisable to use an original dataset related to a problem you are familiar with, possibly from work or a hobby. Alternatively, here are some pointers to find interesting public datasets:

FiveThirtyEight datasets
Swiss OpenData (over 2000 datasets on various topics)
Collection of datasets on various topics
GroupLens datasets, which contain user ratings on movies, jokes, books, etc.
Chicago crime database, exportable in CSV and other formats
UCI Machine Learning Datasets repository
Stack Overflow and Stack Exchange open-source datasets, Kaggle Stack Overflow datasets
Slate Star Codex / Astral Codex Ten reader surveys, with questions on various topics. It is a blog with a peculiar reader base, not representative of the population at large. Results available in CSV format for various editions: 2017, 2018, 2019, 2020, 2022, 2024.
Datasets about sports, collected by the Ohio State University
Find a dataset with the following characteristics.

Have at least a few thousand rows, ideally tens of thousands.
On a topic that is maybe of niche interest but you have some knowledge about and can easily be explained to others. Avoid highly-specialized datasets about abstruse topics you don't understand.
Should have at least 4 or 5 different interesting and easy to understand attributes, ideally with a mix of categorical and numerical attributes. Some datasets have a lot of unclear attributes with limited interest, you should ignore these.
# Presentation of the Chosen Dataset to the Class
Each group will prepare a brief presentation (max 2 minutes), possibly with slides, to describe:

The chosen dataset: why it's interesting; how many observations, how many columns, and what types they are
A description of at least 3 or 4 different columns you find interesting for your analysis
A description of some analyses you would like to perform on this dataset
By the time of the presentation, you should have already imported the data into Pandas. If possible, show a rough exploratory analysis of some interesting columns (for example, histograms showing their distribution).

# Intermediate Presentation
Each group will prepare a brief presentation (max 4 minutes), with some slides, in which they:

Briefly summarize the chosen dataset
Show some relatively complete analyses
Propose some analyses that still need to be performed and/or raise any doubts
## Important suggestions:

Do not show all the charts you made, but focus on the 3 or 4 most interesting ones.
Show at least one ambitious chart/analysis that you haven't completed yet or are unsure how to represent. The idea is to get feedback and provide inspiration to your peers.
The best charts convey a clear and interesting message. For each chart you show, explicitly mention the message it conveys.
# Final Presentation and Notebook Submission (Graded!)
Each group will present their work (using slides) in max 5 minutes (if working in pairs) or 7 minutes (if in groups of three), answering any questions from the class and the instructor.

The presentation will consist of:

One or two slides for a concise presentation of the dataset (what does it represent? why is it interesting?). This should take less than a minute.
A series of analyses/charts showing the results of the exploratory analysis of the dataset.
Any interactive charts or animations can be shown separately if needed.
Each group will submit a .zip file containing:

The presentation slides (PPT or PDF)
The notebook used to generate the charts, already executed and saved in HTML. The notebook should include titles, text (in markdown cells), code, and charts and should ideally only depend on the dataset CSV file (which is not included in the submission). At the beginning of the notebook, describe:
Where the dataset can be found
Any preliminary operations you performed manually before importing it (ideally none!)
# Important Suggestions for Presentations
Practice the presentations at least 2 or 3 times, preferably using classmates as test subjects, and make sure they understand everything you're saying. Your presentation should be accessible even to people who are not already familiar with your project! Time your presentation to ensure you’re within the time limits.
Don’t waste time on unimportant details. The available time may seem short, but it's more than enough to show a lot of material, especially if the presentation is well-structured.
Ensure that the text on your slides and charts is legible when projected.
Ensure that all charts have clear, descriptive axis labels. If numbers have units of measurement, include them in the axis label. For example, for a histogram of people's heights, label the axes like this:
X-axis: Height [cm]
Y-axis: Number of people
Make sure each chart you show has a clear message, and if possible, use that message as the chart title.
# Evaluation Criteria
Projects will be evaluated based on the following criteria:

Technical quality
Correctness of analyses and conclusions
Proper choice of plot types
Do plots always have a clear message?
Do data really support this message?
Depth of the analysis
Clarity and conciseness of the presentation
Use of proper technical language
Time management (do not go overtime!)
Presentation quality
Are plot axes labeled correctly?
Are plots self-explanatory?
Are slides clean, well organized and structured?
Clarity, completeness and conciseness of the submitted notebook
