##Logs 

Train on 60000 samples, validate on 10000 samples
Epoch 1/16

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 10s 162us/step - loss: 0.0972 - acc: 0.9545 - val_loss: 0.0263 - val_acc: 0.9921
Epoch 2/16

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0904 - acc: 0.9572 - val_loss: 0.0274 - val_acc: 0.9924
Epoch 3/16

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 7s 122us/step - loss: 0.0860 - acc: 0.9580 - val_loss: 0.0239 - val_acc: 0.9930
Epoch 4/16

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 7s 123us/step - loss: 0.0843 - acc: 0.9593 - val_loss: 0.0232 - val_acc: 0.9933
Epoch 5/16

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 7s 119us/step - loss: 0.0848 - acc: 0.9574 - val_loss: 0.0223 - val_acc: 0.9936
Epoch 6/16

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0819 - acc: 0.9576 - val_loss: 0.0234 - val_acc: 0.9932
Epoch 7/16

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0789 - acc: 0.9599 - val_loss: 0.0197 - val_acc: 0.9944
Epoch 8/16

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0791 - acc: 0.9589 - val_loss: 0.0178 - val_acc: 0.9950
Epoch 9/16

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0813 - acc: 0.9585 - val_loss: 0.0195 - val_acc: 0.9947
Epoch 10/16

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0768 - acc: 0.9592 - val_loss: 0.0194 - val_acc: 0.9948
Epoch 11/16

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0757 - acc: 0.9612 - val_loss: 0.0192 - val_acc: 0.9942
Epoch 12/16

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0755 - acc: 0.9607 - val_loss: 0.0171 - val_acc: 0.9951
Epoch 13/16

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0764 - acc: 0.9592 - val_loss: 0.0178 - val_acc: 0.9952
Epoch 14/16

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0754 - acc: 0.9601 - val_loss: 0.0181 - val_acc: 0.9947
Epoch 15/16

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0756 - acc: 0.9602 - val_loss: 0.0195 - val_acc: 0.9946
Epoch 16/16

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0749 - acc: 0.9608 - val_loss: 0.0171 - val_acc: 0.9954

<keras.callbacks.History at 0x7fe9758fe4a8>





## Reault of model.evaluate (X_test, Y_test, verbose=0)
[0.01713531746226945, 0.9954]

##Score 0.9954


### To achieve the desired results maxpooling was used and it resuced it to 2X2 thus by maintaing the parameters under 15k and giving performance of 0.9954
