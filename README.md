# 🌺Flower Plant Species Image Classification Using Teachable Machine

## 📌 Project Overview

This project focuses on developing an **Image Classification Model** using **Google Teachable Machine** to identify and classify 20 different ornamental and flowering plant species.

The purpose of this project is to:
- Organize a large image dataset for machine learning
- Train an image classification model
- Evaluate model performance using accuracy metrics and confusion matrices
- Test the model using real-time and uploaded images
- Export and document the trained machine learning model using GitHub

The dataset contains more than **5,000 plant images**, with at least **250 images per species**.

---

# 🌱 Plant Species Section

## 1. Anthurium
- **Scientific Name:** *Anthurium andraeanum*
- **Description:** A tropical ornamental plant known for its glossy leaves and colorful flowers.

![Anthurium](<img width="278" height="280" alt="anthurium" src="https://github.com/user-attachments/assets/e542210f-fe2f-43ff-9236-1a807eb36125" />
)

---

## 2. Cereus
- **Scientific Name:** *Cereus repandus*
- **Description:** A cactus species commonly grown as an ornamental desert plant.

![Cereus](images/plants/cereus.jpg)

---

## 3. Catleya
- **Scientific Name:** *Cattleya orchid*
- **Description:** A popular orchid species with large fragrant flowers.

![Catleya](images/plants/catleya.jpg)

---

## 4. Euphorbia
- **Scientific Name:** *Euphorbia milii*
- **Description:** A flowering succulent commonly known as Crown of Thorns.

![Euphorbia](images/plants/euphorbia.jpg)

---

## 5. Golden Duranta
- **Scientific Name:** *Duranta erecta*
- **Description:** A tropical shrub with golden-yellow leaves used in landscaping.

![Golden Duranta](images/plants/goldenduranta.jpg)

---

## 6. Vanda
- **Scientific Name:** *Vanda coerulea*
- **Description:** A colorful orchid species known for long-lasting flowers.

![Vanda](images/plants/vanda.jpg)

---

## 7. Million Flower
- **Scientific Name:** *Cuphea hyssopifolia*
- **Description:** A flowering shrub producing many tiny purple flowers.

![Million Flower](images/plants/millionflower.jpg)

---

## 8. Dancing Lady
- **Scientific Name:** *Oncidium orchid*
- **Description:** An orchid species whose flowers resemble dancing figures.

![Dancing Lady](images/plants/dancinglady.jpg)

---

## 9. Calendula
- **Scientific Name:** *Calendula officinalis*
- **Description:** A medicinal flowering plant with orange or yellow petals.

![Calendula](images/plants/calendula.jpg)

---

## 10. Cadena de Amor
- **Scientific Name:** *Antigonon leptopus*
- **Description:** A climbing vine plant with pink clustered flowers.

![Cadena de Amor](images/plants/cadenadeamor.jpg)

---

## 11. Dendrobium
- **Scientific Name:** *Dendrobium orchid*
- **Description:** A diverse orchid genus with beautiful blossoms.

![Dendrobium](images/plants/dendrobium.jpg)

---

## 12. Bombils
- **Scientific Name:** *Mirabilis jalapa*
- **Description:** A flowering ornamental plant also called Four O’Clock flower.

![Bombils](images/plants/bombils.jpg)

---

## 13. Allamanda
- **Scientific Name:** *Allamanda cathartica*
- **Description:** A tropical flowering plant with yellow trumpet flowers.

![Allamanda](images/plants/allamanda.jpg)

---

## 14. Rosal
- **Scientific Name:** *Gardenia jasminoides*
- **Description:** A fragrant flowering shrub with white blossoms.

![Rosal](images/plants/rosal.jpg)

---

## 15. Tiger Orchid
- **Scientific Name:** *Grammatophyllum speciosum*
- **Description:** One of the largest orchid species with tiger-patterned flowers.

![Tiger Orchid](images/plants/tigerorchid.jpg)

---

## 16. Phalaenopsis
- **Scientific Name:** *Phalaenopsis orchid*
- **Description:** Commonly known as the Moth Orchid.

![Phalaenopsis](images/plants/phalaenopsis.jpg)

---

## 17. Miniature Roses
- **Scientific Name:** *Rosa chinensis minima*
- **Description:** Small ornamental rose varieties grown in gardens.

![Miniature Roses](images/plants/miniatureroses.jpg)

---

## 18. Lobster Claw
- **Scientific Name:** *Heliconia rostrata*
- **Description:** A tropical plant with hanging claw-shaped flowers.

