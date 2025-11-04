# Proyek-Sistem-Rekomendasi

## 1. Baseline Item Popularity
Kami menggunakan Item Popularity sebagai baseline awal dimana ini buruk karena ini non personalized sehingga yang direkomendasikan sama untuk setiap user. Adapun MAP@10 Score yang kami dapatkan adalah 0.0044.

## 2. Baseline Item Based Colaboraitve Filtering (IBCF)
Kami berusaha menggunakan personalized juga yaitu IBCF. Namun karena matriksnya terlalu besar karena banyaknya kemungkinan. Jadi kami memutuskan hanya menggunakan sebagian data yaitu 2000 user dan 4000 item. Memang hal ini tidak bisa mewakili keseluruhan user dan item namuan secara  keseluruhan pun tidak bisa karena kurangnya perangkat keras yang kami miliki. Adapun MAP@10 Score yang kami dapatkan adalah 0.0303.

## 3. Alternating Least Square (ALS)
Kami telah berhasil meningkatkan performa sistem rekomendasi ALS kami secara signifikan. Proses ini kami lakukan dengan menyesuaikan beberapa setelan penting, seperti durasi latihan model dan seberapa detail model mempelajari pola pengguna, serta memberi bobot lebih pada interaksi yang sering dilakukan. Kami juga memperbaiki cara evaluasi menggunakan MAP@10 dan memastikan model tidak merekomendasikan barang yang sudah pernah dilihat pengguna. Hasilnya, skor performa model melonjak drastis dari 0.018 menjadi 0.10, dan kami akan terus melanjutkan optimasi ini untuk mencapai hasil yang lebih tinggi.

## 4. Bayesian Personalized Ranking (BPR)
