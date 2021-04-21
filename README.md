# vae-pix2pix-paper

Paper for VAE-pix2pix

## Abstract
In this study, we use NASA’s SRTM 1 Arc-Second dataset to collect altitude maps from around the world, and we also use MapTiler to collect corresponding satellite images. Using these collected images, we trained our VAE-pix2pix model, which is a Variational Autoencoder (VAE) combined with pix2pix (a Conditional Generative Adversarial Network). VAE-pix2pix can add details of the real-world mountain should have (including sharp ridges, mountain wall textures, continuous river networks, etc.) to the heightmap, users draw which. Our model can generate the corresponding satellite images as well. Compared with the original pix2pix model, our model can generate heightmap and satellite images that are more realistic. It can also generate different styles of heightmap and satellite images by changing the value of the latent code, such as the color of the landform or the height of the snow line. This increases the diversity of the images generated by the model. To make our model can be better used, we have developed a client on Unity, which can generate a mesh that allows users to directly use it when developing games in Unity. In conclusion, our work has simplified generating a realistic mountain model in the game or other fields as well.

## 摘要

本研究利用NASA的SRTM 1 Arc-Second資料集來收集全球各地的地形高度圖(heightmap)，也利用MapTiler網站收集相對應的衛星空照圖，用這些收集的圖像，訓練我們建構的VAE-pix2pix模型。VAE-pix2pix為Variational Autoencoder (VAE)及pix2pix (為一個Conditional Generative Adversarial Network)結合的模型，能將人工繪製的高度圖加上真實山脈應有的細節(包含尖銳的山脊、山壁上的紋路、連續的河流網路等……)，並生成出相對應的擬真衛星空照圖。相較於原pix2pix模型，VAE-pix2pix所生成的高度圖及衛星空照圖會更接近於真實世界的地形高度圖及衛星空照圖，同時VAE-pix2pix模型也能透過改變latent code的數值來生成出不同風格的高度圖及空照圖，如地貌的顏色或雪線的高度等，這些都增加模型生成圖像的多樣性。為了使我們建構的模型能更廣泛的被應用，我們在Unity上開發了Unity客戶端，其生成的mesh可以讓使用者直接應用於遊戲的場景，簡化了遊戲中生成擬真山脈模型的任務。


## Award / 獎項
- 2021 臺灣國際科展 電腦科學與資訊工程科 四等獎 2021 ITSF Computer Science & Informatic Engineering Forth Award
