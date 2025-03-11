# Statistical-Test
This repo contains all statistical-test related files or projects

### A/B testing Definition
<p>Asumsikan anda mendevelop suatu fitur rekomendasi produk yang bertujuan untuk meningkatkan engagement user app hingga meningkatkan konversinya terhadap transaksi. Conversion Rate ini kemudian menjadi success metric terhadap development fitur tersebut. Lalu, bagaimana cara mengukur apakah fitur ini benar-benar berhasil atau tidak? 
Praktik yang lazim diterapkan adalah, dengan mengukur rata-rata conversion rate before after atau mengukur total revenue before after. Jika meningkat, dapat dianggap berhasil dan sebaliknya. Tentu hal tersebut tidak cukup. Perlu diukur dan diuji signifikansi kenaikan tersebut agar dapat disimpulkan fitur berhasil atau tidak. Pengukuran dan pengujian ini dapat dilakukan dengan A/B Testing.
Sehingga A/B Testing berarti adalah metode pengujian atau eksperimentasi untuk mengetahui mana di antara dua kelompok uji (A dan B) yang lebih baik menurut metric yang ditentukan. Misalnya, dalam case ini conversion rate atau revenue.</p>

### Steps
#### Langkah-langkah A/B Testing adalah 
<ul>
  <li>Exploratory Data Analysis </li>
  <p>Step ini bertujuan untuk memahami karakter data yang akan diuji. Karena A/B testing membandingkan 2 kelompok uji, maka biasanya data tersebut harus mutually exclusive antara 2   kelompok uji tersebut. 
Hal lain yang perlu diketahui adalah, normality distribusi dari dataset. Bisa dilihat melalui deskriptif statistik, kurtosis dan skewness menggunakan pandas, atau visual inspection menggunakan chart seperti boxplot, distribution plot atau violin plot atau uji normalitas menggunakan library scipy.
Normalitas akan berhubungan dengan metode statistik yang digunakan untuk A/B testing nantinya. </p>
<li>Data Cleansing and Preparation</li>
<p>Beberapa data preparation yang standar seperti data deduplikasi, imputasi, outlier removing, labelling antara control dan treatment, dan lainnya. </p>
<li>Sampling</li>
<p>Sampling adalah mengambil sebagian data yang dianggap representatif mewakili karakter populasi. Bertujuan untuk efektivitas resources pada data yang berukuran besar, juga sebagai pengujian konsistensi hasil uji statistik pada data.</p>
<li>Assign Control & Treatment Group</li> 
<li>Statistical Test</li>
<p>Memilih metode pengujian berdasarkan karakteristik data yang sudah dieksplor pada langkah pertama. Misal, menggunakan T-Test untuk normal distribution continuous data, atau Mann-whitney U Test untuk data yang tidak berdistribusi normal</p>
</ul>

### Dataset 
Dataset yang digunakan adalah dataset yang tercantum. Source : https://www.kaggle.com/code/iyadmahdy/a-b-testing-analysis-marketing-campaign/input
### Prerequisite
Berikut minimum spec dan beberapa tools yang dibutuhkan : 
<ul>
<li>Processor: Intel Core i3 (10th Gen) </li>
<li>RAM: 8GB </li>
<li>Storage: 256GB SSD </li>
<li>OS: Windows 10/11, macOS, or Linux</li>
<li>Software: Anaconda with Jupyter Notebook</li>
<li>Jupyter notebook/ google colab/ other code editor tools</li>
</ul>
