# Detectron_2_web_application
This project is a web-based application that uses Detectron2 to detect and identify playing cards. Users can upload images containing playing cards, and the model will predict and display the cards with bounding boxes and labels.
Download the Detectron2 pretrained weights or use a custom model for playing card detection. For example:
wget https://dl.fbaipublicfiles.com/detectron2/COCO-InstanceSegmentation/mask_rcnn_R_50_FPN_3x/137849600/model_final_f10217.pkl
mv model_final_f10217.pkl model_final.pth
