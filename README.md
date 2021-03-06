# Face_Recognition

[In this diploma work](https://github.com/HannaDGit/Face_Recognition/blob/master/dnn_Rozpoznawanie_twarzy_z_wykorzystaniem_wsp%C3%B3%C5%82czesnych_architektur_g%C5%82%C4%99bokich_sieci_neuronowych.pdf)
we presented the main challenges of face recognition and verification
tasks and two examples how they had been met by [state-of-the-art Deep Neural Networks](https://github.com/HannaDGit/Face_Recognition/blob/master/fin_7_Appendix_1_Models_Validation.ipynb). We
presented two architectures: [MobileFaceNet](https://github.com/HannaDGit/Face_Recognition/blob/master/fin_8_Appendix_2_Transfer_Learning_MobileFaceNet.ipynb) and [Light CNN-9](https://github.com/HannaDGit/Face_Recognition/blob/master/fin_9_Appendix_2_Transfer_Learning_LightCNN.ipynb). The models have been chosen
due to their 'light' architectures and few parameters to train. Transfer learning has been applied.
We changed the last layers of the models in order to create face embedding as an output. Face
embedding layers have been trained with chosen deep learning metrics. Our approach has been
tested using evaluation metrics on LWF database as well as gallery of personal photos. We
achieved improvements in some areas what was presented in details in this work.
All notebooks were created in Colab with table of contents.
