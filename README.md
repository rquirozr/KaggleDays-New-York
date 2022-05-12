# KaggleDays-New-York

## What files do I need? ([link](https://www.kaggle.com/competitions/whichbookshouldiread/overview))
You would need the books.csv, users.csv, and train_ratings.csv files to get the training data which consists of books' and users' information. Your aim is to use the given data to develop your solution to predict the rating for the testing dataset present in test_ratings.csv and prepare a submission file with the format present in sample_submisison.csv.

## What should I expect the data format to be?
The dataset provided is tabular data.

## What am I predicting?
Your aim is to predict the value of the rating feature for the testing dataset and generate a submission file with id and rating as features. A sample submission file is provided in the dataset for reference.

## Files
* books.csv - the data provided about the books' information
* users.csv - the data provided about the users' information
* train_ratings.csv - the train set consists of a book-user rating pair.
* test_ratings.csv - the test set consists of a book-user rating pair.
* sample_submission.csv - a sample submission file in the correct format
# About the data set
## 1) books.csv
The dataset provided in the books.csv consists of the following features:

* book_id: Unique ID for each book in the data set.
* title: The title on the book's cover.
* author: Name of the author for the book.
* year: The year when the book was first published.
* publisher: The publisher who published the book for the first time.
## 2) users.csv
The dataset provided in the users.csv consists of the following features:

* user_id: Unique ID for each user in the data set.
* age: The age of the user.
* city: The city to which the user belongs.
* province: The province to which the user belongs.
* country: The country to which the user belongs.
## 3) train_ratings.csv
The dataset provided in the train_ratings.csv consists of the following features:

* id: Unique ID for each data point in the training dataset.
* user_id: The ID for a user from the users' data set.
* book_id: The ID for a book from the books' data set.
* rating: The rating which the user has given for the particular book on a scale of 1-10.  (Target feature)
## 4) test_ratings.csv
The dataset provided in the test_ratings.csv consists of the following features:

* id: Unique ID for each data point in the training dataset.
* user_id: The ID for a user from the users' data set.
* book_id: The ID for a book from the books' data set.
## 5) sample_submission.csv
The dataset provided in the sample_submission.csv consists of the following features:

* id: Unique ID for each data point in the testing dataset.
* rating: The rating which the user has given for the particular book on a scale of 1-10.  
(To be predicted based on the information from test_ratings.csv)