# Laboratory-Work-2-A-Plant-Species-Image-Classification
# A. Project Overview

## Brief Description
This project develops an **image classification system** for **tropical fruits**. It uses a machine learning model to identify fruits from images based on color, shape, and texture.

## Purpose
The model aims to **automatically recognize tropical fruits**, help users identify them quickly, and showcase the application of AI in agriculture.
# B. Plant Species Section


| Image | Common Name | Scientific Name | Description |
|-------|-------------|----------------|-------------|
| <img src="https://www.shutterstock.com/image-photo/red-apple-isolated-on-white-600nw-1727544364.jpg" width="80"> | Apple | Malus domestica | Popular fruit with sweet taste, crisp texture, and high in fiber. |
| <img src="https://st.depositphotos.com/1007373/1690/i/450/depositphotos_16900589-stock-photo-mango-fruits-on-the-local.jpg" width="80"> | Mango | Mangifera indica | Sweet tropical fruit rich in vitamins A and C. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Banana.png" width="80"> | Banana | Musa spp. | Soft, sweet fruit commonly eaten fresh or in desserts. |
| <img src="https://toptropicals.com/pics/garden/23/papaya-waimanalo-IMG_20230914_135541290.jpg" width="80"> | Papaya | Carica papaya | Orange-fleshed tropical fruit, rich in digestive enzymes and vitamins. |
| <img src="https://png.pngtree.com/png-clipart/20230510/original/pngtree-fresh-green-guava-fruit-png-image_9156651.png" width="80"> | Guava | Psidium guajava | Green tropical fruit with sweet or tangy taste, high in vitamin C. |
| <img src="https://del.h-cdn.co/assets/16/18/980x490/landscape-1462301405-pineapple-horizontal.jpg" width="80"> | Pineapple | Ananas comosus | Juicy tropical fruit with spiky skin and sweet-tart flavor. |
| <img src="https://thumbs.dreamstime.com/b/fresh-rambutan-green-leaf-group-bright-red-123732371.jpg" width="80"> | Rambutan | Nephelium lappaceum | Small tropical fruit with hairy red skin and sweet, juicy flesh. |
| <img src="https://www.rappler.com/tachyon/2023/04/shutterstock-durian.jpg?resize=1920%2C1080&zoom=1" width="80"> | Durian | Durio spp. | Large fruit known as the "king of fruits" with strong aroma and creamy flesh. |
| <img src="https://healthyfamilyproject.com/wp-content/uploads/2020/05/Dragonfruit-background.jpg" width="80"> | Dragon Fruit | Hylocereus spp. | Bright pink fruit with white flesh and black seeds, mildly sweet. |
| <img src="https://i.etsystatic.com/44761539/r/il/489d77/5941560776/il_600x600.5941560776_3edz.jpg" width="80"> | Star Fruit | Averrhoa carambola | Yellow-green fruit with star-shaped slices, tangy and crisp. |
| <img src="https://morningchores.com/wp-content/uploads/2020/11/Growing-breadfruit.jpg" width="80"> | Breadfruit | Artocarpus altilis | Large starchy fruit often cooked and eaten like potatoes. |
| <img src="https://images.healthshots.com/healthshots/en/uploads/2024/04/04153309/avocado-1.jpg" width="80"> | Avocado | Persea americana | Creamy green fruit high in healthy fats, used in salads and spreads. |
| <img src="https://eskipaper.com/images/pomegranate-fruit-1.jpg" width="80"> | Pomegranate | Punica granatum | Red fruit with juicy seeds rich in antioxidants and vitamin C. |
| <img src="https://www.mtfruit.com/wp-content/uploads/2020/07/Frozen-Soursop-600x600.jpg" width="80"> | Soursop | Annona muricata | Tropical fruit with spiky green skin and sweet-sour white flesh. |
| <img src="https://www.motionfitnessbali.com/wp-content/uploads/2016/02/mangosteen.jpg" width="80"> | Mangosteen | Garcinia mangostana | Small round fruit with thick purple rind and juicy sweet-white segments. |
| <img src="https://img.freepik.com/premium-photo/sapodilla-tree-with-young-fruit-green-leaves-sapodilla-fruit-garden_653449-3913.jpg?w=2000" width="80"> | Sapodilla | Manilkara zapota | Brown-skinned fruit with sweet, grainy-textured flesh. |
| <img src="https://cdn.britannica.com/95/126995-050-101B8B8D/Sweetsop.jpg" width="80"> | Custard Apple | Annona squamosa | Sweet, creamy fruit with segmented flesh, often eaten fresh. |
| <img src="https://images.wisegeek.com/lychee.jpg" width="80"> | Lychee | Litchi chinensis | Small, round fruit with rough red skin and juicy translucent flesh. |

