# OKCupid Profile Predictions

GITHUB can be buggy with Jupyter files, if it renders green or fails to render at all, please refresh and try again.

This was a Codecademy project with no direction or instructions, just data from OK Cupid. As an inititial step, I created values in an attempt to capture a person's relationship with smoking, offspring, income, alcohol, drugs, education, religion, and pet ownership. I turned several columns into integers, then scaled them, and then used features as labels to predict another features. [The data itself had only a binary gender classification and had limited orientation classification. For a more inclusive model, I would suggest additional classifications.] I then used kmeans to cluster the data. I found that it needed at least 100 clusters before it started to really group different profiles together on features such as educational levels and whether the person wanted children.

