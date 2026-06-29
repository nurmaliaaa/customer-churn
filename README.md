📊 Prediksi Customer Churn dengan Data Mining

Implementasi CRISP-DM untuk memprediksi pelanggan yang berpotensi churn menggunakan Logistic Regression.


📁 Dataset


440.833 pelanggan | 12 fitur | Target: Churn (0/1)
Distribusi: 56,7% Churn / 43,3% Tidak Churn


⚙️ Metodologi


Framework: CRISP-DM
Algoritma: Logistic Regression + Threshold Tuning (0,5 → 0,4)
Tools: Python, Google Colab


📈 Hasil

MetrikTargetHasilStatusRecall≥ 75%86,68%✅ TercapaiAUC-ROC≥ 85%92,80%✅ Tercapai

💡 Insight Utama


Support Calls = faktor churn terkuat
Total Spend = faktor pelindung terkuat
Pelanggan kontrak Monthly memiliki churn tertinggi (100%)
