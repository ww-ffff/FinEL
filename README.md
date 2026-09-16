# FinEL: A Large-Scale Benchmark for Financial Entity Linking

Entity Linking dataset for  Large Language Models texting and training

## Overview

FinEL is a high-quality human-annotated EL dataset. It includes 10,398 instances, covering 3 diverse difficulty-graded tasks, and 10 common financial concepts. 


## Dataset 

### Get the Data

- The annotated data: Economy_Text_En.json


### Data Format

- The annotated data (mention level)
```
{
  "Qid": "Q961407",
  "name": "business broker",
  "description": "person who acts as an intermediary between sellers and buyers of private businesses",
  "sentence": "The use of a business broker is not a requirement for the sale or conveyance of a business in most parts of the world.",
  "candidates": [
                  {"Qid": "Q961407",
                   "name": "business broker",
                   "description": "person who acts as an intermediary between sellers and buyers of private businesses"},

                  {"Qid": "Q105547359",
                   "name": "Business brokers initiative",
                   "description": "UK government business support scheme"},

                  {"Qid": "Q4830453",
                   "name": "business",
                   "description": "organization undertaking commercial, industrial, or professional activity"}
                ],

   "difficulty": 0,
   "type": "Business"
}
```
