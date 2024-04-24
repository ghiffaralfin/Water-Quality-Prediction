# The Art of Prompt Engineering
Author : Sina Nazeri (PhD.)
<br>
Source : [CognitiveClass.ai](https://cognitiveclass.ai/courses/course-v1:IBMSkillsNetwork+GPXX0TGVEN+v1?authuser=0 "The Art of Prompt Engineering")

---

Mentee assignment from IBM Advance AI @ Infinite Learning

Mikro & Makro Project From Group **30**

---



## Mentee Info:

| Program : | IBM Advanced AI |
|--------|--------------------|
| Name :| Muhammad Irvan Arfirza |
| Name :| Ghiffar ALfin Faiz |
| Name :| Salmen Christowfik |
| Name :| Eka Bulandary|
| Name :| Alma Sara Khalidiyah |

<br>

---

## Documentation

### *Background*

Indonesia menghadapi tantangan serius terkait kualitas dan akses air bersih bagi masyarakatnya. Menurut data UNICEF pada tahun 2020, hanya 72% dari penduduk Indonesia yang memiliki akses terhadap air minum yang layak. Bahkan lebih mengkhawatirkan, sebanyak 28% dari penduduk Indonesia sama sekali tidak memiliki akses terhadap air minum yang aman[1].

### *Objective*

Dengan dibangunnya suatu model yang mampu mengidentifikasi kualitas air, diharapkan model tersebut dapat membantu dalam menentukan apakah air tersebut layak untuk dikonsumsi atau tidak, berdasarkan hasil uji kualitas air yang dilakukan.

### *Goals*

Dengan dibuatnya suatu model yang dapat mendeteksi kualitas dari air yang ada, maka diharapkan bahwa air yang disalurkan kepada pengguna bisa dipastikan layak minum dengan begitu dampak buruk karena meminum air yang kurang layak dapat dihindarkan. 

---
## Dataset and Algorithm

Dataset yang kami gunakan untuk mengolah model ini memiliki beberapa parameter untuk diolah yaitu pH Value, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic_carbon, Trihalomethanes, Turbidity dan Potability.

Dataset Source : [Water Quality Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability/data "Water Quality Dataset") 

Algoritma yang kami gunakan merupakan algoritma gabungan dari Random Forest dan Decision Tree, karena dari kedua algoritma tersebut memiliki beberapa kelebihan dan kekurangan yang dapat ditutup ketika kedua algoritma tersebut disatukan.

---
## Model Evaluation
Menggunakan teknik evaluasi model yang umum, yaitu Grid Search Cross-Validation untuk mencari kombinasi hyperparameter terbaik pada model Decision Tree Classifier. Evaluasi dilakukan dengan membagi data menjadi training dan testing set, di mana data training digunakan untuk melatih model dan data testing digunakan untuk menguji kinerja model yang telah dilatih.

 Kombinasi hyperparameter terbaik ditemukan dengan mencoba berbagai nilai hyperparameter menggunakan Repeated Stratified K-Fold Cross-Validation. Selain itu, metrik evaluasi yang digunakan juga bervariasi, termasuk akurasi (accuracy score) dan area di bawah kurva ROC (ROC AUC score) untuk melihat kinerja model secara keseluruhan. Evaluasi ini membantu memilih model terbaik yang dapat menggeneralisasi dengan baik terhadap data yang belum pernah dilihat sebelumnya.
 
 ## Achievement of project goals
 
1. Menghasilkan model AI yang dapat secara akurat menentukan kualitas air, apakah layak untuk dikonsumsi atau tidak.
2. Dapat mengidentifikasi parameter-parameter utama yang mempengaruhi kualitas air, seperti kandungan mineral, tingkat keasaman (pH), dan komponen lainnya.
3. Dapat memastikan model AI yang dikembangkan dapat diterapkan secara luas dan mudah digunakan oleh masyarakat, terutama di daerah-daerah yang kurang memiliki akses ke air bersih.

## Limitations and challeges faces

1. memilih algoritma yang sesuai dengan jenis permasalahan (klasifikasi kualitas air) dan karakteristik data yang tersedia.
2. proses penyesuaian  parameter algoritma dalam mengoptimalkan performa model.untuk mendapatkan akurasi klasifikasi yang tinggi dan generalisasi yang baik.

<br>

## Thank you





