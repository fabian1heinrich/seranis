# SeRANIS Start-Up-Challenge
this repository hosts all my (upcomming) code for my application to the SeRANIS x founders challenge

## idea paper
[idea paper](seranis.pdf)

## master's thesis
[master's thesis](https://raw.githubusercontent.com/fabian1heinrich/LearningCommunicationChannelsWithAutoencoders/main/thesis.pdf)

## reference to my master's thesis
most of points we want to review have already been brought up in my master's thesis however we want to use this projects to dig more into the specific parts and derive more feasible results that can be brought into production \
furthermore, we will focus on publishing certain issues
## issues to be examined
### modulation
we want to setup an end2end autoencoder model that uses a certain channel model. in the following we want to investigate different constellation diagrams that can be obtain with regard to channel and modulations parameters as linearity, noise and orders
### coding scheme
in the next step we want to add coding scheme on top of your modulation model
### channel models
at the end we want to use data to use models estimating channel parameters in a more dynamic way that can adapt online during training. in course of my master's thesis we already came up with GANs that do a pretty good job predicting the signal after it has been affected by the channel (eg with non-linearities etc) though we want to revisit this topic since our experience within the ml field has been increasing massively sine last year
