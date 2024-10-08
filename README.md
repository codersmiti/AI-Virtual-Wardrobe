# AI-Virtual-Wardrobe
AI-Virtual Wardrobe leverages advanced computer vision and artificial intelligence techniques to revolutionize the virtual clothing try-on experience. The project allows users to virtually try on various clothing items and accessories with high accuracy and realism, transforming the fashion industry's approach to garment customization and personal style.

**Modules Implemented**
1. **Clothes Try-On Module**
**Models Explored**: IUV Model, Thin Plate Spline, VGG, Keypoint-Based Warping, SeiveNet, GMM & TOM.<br/>
**Best Model**: ACGPN Model - Achieved the highest realism and fit for virtual try-on.

![image](https://github.com/user-attachments/assets/ae6bcfe5-8e04-4687-ab1b-35fbf172b6c0)
![image](https://github.com/user-attachments/assets/0728cad9-65a0-48ac-8266-23f15a9619f6)


2. **Glasses Try-On Module**
**Model Used**: Face Detection: Haar cascade classifier.
Facial Landmark Detection: Haar cascade for eye detection.<br/>
**Approach**: Detects the user's face and eyes, then accurately places the glasses.

![image](https://github.com/user-attachments/assets/6dfd4fac-f69d-4576-9990-a5dce9855d98)

3. **Necklace Try-On Module**
**Model Used**:Facial Landmark Detection: Dlib shape predictor.<br/>
**Approach**:Detects facial landmarks, focusing on the neck region for realistic necklace placement.

![image](https://github.com/user-attachments/assets/33f11df4-5071-41fc-867d-45d7779085d5)

4. **Earring Try-On Module**
**Model Used**:Face and Ear Detection: Haar cascade classifiers for face and ear detection.<br/>
**Approach**:Detects face and ears, then places earrings accordingly for a perfect earring placement.

![image](https://github.com/user-attachments/assets/4650d994-2e5e-4b28-8c66-ecec75f5e156)

5. **Hairwig Try-On Module**
**Model Used**: UNet Architecture: Segments the face into five regions—hair, face, ears, neck, and shirt.
Facial Landmark Detection: Used on the segmented image to generate semantic maps.<br/>
**Approach**: The system overlaps the source hair with the target face, creating a difference mask to fill in the missing sections using the SDEdit method. A smooth transition is achieved by filling in these sections using the fast marching approach.

![image](https://github.com/user-attachments/assets/ef077882-2db4-4e1b-b056-2abdc515663c)

![image](https://github.com/user-attachments/assets/6dfec046-841c-46b2-9a49-711722ef6cc9)


6. **Lipstick Try-On Module**
**Model Used**: Lip Landmark Detection: Dlib shape predictor.
Lip Detection: Haar cascade classifier.<br/>
**Approach**: Detects lip region and applies different lipstick colors. The system then recommends various products based on the selected color

![image](https://github.com/user-attachments/assets/0d92432c-6323-4bb3-867b-c99ff0f0e168)

**Frontend**
**Flask Web App**

![image](https://github.com/user-attachments/assets/32f8d69c-1095-4121-b287-4526b18d7947)

**Home Page of Application**

![image](https://github.com/user-attachments/assets/e2449f31-e34e-4b7c-83d5-039beabe8ba2)

**Try On Page of Application**

![image](https://github.com/user-attachments/assets/503ac8af-6b90-4ac7-ac8f-0a488cd9259d)



