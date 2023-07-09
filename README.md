# Filtering Top Interns Project

This project aims to identify suitable candidates for a machine learning internship based on specific criteria and sort them by performance. It utilizes a dataset containing information about applicants' skills and availability for a remote internship.

## Usage

1. Upload the dataset file `Applications_for_Machine_Learning_internship_edited.csv` to your Colaboratory environment.
2. Run the code cells in order to filter the candidates and select the top interns.
3. The resulting dataframe `top_interns` will contain the top 50 interns based on their performance.

## Filtering Criteria

The following criteria are used to filter the candidates:

- Python skills: At least 2 out of 3
- Machine Learning skills: At least 2 out of 3
- Natural Language Processing (NLP) skills: At least 2 out of 3
- Deep Learning skills: At least 2 out of 3
- Other skills: Must contain the term "machine learning" (case-insensitive)
- Availability: Must be available for 3 months starting immediately for a full-time work from home internship.

## Sorting and Selection

The filtered candidates are then sorted based on their performance in their postgraduate (PG) and undergraduate (UG) degrees. The sorting is done in descending order of PG performance and then UG performance.

Top 50 interns based on their performance are selected and stored in the dataframe `top_interns`.

## Dataset

The dataset used for this project should be uploaded to the Colaboratory environment and stored as the file `Applications_for_Machine_Learning_internship_edited.csv`. It should contain the following columns:

- Python (out of 3)
- Machine Learning (out of 3)
- Natural Language Processing (NLP) (out of 3)
- Deep Learning (out of 3)
- Other skills
- Are you available for 3 months, starting immediately, for a full-time work from home internship?

Make sure that the dataset file is correctly formatted and matches the provided column names.

For any questions or issues, feel free to leave a comment.

