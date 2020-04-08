# BigData
OCR project

READ_ME

INSIDE MAIN FOLDER (NB: these have been divided into three separate maps on Github)

Maps
1.	Adv[anced]Im[a]g[e]Seg[mentation]
2.	AdvImgSegOut
3.	GreyScaleANDBinarization
4.	SimpleImgSeg
5.	SimpleImgSegOut
6.	SkewCorr[ection]
7.	SkewCorrOut
INFO: These maps contain the infiles and outfiles for the different methods. Including handmade transcriptions of the files used. More about ‘GreyScaleANDBinarization’ and ‘AdvImgSeg’ below.

Files
1.	Datasets Transcriptions
INFO: Contains all the human made transcriptions for all datasets in pdf format.
2.	RotatorGreyscale
3.	RotatorImgSegm
4.	RotatorSkewCorrection
INFO: These files perform automatic greyscale conversion, image segmentation, and skew correction over all the infiles in the maps.
5.	RotatorReading
INFO: This file automatically reads, measures the reading time, and calculates accuracy for all the in- or outfiles in the maps above.


INSIDE GreyscaleANDBinarization

Maps
1.	Bin[ary]OutCovers
2.	BinOutNoisy
3.	Covers
4.	Grey[scale]OutCovers
5.	NoisyData
INFO:These maps contain the infiles and outfiles for the different methods. Including handmade transcriptions of the files used.

Files
1.	BinVisualisation
INFO: This file calculates the average reading time and accuracy for every possible threshold (0-255) for binarization and plots them, using a specified dataset.


INSIDE AdvImgSeg

Maps
1.RandomForestFiles
INFO: Files used for the RF model and preprocessing.

Files
Two infiles and a transcriptions file.


INSIDE RandomForestFiles

Files
1.	Adjustment
INFO: Visually alterns the image using the label predictions
2.	Predict
INFO: Uses RF model to predict labels for new image
3.	Processing
INFO: Read pixel values of a file. Optionally, these can be labeled. Can be used to create training data or to get data of an image in order to make predictions using the ‘predict’ file.
4.	RandomForest
INFO: Fitting of the model
5.	RandomForestmodel
INFO: Contains the saved model














