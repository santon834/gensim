Training loss is now calculated when running Cython dbow neg and get_latest_training_loss() prints it instead of returning 0.
==================================

Example:

model = Doc2Vec(compute_loss=True, ...)

model.train(...)

model.get_latest_training_loss()

*special thanks to Jonathan Quach and Bob Xiao
