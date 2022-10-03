# fastai Sudoku

Learn fastai data preparation by playing Sudoku

## Why?

I love fastai. However I constantly would try a new problem where the data looked *slightly* different to the courses - I have stopped several Kaggle competitions because preparing the data to ultimately build a `Learner` (where all the cool AI magic happens) was too difficult for me. I therefore wanted a way that I could repeatedly check back on to test my knowledge of the fastai API.

And what better way learn the library than to gamify it?

## What?

You are given a Sudoku puzzle and two challenges:
1. Create the Sudoku dataset using the `DataBlock` API
2. Solve the Sudoku puzzle with the `TfmdDL` class

Your job is to solve the two challenges above by creating and using *as many* of the function arguments as you can. Note that this approach is not by any means the most efficient way to go about the task of creating a `DataLoader` - but this is helpful to learn what different arguments, functions, and classes do in fastai.

> There are 2 notebooks in this repo. A sample solution notebook is in the `solutions` directory.

## Learning Outcomes

My learning outcomes were:

1. What all of the major fastai data preparation classes *actually do* and *why* they are necessary
2. That there are many ways within fastai to achieve the same outcome 
3. How to read fastai code (Jeremy & team use a lot of bleeding edge Python techniques, some of which I was unfamiliar with, and have a writing style that took me a bit of getting used to). However now that I feel much more comfortable with the source code, it is making troubleshooting a breeze.
  * You will also get a sense just how robust and flexible fastai is
  
## Feedback

I would love any and all feedback on this. I can't be the only one who struggled with learning the guts of fastai, so I am hoping this will help someone else.
