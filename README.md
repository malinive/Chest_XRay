# Chest_XRay
This is the course project in DAT255 (Deep Learning Engineering). 

**Dataset:** Downloaded from https://stanfordmlgroup.github.io/competitions/chexpert. The dataset is a csv-file. 

**The goal:** To create a deep learning system able to detect one or more of 14 conditions from one or more chest X-rays. 

**Methods:** This project is doable with the knowledge obtained from the Fastai course. 



## Jupyter Notebooks
The project contains two notebooks:

**00-ChestXray-collect_and_explore_data.ipynb** explores the data in the dataset.

**01-ChestXRay-preprocessing_and_training.ipynb** preprocesses data, trains the data and makes a Notebook App of the model. 



## What are the 14 conditions that can potensially be detected on the x-rays?

See https://github.com/stanfordmlgroup/chexpert-labeler/tree/master/phrases/mention for a list of all the terms used by the labeler which fall into a category.

1. **No Findings:** The absence of pathologies.
2. **Enlarged Cardiomediastinum:** Enlargement of the central compartment of the thoracic cavity.
3. **Cardiomegaly:** An enlarged heart refers to a heart that is bigger than typical. The heart may be unusually thick or dilated (stretched). An enlarged heart may be temporary or permanent, depending on the cause.
4. **Lung Opacity:** A frequently used term by radiologists on chest X-rays and essentially means a white spot of uncertain significance. The lungs are normally black on a chest X-ray so anything that blocks the X-rays from getting through will look white on an X-ray. A white spot amidst the normal black lungs can therefore be a cancer, infection, bleeding, fluid, foreign body amongst other possibilities.
5. **Lung Lesion:** An abnormality in the lungs.
6. **Edema:** Swelling caused by excess fluid trapped in your body's tissues. It can affect any part of your body, but may be more noticeable in hands, arms, feet, ankles and legs. 
7. **Consolidation:** Occurs when the air that usually fills the small airways in your lungs is replaced with something else (a fluid or a solid).
8. **Pneumonia:** Swelling (inflammation) of the tissue in one or both lungs. It's usually caused by a bacterial infection. It can also be caused by a virus, such as coronavirus (COVID-19).
9. **Atelectasis:** A complete or partial collapse of the entire lung or area (lobe) of the lung. It occurs when the tiny air sacs (alveoli) within the lung become deflated or possibly filled with alveolar fluid.
10. **Pneumothorax:** A collapsed lung. A pneumothorax occurs when air leaks into the space between your lung and chest wall. This air pushes on the outside of your lung and makes it collapse. A pneumothorax can be a complete lung collapse or a collapse of only a portion of the lung.
11. **Pleural Effusion:** Pleural effusion, sometimes referred to as “water on the lungs,” is the build-up of excess fluid between the layers of the pleura outside the lungs. The pleura are thin membranes that line the lungs and the inside of the chest cavity and act to lubricate and facilitate breathing. Normally, a small amount of fluid is present in the pleura.
12. **Pleural Other:** Conditions that affect the tissue that covers the outside of the lungs and lines of your chest cavity. 
13. **Fracture:** A bone fracture is a full or partial break in the continuity of bone tissue. Fractures can occur in any bone in the body.
14. **Support Devices:** Includes devices like central lines, pacemakers, ET tubes etc. 



## Why is this important?
Chest radiography is the most common imaging examination globally, critical for screening, diagnosis, and management of many life threatening diseases. Automated chest radiograph interpretation at the level of practicing radiologists could provide substantial benefit in many medical settings, from improved workflow prioritization and clinical decision support to large-scale screening and global population health initiatives (https://stanfordmlgroup.github.io/competitions/chexpert/).



Sources: 
https://www.mayoclinic.org/diseases-conditions/edema/symptoms-causes/syc-20366493
https://www.medicalnewstoday.com/articles/173312#what-is-a-bone-fracture
https://my.clevelandclinic.org/health/diseases/17373-pleural-effusion-causes-signs--treatment
https://www.nhlbi.nih.gov/health/pleural-disorders
https://www.mayoclinic.org/diseases-conditions/pneumothorax/symptoms-causes/syc-20350367
https://www.healthline.com/health/lung-consolidation
https://www.nhs.uk/conditions/pneumonia/
https://www.mayoclinic.org/diseases-conditions/atelectasis/symptoms-causes/syc-20369684
https://www.cancercenter.com/community/blog/2021/05/when-to-worry-about-lung-nodules
https://radiologyinplainenglish.com/what-is-meant-by-lung-opacity-on-a-chest-x-ray/
https://my.clevelandclinic.org/health/diseases/21490-enlarged-heart-cardiomegaly
https://en.wikipedia.org/wiki/Mediastinum







