<img src="https://capsule-render.vercel.app/api?type=waving&color=006600&height=150&section=header" />

# Master-Thesis
## It is a research paper in the field of digital healthcare.

- ### Summary
Development of Medical AI Based on YOLO Model to Support Surgical Plan for Bone Fracture Area  
뼈 골절 부위 수술 계획 지원을 위한 YOLO 모델 기반의 의료 AI 개발

- ### Background  
Utilizing artificial intelligence (AI) offers valuable support in fracture detection and diagnostic decision-making. ‘You only look once’ (YOLO) v4 proves to be a suitable model for identifying bone fractures in medical images. As YOLO v4 detects fractured regions slide by slide on two-dimensions (2D) computed tomography (CT) images using bounding boxes, multiple boxes across various slides intuitively delineate the fractured area on 3D reconstructed bone images. This process enhances the comprehensibility of the fractured region within the bone structure.

- ### Method  
Total individual images for training were 280,000 CT images via data augmentation. Preprocessed data is fed into the backbone from the input. The data accepted into the backbone is diversified through DarkNet-53 (CSPDarkNet-53). Extract feature maps using Spatial Pyramid Pooling (SPP) and Path Aggregation Network (PAN) in the neck part. The head part aggregates and generates the final output. all bounding boxes by the YOLO v4 were mapped onto the 3D reconstructed bone images after being resized to match the same region as shown in the 2D CT images. Individually, the YOLO v4 based AI model was evaluated through precision-recall curve (PR Curve) 

- ### Results  
Our proposed system facilitated an intuitive display of the fractured area through a distinctive red mask overlaid on the 3D reconstructed bone images. All PR curves were acquired by using dataset for tibia and elbow, respectively. The high average precisions (> 0.60) were reported 0.71, and 0.81 from PR curve of tibia and PR curve of elbow, respectively. IoU were calculated as 0.6327 (tibia) and 0.6638(elbow). 

- ### Conclusion  
We verified the viability and effectiveness of integrating YOLO v4 based fracture detection with intuitive visualization and 3D reconstructed bone images derived from CT scans. When utilized by orthopedic surgeons in real clinical scenarios, this AIpowered 3D diagnosis support system enables quick and accurate trauma diagnosis, making the process effortless regardless of the surgeons' experience or expertise level. 

- ### Keywords  
YOLO v4, Fracture Detection, Deep learning, Three dimensional (3D) Reconstructed image, Computed Tomography (CT) images, Artificial intelligence (AI), Digital Imaging and Communications in Medicine (DICOM), Machine learning, Tibia, Elbow 

- ### SW environment
-. matlab (version - R2023a)  
https://kr.mathworks.com

- ### Object detection model
-. YOLO (version - v4)  
https://github.com/AlexeyAB/darknet

- ### Thesis
https://dcollection.yonsei.ac.kr/srch/srchDetail/000000553261

<img src="https://capsule-render.vercel.app/api?type=waving&color=006600&height=150&section=footer" />
