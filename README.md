# CCDM_Mendeley

This notebook evaluates our VGG‑16–based cervical cell classifier on the external Mendeley cervical cell image dataset. It:

Loads & preprocesses the Mendeley images (resizing, normalization, train/validation split).

Recreates the VGG‑16 pipeline (with our custom top layers) and loads the saved model.h5 weights.

Runs inference on the Mendeley test set, producing class predictions for each cell image.

Computes performance metrics—accuracy, precision, recall—and displays the confusion matrix to highlight how well the model generalizes.

Visualizes sample predictions, overlaying true vs. predicted labels on a handful of cell images.

The results confirm that our model achieves comparable accuracy (100%) on this independent dataset, demonstrating robust cross‐dataset generalizability.
