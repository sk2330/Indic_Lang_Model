#  Text Normalisation Model- Task



-->Trained this model in Tamil and Malayalam language.

-->Base model: Used sarvamai/sarvam-1

-->The dataset used for training this was used for hugging face
Dataset link:
https://huggingface.co/datasets/ai4bharat/IndicSentenceSummarization/viewer/ml - Malayalam
https://huggingface.co/datasets/ai4bharat/IndicSentenceSummarization/viewer/ta - Tamil

-->The dataset split is:
Train:test:validation = 8:1:1

-->Entities were handled and the fuctions were passed onto the dataset

-->In this dataset columns "id" and "url" were dropped and uploaded into hugging face

-->Processed dataset link: https://huggingface.co/datasets/Saikrishna2403/tamil_ml_text_normalization

-->The data is then used to train the sarvamai model.


-->Frameworks used: Hugging Face, transformers, indic-nlp-library, indic-numtowords, regex
indic-numtowords- this library is especially for indic languages to convert numbers to words



-->Hyperparameters: Learning rate, per_device_train_batch_size, per_device_eval_batch_size, weight_decay,num_train_epochs

Learning rate controls how much a model adjusts its parameters during each training iteration, essentially determining the step size taken towards minimizing the loss function.

-->The per_device_train_batch_size is used as the initial batch size to start off with.

-->Weight decay is a regularization method to make models generalize better by learning smoother functions.







