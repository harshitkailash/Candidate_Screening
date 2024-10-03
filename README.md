# Candidate_Screening

## Explanation:

### Candidate Data:

Each candidate is represented as a dictionary, with their scores for each evaluation criterion (e.g., technical expertise, problem-solving, etc.).

### Weights:

The weights for each evaluation criterion are predefined. These weights ensure that technical expertise is prioritized more heavily (40%) than communication (20%).

### Score Calculation:

The compute_score() function calculates a candidate's total score by multiplying their individual scores by the weight of each criterion.

### Ranking Candidates:

Candidates are ranked in descending order of their total score using the sorted() function.

### Print and Display:

The ranked candidates are printed, displaying their names and total scores.
