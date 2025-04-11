🧠 How AI Makes Decisions Under Uncertainty — A Hands-On MCMC Walkthrough
Yapay Zeka Belirsizlik Altında Nasıl Karar Verir? MCMC ile Uygulamalı Bir Rehber

🇬🇧 ENGLISH VERSION
“An AI doesn’t just need to be right — it needs to know how uncertain it is.”
This article takes a journey through Markov Chain Monte Carlo (MCMC): a powerful tool that helps AI navigate complex, uncertain decisions.

🧨 From the Manhattan Project to Machine Learning
MCMC's roots go back to WWII, when physicist Stanislaw Ulam and John von Neumann used randomness to estimate probabilities for nuclear simulations. Fast forward to today — MCMC helps AI make sense of uncertain data.

🔍 What We Did in the Notebook:
We used a real breast cancer dataset (UCI’s WDBC) to explore how an AI might:

Learn from data using logistic regression

Sample thousands of possible models using MCMC with Metropolis-Hastings

Visualize the posterior distributions of model parameters

Predict a single sample and show the full distribution of uncertainty

Make a binary decision based on probability > threshold

📊 Here's an example output:

“Predicted probability of malignancy: 43.6%”
“Final decision: Benign ✅”

📎 Full notebook: https://github.com/efecavdar/MCMC/
(optional thumbnail of the histogram of predicted probabilities)

🇹🇷 TÜRKÇE VERSİYONU
“Bir yapay zekanın sadece doğru olması değil, ne kadar emin olduğunu da bilmesi gerekir.”
Bu yazıda, yapay zekanın belirsizlik altında nasıl karar verdiğini gösteren güçlü bir araç olan MCMC (Markov Zinciri Monte Carlo) yöntemini keşfediyoruz.

🧨 Manhattan Projesi'nden Makine Öğrenmesine
MCMC, 2. Dünya Savaşı'nda atom bombasının olasılık hesaplarında ortaya çıktı. Günümüzde ise AI modelleri için belirsizlik altında karar verme sistemlerinin temelinde yer alıyor.

🔍 Notebook'ta Ne Yaptık?
Gerçek bir veri seti (UCI meme kanseri verisi) üzerinden:

Lojistik regresyon modeli kurduk

MCMC ile binlerce model parametresi örnekledik

Parametrelerin posterior dağılımlarını görselleştirdik

Tek bir örnek için tahmin yaptık ve belirsizlik dağılımını analiz ettik

Tahmin > 0.5 ise sınıflandırma kararı verdik

Notebook : https://github.com/efecavdar/MCMC/
