
# Lasso Regression Streamlit App

![Status](https://img.shields.io/badge/status-in%20development-yellow)

Simply upload a csv / excel / sqlite db with your desired data and select a target feature to predict.

The model will initially train itself and provide an RMSE value  (better if close to 1 but depends on the size of data / number of features).

This RMSE number can then be fine tuned by specifying two hyperparametres:

 - _alpha_ which sets the capture net of the lasso model.
 - _iterations_ which train the model on for the specified number of epochs.

Once the model is fine-tuned, the ideal values can then be used to run on the desired dataset - it will automatically hunt for features in all the rest of columns and predict a value based on custon feature values.




## Acknowledgements

 - [ML Cheatsheet 🔖](https://s3.amazonaws.com/assets.datacamp.com/email/other/ML+Cheat+Sheet_2.pdf)
 - [SA Methods (including ISAMI guides) 📗](http://goto/samethods)
 - Special thanks to _CK_ for his amazing ideas 🧑 (future is Digital!)

## Authors

- [@Arslan Badr 🦁](https://www.github.com/octokatherine)


## Contributing

Contributions are always welcome - please get in touch with me!

Goto `goto/pioneer` to pitch your automation ideas!

Please adhere to this project's `code of conduct`.


## FAQ

#### What is Lasso Regression!?

A simple search on google will yeild answers, but here - [click me to learn more](https://www.mygreatlearning.com/blog/understanding-of-lasso-regression/#:~:text=Lasso%20regression%20is%20a%20regularization,i.e.%20models%20with%20fewer%20parameters)

#### When streamlit works fine, why do we need to package this with a Next.JS FE?

Because:

 - I wish to continue to develop to the point where I can 'deliver' E2E solutions quickly and efficently.
 - Life is not worth living without challenges.
 - It's a much nicer UX.

#### Do the predictions come with any guarentees??

No. If you're looking to predict the RFs based on a given criteria for eg - this is meant to provide a general 'feeling' of what it should be, in some cases with upto 98% accuracy! While it will be capable of this in the next 5-7 years, the answer is sadly no today, keeping most of us employed.