![Lobster Claw](images/plants/lobsterclaw.jpg)

---

## 19. Lerio
- **Scientific Name:** *Liriope muscari*
- **Description:** A grass-like ornamental flowering plant.

![Lerio](images/plants/lerio.jpg)

---

## 20. Firecracker
- **Scientific Name:** *Russelia equisetiformis*
- **Description:** A flowering shrub with red tubular flowers resembling fireworks.

![Firecracker](images/plants/firecracker.jpg)

---

# ⚙️ Model Training Details

The model was trained using **Google Teachable Machine**.

| Parameter | Value |
|---|---|
| Epochs | 50 |
| Batch Size | 16 |
| Learning Rate | 0.001 |
| Number of Classes | 20 |
| Images per Class | 250+ |
| Total Dataset Images | 5,000+ |

---

## 📸 Training Settings Screenshot

![Training Settings](images/training/training_settings.png)

---

## 📝 Training Parameter Explanation

### Epochs (50)
The model was trained for 50 epochs to allow it to learn plant features more effectively without excessive overfitting.

### Batch Size (16)
A batch size of 16 provided stable learning and balanced memory usage during training.

### Learning Rate (0.001)
A learning rate of 0.001 allowed the model to gradually optimize weights and improve prediction accuracy.

---

# 📊 Model Evaluation

## 📸 Confusion Matrix

![Confusion Matrix](images/evaluation/confusion_matrix.png)

---

## 📸 Accuracy Per Class

![Accuracy Per Class](images/evaluation/accuracy_per_class.png)

---

## 📸 Overall Model Accuracy

![Overall Accuracy](images/evaluation/overall_accuracy.png)

---

# 🧪 Model Testing

The trained model was tested using uploaded images and real-time camera testing inside the Preview section of Teachable Machine.

## 📸 Test 1
![Test1](images/testing/test1.png)

## 📸 Test 2
![Test2](images/testing/test2.png)

## 📸 Test 3
![Test3](images/testing/test3.png)

## 📸 Test 4
![Test4](images/testing/test4.png)

## 📸 Test 5
![Test5](images/testing/test5.png)

## 📸 Test 6
![Test6](images/testing/test6.png)

## 📸 Test 7
![Test7](images/testing/test7.png)

## 📸 Test 8
![Test8](images/testing/test8.png)

## 📸 Test 9
![Test9](images/testing/test9.png)

## 📸 Test 10
![Test10](images/testing/test10.png)

---

# 📦 Exported Model

The trained model was exported from Google Teachable Machine in the following formats:

- TensorFlow
- TensorFlow Lite
- Web Model

The exported model files are included in this repository.

---

# 📁 Repository Contents

This repository contains:

- README.md
- Exported Teachable Machine model files
- Dataset screenshots
- Training screenshots
- Under-the-hood evaluation screenshots
- Preview testing screenshots

---

# 💭 Reflection Questions

## 1. How did the number of images per class affect your model’s accuracy?

Having more images per class improved the model’s accuracy because the model was exposed to different lighting conditions, angles, and plant appearances.

---

## 2. Which plant species were most commonly misclassified and why?

Some orchid species such as Vanda, Dendrobium, and Phalaenopsis were occasionally misclassified because they share similar flower shapes and colors.

---

## 3. How did changing the epochs, batch size, or learning rate affect the training results?

Increasing the epochs improved accuracy but also increased training time. The batch size affected training stability, while the learning rate controlled how quickly the model learned patterns from the dataset.

---

## 4. What challenges did you encounter during dataset collection and labeling?

The biggest challenges included collecting high-quality images, avoiding duplicate images, organizing files correctly, and ensuring all plant classes had balanced image counts.

---

## 5. If you were to improve your model, what specific changes would you make and why?

I would improve the model by adding more training images, improving image quality, removing noisy backgrounds, and collecting more samples under different environmental conditions to increase prediction accuracy.

---

# 🛠️ Tools and Technologies Used

- Google Teachable Machine
- TensorFlow
- GitHub
- Google Drive
- Markdown

---

# 👨‍💻 Author

**Name:** Your Name Here  
**Course & Section:** Your Course Here  
**Activity:** Laboratory Work 2-A — Plant Species Image Classification Using Teachable Machine  

[##ImageDataset](https://drive.google.com/drive/folders/1SGSxJlWoKGafAp_QliqY6Tgj1oEu-0pL?usp=drive_link)