# C. Model Training Details

<img width="226" height="484" alt="image" src="https://github.com/user-attachments/assets/c57c8743-b0e0-4ee8-bccc-bf3cb60a6972" />


### Why I chose these values:

* **Epochs (50):** An epoch represents one full cycle through the training dataset. I chose **50 epochs** to give the model enough time to learn and refine its recognition of specific fruit textures (like the spikes on a Durian or the ridges of a Starfruit). This number is high enough for high accuracy but low enough to prevent "overfitting," where the model simply memorizes the images.

* **Batch Size (16):** The batch size determines how many images are analyzed before the model updates its internal parameters. A **batch size of 16** provides a good balance between training speed and memory usage, ensuring the browser remains stable while the model learns effectively from small groups of data.

* **Learning Rate (0.001):** The learning rate is the "step size" the model takes while searching for the most accurate results. I used **0.001** because it is a standard, reliable rate that allows the model to converge on the correct answers steadily without skipping over the optimal patterns.
# D. Model Evaluation
  <img width="398" height="600" alt="image" src="https://github.com/user-attachments/assets/be307993-1fbd-4eb7-90cf-e996be4c73e7" />

 
## Fruit Classification Results

| Image | Fruit Name |
|:-----:|:-----------|
| <img src="https://github.com/user-attachments/assets/a93e99a5-da29-474f-b55e-76faecb06b8d" width="250" /> | Sapodilla |
| <img src="https://github.com/user-attachments/assets/f6ee2b51-7c37-465d-a21c-aa53b53ea996" width="250" /> | Starfruit |
| <img src="https://github.com/user-attachments/assets/83d2ec5c-06a2-4806-9713-5169ad96ea4a" width="250" /> | Durian |
| <img src="https://github.com/user-attachments/assets/8558696c-46dd-4d5b-9f4e-f89d7295eff8" width="250" /> | Pineapple |
| <img src="https://github.com/user-attachments/assets/b85ff287-37ed-4d17-9b5e-65dc89ce384c" width="250" /> | Papaya |
| <img src="https://github.com/user-attachments/assets/3c8b3f18-7be8-4bf5-a5cd-903543e7891c" width="250" /> | Apple |
| <img src="https://github.com/user-attachments/assets/519a7869-2b72-4ca5-9c18-60e77144da4e" width="250" /> | Rambutan |
| <img src="https://github.com/user-attachments/assets/9d34d481-3b0d-40dd-9884-6c60d03220bf" width="250" /> | Mango |
| <img src="https://github.com/user-attachments/assets/3dc0fa10-94e6-4485-8374-717540b359e9" width="250" /> | Guava |

## 📝 Reflection Questions

### 1. How did the number of images per class affect your model’s accuracy?
The number of images per class was critical for the model's ability to generalize. I found that classes with more diverse images (different angles, lighting, and backgrounds) achieved higher accuracy. A balanced dataset across all fruit types ensured that the model didn't become biased toward one specific fruit.

### 2. Which plant species were most commonly misclassified and why?
The species most commonly misclassified were those with similar external textures or colors, such as **Mango and Guava**, especially in low-light images. This happened because the model initially focused on the green hue and round shape, which are shared characteristics between the two.

### 3. How did changing the epochs, batch size, or learning rate affect the training results?
* **Epochs (50):** Increasing the epochs to 50 allowed the model to reach 100% confidence by giving it enough time to minimize loss. 
* **Batch Size (16):** A smaller batch size of 16 made the training more stable on the web browser and allowed the model to update its weights more frequently.
* **Learning Rate (0.001):** This "middle-ground" rate ensured the model learned at a steady pace. A higher rate made the accuracy fluctuate too much, while a lower rate made the training too slow.

### 4. What challenges did you encounter during dataset collection and labeling?
The main challenge was ensuring quality and variety. It was difficult to find images of certain fruits that didn't have distracting backgrounds. Labeling required careful attention to detail to ensure that no images were placed in the wrong category, which would have confused the model.

### 5. If you were to improve your model, what specific changes would you make and why?
I would increase the **dataset size** and include images of fruits in various stages of ripeness. I would also add a "Neutral" or "Unknown" class to prevent the model from forced-classifying objects that are not fruits at all. This would make the model more robust for real-world use.


