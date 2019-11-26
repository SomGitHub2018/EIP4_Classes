_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_97 (Conv2D)           (None, 26, 26, 16)        160       
_________________________________________________________________
batch_normalization_85 (Batc (None, 26, 26, 16)        64        
_________________________________________________________________
dropout_85 (Dropout)         (None, 26, 26, 16)        0         
_________________________________________________________________
conv2d_98 (Conv2D)           (None, 24, 24, 12)        1740      
_________________________________________________________________
batch_normalization_86 (Batc (None, 24, 24, 12)        48        
_________________________________________________________________
dropout_86 (Dropout)         (None, 24, 24, 12)        0         
_________________________________________________________________
conv2d_99 (Conv2D)           (None, 24, 24, 12)        156       
_________________________________________________________________
max_pooling2d_13 (MaxPooling (None, 12, 12, 12)        0         
_________________________________________________________________
conv2d_100 (Conv2D)          (None, 10, 10, 12)        1308      
_________________________________________________________________
batch_normalization_87 (Batc (None, 10, 10, 12)        48        
_________________________________________________________________
dropout_87 (Dropout)         (None, 10, 10, 12)        0         
_________________________________________________________________
conv2d_101 (Conv2D)          (None, 8, 8, 16)          1744      
_________________________________________________________________
batch_normalization_88 (Batc (None, 8, 8, 16)          64        
_________________________________________________________________
dropout_88 (Dropout)         (None, 8, 8, 16)          0         
_________________________________________________________________
conv2d_102 (Conv2D)          (None, 6, 6, 16)          2320      
_________________________________________________________________
batch_normalization_89 (Batc (None, 6, 6, 16)          64        
_________________________________________________________________
dropout_89 (Dropout)         (None, 6, 6, 16)          0         
_________________________________________________________________
conv2d_103 (Conv2D)          (None, 4, 4, 16)          2320      
_________________________________________________________________
batch_normalization_90 (Batc (None, 4, 4, 16)          64        
_________________________________________________________________
dropout_90 (Dropout)         (None, 4, 4, 16)          0         
_________________________________________________________________
conv2d_104 (Conv2D)          (None, 1, 1, 10)          2570      
_________________________________________________________________
batch_normalization_91 (Batc (None, 1, 1, 10)          40        
_________________________________________________________________
dropout_91 (Dropout)         (None, 1, 1, 10)          0         
_________________________________________________________________
flatten_13 (Flatten)         (None, 10)                0         
_________________________________________________________________
activation_13 (Activation)   (None, 10)                0         
=================================================================
Total params: 12,710
Trainable params: 12,514
Non-trainable params: 196
_________________________________________________________________
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:36: UserWarning: Update your `Conv2D` call to the Keras 2 API: `Conv2D(10, (4, 4))`

================================================================================================================================
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 19s 320us/step - loss: 0.5154 - acc: 0.8559 - val_loss: 0.0968 - val_acc: 0.9809
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 11s 180us/step - loss: 0.2519 - acc: 0.9264 - val_loss: 0.0605 - val_acc: 0.9884
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 11s 186us/step - loss: 0.2000 - acc: 0.9392 - val_loss: 0.0480 - val_acc: 0.9887
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 11s 183us/step - loss: 0.1723 - acc: 0.9459 - val_loss: 0.0352 - val_acc: 0.9913
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 11s 183us/step - loss: 0.1530 - acc: 0.9489 - val_loss: 0.0310 - val_acc: 0.9925
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 11s 184us/step - loss: 0.1403 - acc: 0.9504 - val_loss: 0.0318 - val_acc: 0.9908
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 11s 187us/step - loss: 0.1324 - acc: 0.9520 - val_loss: 0.0274 - val_acc: 0.9940
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 11s 188us/step - loss: 0.1260 - acc: 0.9520 - val_loss: 0.0249 - val_acc: 0.9926
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 11s 188us/step - loss: 0.1206 - acc: 0.9537 - val_loss: 0.0260 - val_acc: 0.9919
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 11s 188us/step - loss: 0.1179 - acc: 0.9523 - val_loss: 0.0218 - val_acc: 0.9942
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 11s 187us/step - loss: 0.1106 - acc: 0.9550 - val_loss: 0.0227 - val_acc: 0.9938
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 11s 186us/step - loss: 0.1094 - acc: 0.9550 - val_loss: 0.0234 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 11s 184us/step - loss: 0.1047 - acc: 0.9562 - val_loss: 0.0248 - val_acc: 0.9930
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 11s 187us/step - loss: 0.1050 - acc: 0.9560 - val_loss: 0.0214 - val_acc: 0.9938
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 11s 185us/step - loss: 0.1006 - acc: 0.9570 - val_loss: 0.0209 - val_acc: 0.9940
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 11s 184us/step - loss: 0.1009 - acc: 0.9563 - val_loss: 0.0213 - val_acc: 0.9942
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 11s 183us/step - loss: 0.0970 - acc: 0.9579 - val_loss: 0.0206 - val_acc: 0.9946
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 11s 182us/step - loss: 0.0968 - acc: 0.9576 - val_loss: 0.0191 - val_acc: 0.9943
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 11s 184us/step - loss: 0.0961 - acc: 0.9570 - val_loss: 0.0191 - val_acc: 0.9948
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 11s 186us/step - loss: 0.0984 - acc: 0.9571 - val_loss: 0.0198 - val_acc: 0.9943
<keras.callbacks.History at 0x7f39b722def0>

================================================================================================================================
score = model.evaluate(X_test, Y_test, verbose=0)
print(score)

[0.019805287554708777, 0.9943]