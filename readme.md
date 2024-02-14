## Facial Recognition, Text Recognition and Image/Video Description in Vision Studio




<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/GianDutra/Machine-Learning-no-Azure-ML">

   <a href="https://github.com/GianDutra/Machine-Learning-no-Azure-ML/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/GianDutra/Machine-Learning-no-Azure-ML">
  </a>
  
</p>
<img src="./Images/8.png" alt="dashboard apresentando diversos números estatísticos, um gráfico comparando o que estava previsto e o que realmente aconteceu e um gráfico de histograma" title="Machine-Learning-Azure-ML">
> Project developed as a challenge - AI-900 Preparation!

## About the project

I created a service in Azure AI Vision Studio and experimented with some uses of artificial intelligence, such as recognizing a face, a text, describing what is happening in an image, and searching for an event/object in a video.
  
## **How to get started**

First, I clicked on "Create a resource" and created a new "Cognitive Service". After that, I simply selected my resource group that I had previously created in the [previous challenge](https://github.com/GianDutra/Machine-Learning-no-Azure-ML), chose a name that I thought was suitable, and the "Standard S0" plan. After that, I waited and in less than 1 minute I had already created a resource on [Vision Studio website](https://portal.vision.cognitive.azure.com/).

<img src="./Images/1.png" alt="">
<img src="./Images/2.png" alt="">
<img src="./Images/3.png" alt="">
<img src="./Images/4.png" alt="">
<img src="./Images/5.png" alt="">


### **Step two**

I initiated the studio as you can see in the photo, I chose the "Automated ML" option and created a new automated ML job. Next, I put in a name I thought was suitable for my project, a name for my experiment, and a description. After that, I chose to perform regression because I wanted to predict a numerical value. I selected "Tabular" as the data asset type, imported a .csv file that I wanted to experiment with, and processed the data to see if it was in the correct format. Finally, I chose the primary metric "NormalizedRootMeanSquaredError" and allowed the "RandomForest" and "LightGBM" models, setting in the limits tab the respective values of: 3, 3, 3, 0.085, 15, 15, and enabling early termination, in addition to choosing the validation option called "Training validation split".

<img src="./Images/6.png" alt="">
<img src="./Images/7.png" alt="">
<img src="./Images/8.png" alt="">
<img src="./Images/9.png" alt="">
<img src="./Images/10.png" alt="">
<img src="./Images/11.png" alt="">
<img src="./Images/12.png" alt="">
<img src="./Images/13.png" alt="">
<img src="./Images/14.png" alt="">
<img src="./Images/15.png" alt="">


## Final Considerations
In this project, I learned a lot about Azure Machine Learning, and although I already had some experience in Machine Learning through courses and projects, it was really cool to see how easy, fast, and advanced this matter is within Azure. I will definitely use these services again if I need to perform a regression or any other task, and I'm excited for my next learning opportunity.

## 👨‍💼 Autor

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://github.com/GianDutra.png" width="100px;" alt="Foto do Gian no GitHub"/><br>
        <sub>
          <b>Gian Dutra</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
