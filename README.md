# recolour_image
Recover missing Colour information (one missing channel) from an RGB image

using the power of machine learning, this repo tends to recover colour from greyscale image. I will try neural network, but as i plot it, it shows towards a regression problem, polynomial to be precise. In my experience, the NN does not work pretty well with linear problem like this but since we need to figure out a lot of data, that worth a try. But if the result is not getting better (currently stuck in 12% acc), i will consider changeing to polynomial regression.


Steps of this fun research: recover greeen channel, recover two channels, then entirely convert grey to rgb from feature extractions and millions of datasets of object and their colour
I will try to mimic child's behavior with their colouring book... They will fill objects with colour as they see it in the real world (in my model, datasets of objects) Or their
parent advices
