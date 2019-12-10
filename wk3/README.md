Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
separable_conv2d_1 (Separabl (None, 32, 32, 48)        219       
_________________________________________________________________
batch_normalization_1 (Batch (None, 32, 32, 48)        192       
_________________________________________________________________
dropout_1 (Dropout)          (None, 32, 32, 48)        0         
_________________________________________________________________
separable_conv2d_2 (Separabl (None, 30, 30, 48)        2784      
_________________________________________________________________
batch_normalization_2 (Batch (None, 30, 30, 48)        192       
_________________________________________________________________
dropout_2 (Dropout)          (None, 30, 30, 48)        0         
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 15, 15, 48)        0         
_________________________________________________________________
batch_normalization_3 (Batch (None, 15, 15, 48)        192       
_________________________________________________________________
dropout_3 (Dropout)          (None, 15, 15, 48)        0         
_________________________________________________________________
separable_conv2d_3 (Separabl (None, 15, 15, 96)        5136      
_________________________________________________________________
batch_normalization_4 (Batch (None, 15, 15, 96)        384       
_________________________________________________________________
dropout_4 (Dropout)          (None, 15, 15, 96)        0         
_________________________________________________________________
separable_conv2d_4 (Separabl (None, 13, 13, 96)        10176     
_________________________________________________________________
batch_normalization_5 (Batch (None, 13, 13, 96)        384       
_________________________________________________________________
dropout_5 (Dropout)          (None, 13, 13, 96)        0         
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 6, 6, 96)          0         
_________________________________________________________________
batch_normalization_6 (Batch (None, 6, 6, 96)          384       
_________________________________________________________________
dropout_6 (Dropout)          (None, 6, 6, 96)          0         
_________________________________________________________________
separable_conv2d_5 (Separabl (None, 6, 6, 192)         19488     
_________________________________________________________________
batch_normalization_7 (Batch (None, 6, 6, 192)         768       
_________________________________________________________________
dropout_7 (Dropout)          (None, 6, 6, 192)         0         
_________________________________________________________________
separable_conv2d_6 (Separabl (None, 4, 4, 192)         38784     
_________________________________________________________________
batch_normalization_8 (Batch (None, 4, 4, 192)         768       
_________________________________________________________________
dropout_8 (Dropout)          (None, 4, 4, 192)         0         
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 2, 2, 192)         0         
_________________________________________________________________
batch_normalization_9 (Batch (None, 2, 2, 192)         768       
_________________________________________________________________
dropout_9 (Dropout)          (None, 2, 2, 192)         0         
_________________________________________________________________
flatten_1 (Flatten)          (None, 768)               0         
_________________________________________________________________
dense_1 (Dense)              (None, 10)                7690      
=================================================================
Total params: 88,309
Trainable params: 86,293
Non-trainable params: 2,016
____________________________

Train on 50000 samples, validate on 10000 samples
Epoch 1/50

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
50000/50000 [==============================] - 24s 476us/step - loss: 0.7325 - acc: 0.7643 - val_loss: 0.6596 - val_acc: 0.7800
Epoch 2/50

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
50000/50000 [==============================] - 23s 458us/step - loss: 0.4444 - acc: 0.8431 - val_loss: 0.6759 - val_acc: 0.7790
Epoch 3/50

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
50000/50000 [==============================] - 23s 468us/step - loss: 0.3845 - acc: 0.8620 - val_loss: 0.6386 - val_acc: 0.7985
Epoch 4/50

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
50000/50000 [==============================] - 23s 468us/step - loss: 0.3408 - acc: 0.8774 - val_loss: 0.6142 - val_acc: 0.8026
Epoch 5/50

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
50000/50000 [==============================] - 23s 456us/step - loss: 0.3020 - acc: 0.8936 - val_loss: 0.6165 - val_acc: 0.8099
Epoch 6/50

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
50000/50000 [==============================] - 23s 455us/step - loss: 0.2747 - acc: 0.9001 - val_loss: 0.6261 - val_acc: 0.8046
Epoch 7/50

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
50000/50000 [==============================] - 23s 453us/step - loss: 0.2518 - acc: 0.9100 - val_loss: 0.6338 - val_acc: 0.8089
Epoch 8/50

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
50000/50000 [==============================] - 23s 454us/step - loss: 0.2276 - acc: 0.9186 - val_loss: 0.6408 - val_acc: 0.8076
Epoch 9/50

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
50000/50000 [==============================] - 23s 453us/step - loss: 0.2127 - acc: 0.9231 - val_loss: 0.6401 - val_acc: 0.8045
Epoch 10/50

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
50000/50000 [==============================] - 23s 453us/step - loss: 0.2004 - acc: 0.9273 - val_loss: 0.6357 - val_acc: 0.8095
Epoch 11/50

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
50000/50000 [==============================] - 23s 452us/step - loss: 0.1873 - acc: 0.9316 - val_loss: 0.6535 - val_acc: 0.8119
Epoch 12/50

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
50000/50000 [==============================] - 23s 452us/step - loss: 0.1758 - acc: 0.9362 - val_loss: 0.6717 - val_acc: 0.8091
Epoch 13/50

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
50000/50000 [==============================] - 23s 452us/step - loss: 0.1692 - acc: 0.9386 - val_loss: 0.6817 - val_acc: 0.8106
Epoch 14/50

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
50000/50000 [==============================] - 23s 452us/step - loss: 0.1630 - acc: 0.9413 - val_loss: 0.6750 - val_acc: 0.8096
Epoch 15/50

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1556 - acc: 0.9434 - val_loss: 0.6711 - val_acc: 0.8179
Epoch 16/50

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
50000/50000 [==============================] - 23s 455us/step - loss: 0.1528 - acc: 0.9446 - val_loss: 0.6881 - val_acc: 0.8160
Epoch 17/50

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
50000/50000 [==============================] - 23s 455us/step - loss: 0.1401 - acc: 0.9493 - val_loss: 0.6736 - val_acc: 0.8146
Epoch 18/50

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
50000/50000 [==============================] - 24s 470us/step - loss: 0.1422 - acc: 0.9474 - val_loss: 0.6841 - val_acc: 0.8178
Epoch 19/50

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
50000/50000 [==============================] - 23s 459us/step - loss: 0.1344 - acc: 0.9511 - val_loss: 0.7006 - val_acc: 0.8140
Epoch 20/50

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
50000/50000 [==============================] - 23s 455us/step - loss: 0.1296 - acc: 0.9531 - val_loss: 0.7027 - val_acc: 0.8143
Epoch 21/50

Epoch 00021: LearningRateScheduler setting learning rate to 0.0004065041.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1233 - acc: 0.9554 - val_loss: 0.7044 - val_acc: 0.8198
Epoch 22/50

Epoch 00022: LearningRateScheduler setting learning rate to 0.000389661.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1238 - acc: 0.9557 - val_loss: 0.7005 - val_acc: 0.8154
Epoch 23/50

Epoch 00023: LearningRateScheduler setting learning rate to 0.0003741581.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1229 - acc: 0.9559 - val_loss: 0.7189 - val_acc: 0.8172
Epoch 24/50

Epoch 00024: LearningRateScheduler setting learning rate to 0.0003598417.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1178 - acc: 0.9574 - val_loss: 0.7236 - val_acc: 0.8155
Epoch 25/50

Epoch 00025: LearningRateScheduler setting learning rate to 0.0003465804.
50000/50000 [==============================] - 23s 451us/step - loss: 0.1160 - acc: 0.9583 - val_loss: 0.7352 - val_acc: 0.8124
Epoch 26/50

Epoch 00026: LearningRateScheduler setting learning rate to 0.0003342618.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1120 - acc: 0.9593 - val_loss: 0.7220 - val_acc: 0.8165
Epoch 27/50

Epoch 00027: LearningRateScheduler setting learning rate to 0.0003227889.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1078 - acc: 0.9606 - val_loss: 0.7288 - val_acc: 0.8161
Epoch 28/50

Epoch 00028: LearningRateScheduler setting learning rate to 0.0003120774.
50000/50000 [==============================] - 23s 453us/step - loss: 0.1072 - acc: 0.9618 - val_loss: 0.7174 - val_acc: 0.8192
Epoch 29/50

Epoch 00029: LearningRateScheduler setting learning rate to 0.000302054.
50000/50000 [==============================] - 23s 452us/step - loss: 0.1064 - acc: 0.9620 - val_loss: 0.7317 - val_acc: 0.8195
Epoch 30/50

Epoch 00030: LearningRateScheduler setting learning rate to 0.0002926544.
50000/50000 [==============================] - 23s 454us/step - loss: 0.1034 - acc: 0.9628 - val_loss: 0.7261 - val_acc: 0.8210
Epoch 31/50

Epoch 00031: LearningRateScheduler setting learning rate to 0.0002838221.
50000/50000 [==============================] - 23s 458us/step - loss: 0.1017 - acc: 0.9630 - val_loss: 0.7345 - val_acc: 0.8185
Epoch 32/50

Epoch 00032: LearningRateScheduler setting learning rate to 0.0002755074.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0999 - acc: 0.9640 - val_loss: 0.7359 - val_acc: 0.8200
Epoch 33/50

Epoch 00033: LearningRateScheduler setting learning rate to 0.000267666.
50000/50000 [==============================] - 23s 452us/step - loss: 0.0999 - acc: 0.9644 - val_loss: 0.7517 - val_acc: 0.8169
Epoch 34/50

Epoch 00034: LearningRateScheduler setting learning rate to 0.0002602585.
50000/50000 [==============================] - 23s 456us/step - loss: 0.0957 - acc: 0.9653 - val_loss: 0.7429 - val_acc: 0.8201
Epoch 35/50

Epoch 00035: LearningRateScheduler setting learning rate to 0.00025325.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0986 - acc: 0.9648 - val_loss: 0.7501 - val_acc: 0.8186
Epoch 36/50

Epoch 00036: LearningRateScheduler setting learning rate to 0.0002466091.
50000/50000 [==============================] - 23s 454us/step - loss: 0.0959 - acc: 0.9657 - val_loss: 0.7519 - val_acc: 0.8212
Epoch 37/50

Epoch 00037: LearningRateScheduler setting learning rate to 0.0002403076.
50000/50000 [==============================] - 23s 454us/step - loss: 0.0924 - acc: 0.9672 - val_loss: 0.7618 - val_acc: 0.8196
Epoch 38/50

Epoch 00038: LearningRateScheduler setting learning rate to 0.0002343201.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0903 - acc: 0.9677 - val_loss: 0.7520 - val_acc: 0.8195
Epoch 39/50

Epoch 00039: LearningRateScheduler setting learning rate to 0.0002286237.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0915 - acc: 0.9666 - val_loss: 0.7585 - val_acc: 0.8216
Epoch 40/50

Epoch 00040: LearningRateScheduler setting learning rate to 0.0002231977.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0908 - acc: 0.9680 - val_loss: 0.7572 - val_acc: 0.8211
Epoch 41/50

Epoch 00041: LearningRateScheduler setting learning rate to 0.0002180233.
50000/50000 [==============================] - 23s 451us/step - loss: 0.0889 - acc: 0.9680 - val_loss: 0.7521 - val_acc: 0.8198
Epoch 42/50

Epoch 00042: LearningRateScheduler setting learning rate to 0.0002130833.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0891 - acc: 0.9680 - val_loss: 0.7718 - val_acc: 0.8174
Epoch 43/50

Epoch 00043: LearningRateScheduler setting learning rate to 0.0002083623.
50000/50000 [==============================] - 23s 452us/step - loss: 0.0862 - acc: 0.9690 - val_loss: 0.7598 - val_acc: 0.8203
Epoch 44/50

Epoch 00044: LearningRateScheduler setting learning rate to 0.0002038459.
50000/50000 [==============================] - 23s 452us/step - loss: 0.0874 - acc: 0.9685 - val_loss: 0.7689 - val_acc: 0.8171
Epoch 45/50

Epoch 00045: LearningRateScheduler setting learning rate to 0.0001995211.
50000/50000 [==============================] - 23s 456us/step - loss: 0.0874 - acc: 0.9690 - val_loss: 0.7652 - val_acc: 0.8204
Epoch 46/50

Epoch 00046: LearningRateScheduler setting learning rate to 0.0001953761.
50000/50000 [==============================] - 23s 452us/step - loss: 0.0864 - acc: 0.9695 - val_loss: 0.7765 - val_acc: 0.8218
Epoch 47/50

Epoch 00047: LearningRateScheduler setting learning rate to 0.0001913998.
50000/50000 [==============================] - 23s 452us/step - loss: 0.0829 - acc: 0.9705 - val_loss: 0.7737 - val_acc: 0.8216
Epoch 48/50

Epoch 00048: LearningRateScheduler setting learning rate to 0.0001875821.
50000/50000 [==============================] - 23s 453us/step - loss: 0.0832 - acc: 0.9702 - val_loss: 0.7793 - val_acc: 0.8194
Epoch 49/50

Epoch 00049: LearningRateScheduler setting learning rate to 0.0001839137.
50000/50000 [==============================] - 23s 451us/step - loss: 0.0799 - acc: 0.9716 - val_loss: 0.7736 - val_acc: 0.8228
Epoch 50/50

Epoch 00050: LearningRateScheduler setting learning rate to 0.000180386.
50000/50000 [==============================] - 23s 452us/step - loss: 0.0844 - acc: 0.9698 - val_loss: 0.7748 - val_acc: 0.8249
Model took 1137.34 seconds to train

Accuracy on test data is: 82.49