Explain what you do in your project
: First I decided the model as SVC, and modifide hyper parameters
Explain the training dataset
: I just used datasets of brain_tumor which I received, and by the ratio of 7:3, split data as train : test
Explain the algorithm you choose
: I choosed SVC, first it's quite familiar to me probably because of similarity to linear regression, and
also with many trials, average accuracy and stability of SVC is trustable.
Explain hyper-parameter of the function
: kernel = 'poly' , C = 2.5, degree = 5, coef0 = 2.6, probability = True, break_ties = True
I think 'linear' form is inappropriate, so I decide 'poly' as familiar one, and decide C as 2.5 and coef0 with many trials and errors. degree needed to be moderate not extreme, so I think 5 is proper. 
