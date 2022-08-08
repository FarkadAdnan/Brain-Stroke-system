#   ![image](https://user-images.githubusercontent.com/35774039/183364198-9c164f64-cc71-4715-ac06-d507d36da873.png)


and an adaptive fuzzy neurological reasoning system with medical imaging using magnetic resonance imaging (magnetic resonance imaging) to aid in the diagnosis of strokes , *farkadadnan

- https://linktr.ee/farkadadnan

-  By:Farkad Adnan فرقد عدنان - 
 - E-mail: farkad.hpfa95@gmail.com 
- inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
- FaceBook: كتاب عالم الاردوينو 
- inst : arduinobook

* facebook : https://www.facebook.com/profile.php?id=100002145048612
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/

 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>

# Brain Stroke Severity Prediction and Analysis
Stroke is a disease that affects the arteries leading to and within the brain. A stroke occurs when a blood vessel that carries oxygen and nutrients to the brain is either blocked by a clot or ruptures. According to the WHO, stroke is the 2nd leading cause of death worldwide. Globally, 3% of the population are affected by subarachnoid hemorrhage, 10% with intracerebral hemorrhage, and the majority of 87% with ischemic stroke. 80% of the time these strokes can be prevented, so putting in place proper education on the signs of stroke is very important. The existing research is limited in predicting risk factors pertained to various types of strokes. This research work proposes an early prediction of stroke diseases by using different machine learning approaches with the occurrence of hypertension, body mass index level, average glucose level, smoking status, previous stroke and age. Machine Learning techniques including Logistic Regression, Random Forest, Decision Trees, Naive Bayes, SVM, MLP etc. are used to predict the severity of future stroke occurrence on a scale of 0 to 3. The study not only predicts the fututre risk of a getting a stroke for a certain individual who has never had a stroke, but also the future risk of occurrence of a more dangerous variant of stroke for those who have already had a stroke.

- في مجال التعلم الآلي والتعلم العميق ، كان الإجماع على أنه كلما كانت الشبكة أعمق ، يجب أن تكون مجموعة البيانات أكبر وكلما زادت عينات التدريب المطلوبة. وبالتالي ، تم تقييد الشبكات العصبية التلافيفية بحجم مجموعات البيانات المتاحة. على الرغم من أدائهم الجيد في مناطق مختلفة ، إلا أن حجم مجموعة البيانات المتاحة للمهام المختلفة حد من نجاح كل شبكة. في الآونة الأخيرة ، أصبحت مجموعات بيانات الصور أكبر بكثير ، أي ملايين الصور في مجموعة البيانات مما يجعل من الممكن تدريب شبكات أعمق. ومع ذلك ، بالنسبة لمناطق محددة حيث الصور غير متاحة للجمهور أو يصعب الحصول عليها ، على سبيل المثال التطبيقات الطبية الحيوية ، تظل المشكلة قائمة.
# Introduction
In 2018, 1 in every six deaths from cardiovascular disease was due to stroke. Someone in the United States has a stroke every 40 seconds. Every 4 minutes, someone dies of a stroke. Every year, more than 795,000 people in the United States have a stroke. About 610,000 of these are first or new strokes. Stroke is a leading cause of serious long-term disability. Stroke reduces mobility in more than half of stroke survivors age 65 and over.

- في عام 2018 ، كانت حالة واحدة من كل ست وفيات ناجمة عن أمراض القلب والأوعية الدموية بسبب السكتة الدماغية. يصاب شخص ما في الولايات المتحدة بسكتة دماغية كل 40 ثانية. كل 4 دقائق يموت شخص بسكتة دماغية. كل عام ، يصاب أكثر من 795000 شخص في الولايات المتحدة بسكتة دماغية. حوالي 610،000 من هذه السكتات الدماغية الأولى أو الجديدة. السكتة الدماغية هي سبب رئيسي للإعاقة الخطيرة طويلة الأمد. تقلل السكتة الدماغية من الحركة لدى أكثر من نصف الناجين من السكتات الدماغية في سن 65 وما فوق.
![z](https://user-images.githubusercontent.com/35774039/183362305-29bffbe8-03b1-4cd1-b0c6-bc21f06c3b20.PNG)

# Machine Learning for Stroke Prediction

Machine learning techniques can be used to predict the occurrence and risk of stroke in a human being.The existing research is limited in predicting whether a stroke will occur or not. Our work attempts to predict the risk of stroke-based upon a ranking scale determined with the following criteria: 0:Low risk, 1: Moderate Risk, 2: High Risk, 3: Severe risk. This is a multiclass classification in contrast to the binary classification done by most authors earlier. We have used features including hypertension, body mass index level, average glucose level, smoking status, previous stroke severity(Nihss score), age and gender to predict the risk of stroke for an individual. Machine Learning techniques including Logistic Regression, Random Forest, Decision Trees and Naive Bayes have been used for prediction.Our work also determines the importance of the characteristics available and determined by the dataset.Our contribution can help predict early signs and prevention of this deadly disease.


- يمكن استخدام تقنيات التعلم الآلي للتنبؤ بحدوث السكتة الدماغية ومخاطرها لدى الإنسان ، فالبحوث الحالية محدودة في التنبؤ بما إذا كانت السكتة ستحدث أم لا. يحاول عملنا التنبؤ بمخاطر الإصابة بالسكتة الدماغية بناءً على مقياس تصنيف محدد بالمعايير التالية: 0: مخاطر منخفضة ، 1: مخاطر متوسطة ، 2: مخاطر عالية ، 3: مخاطر شديدة. هذا تصنيف متعدد الطبقات على عكس التصنيف الثنائي الذي قام به معظم المؤلفين في وقت سابق. لقد استخدمنا ميزات تشمل ارتفاع ضغط الدم ومستوى مؤشر كتلة الجسم ومتوسط مستوى الجلوكوز وحالة التدخين وشدة السكتة الدماغية السابقة (درجة Nihss) والعمر والجنس للتنبؤ بخطر الإصابة بالسكتة الدماغية للفرد. تم استخدام تقنيات التعلم الآلي ، بما في ذلك الانحدار اللوجستي والغابات العشوائية وأشجار القرار و Naive Bayes للتنبؤ ، كما يحدد عملنا أهمية الخصائص المتاحة والتي تحددها مجموعة البيانات ، ويمكن أن تساعد مساهمتنا في التنبؤ بالعلامات المبكرة والوقاية من هذا المرض الفتاك .

#  ![image](https://user-images.githubusercontent.com/35774039/183363108-8f44a1ac-cfb7-4d37-9019-841163340fc6.png)
There are varying methods used for diagnosis include artificial intelligence techniques, such as support vector machine neural network, artificial neural network, fuzzy logic, and adaptive neuro-fuzzy inference system with medical imaging like by Computed Tomography (CT) or Methods using Magnetic Resonance Imaging (MRI) are very important to help diagnose this disease. We well investigated all these techniques to identify a method that can provide superior accuracy for diagnosis the diseases
 

# ![image](https://user-images.githubusercontent.com/35774039/183363578-c0effc5f-e923-43db-a712-8d21421b3b42.png)
Normally, there are five main steps for brain stroke detection as shown in Figure (1), which are image acquisition , pre-processing, segmentation, features extraction, features selection and finally classification
 
![image](https://user-images.githubusercontent.com/35774039/183363735-815a5f56-7fd4-4530-845c-ca3b21c1b0fe.png)



#  ![image](https://user-images.githubusercontent.com/35774039/183363418-4ee4d4d3-b0b1-4705-80be-db4391399a4b.png)


![Capturessss](https://user-images.githubusercontent.com/35774039/183362541-e8469d99-f75b-40e9-9f0e-1412c85d6db7.PNG)
- النتائج التالية وحسب التسلسل تظهر لعرض وتحديد السكتة الدماغية

![a (1)](https://user-images.githubusercontent.com/35774039/183362851-75bdbcda-d9f7-40a7-899a-93fd57dafc69.PNG)
![a (2)](https://user-images.githubusercontent.com/35774039/183362855-586c0158-b094-446a-967f-b60ea4648b74.PNG)
![a (3)](https://user-images.githubusercontent.com/35774039/183362857-51da4c0c-00c4-4f4a-b3c5-69500fed9581.PNG)
![a (4)](https://user-images.githubusercontent.com/35774039/183362859-d4dde547-a8eb-4f4a-83aa-136f147ed1f6.PNG)
![a (5)](https://user-images.githubusercontent.com/35774039/183362860-9291972f-ca9b-4e53-abab-9c716223f1e3.PNG)
![a (6)](https://user-images.githubusercontent.com/35774039/183362861-bf07110c-ca96-4b55-a3b9-233df5c6986e.PNG)
![a (7)](https://user-images.githubusercontent.com/35774039/183362863-bc2da834-fb7d-4f4f-aa24-84b1a4f33fa1.PNG)


#  ![image](https://user-images.githubusercontent.com/35774039/183363885-51ffc486-b680-4768-a27d-ad343862dd28.png)

- 	Virani, S.S.; Alonso, A.; Aparicio, H.J.; Benjamin, E.J.; Bittencourt, M.S.; Callaway, C.W.; Carson, A.P.; Chamberlain, A.M.; Cheng, S.; Delling, F.N.; et al. Heart Disease and Stroke Statistics—2021 Update: A Report from the American Heart Association. Available online: https://www.heart.org/-/media/PHD-Files-2/Science-News/2/2021-Heart-and-Stroke-Stat-Update/2021_Stat_Update_factsheet_Global_Burden_of_Disease.pdf (accessed on 27 January 2021). [CrossRef]
- 	Easton JD, Saver JL, Albers GW, Alberts MJ, Chaturvedi S, Feldmann E. Definition and Evaluation of Transient Ischemic Attack. Stroke. 2009; 40:2276-2293 doi: 10.1161/STROKEAHA.108.192218. (Accessed: 25 April 2010).
- 	Copenhaver B.R, J. Shin, S. Warach, J. A. Butman, J. L. Saver and C. S. Kidwell. Gradient echo MRI: Implementation of a training tutorial for intracranial hemorrhage diagnosis. Neurology 2009; 72; 1576-1581. DOI: 10.1212/WNL.0b013e3181a411df (Accessed: 9 February 2010)
- 	Davis S, Marc Fisher, Steven Warach. (2003) Magnetic Resonance Imaging in stroke.
- 	 Donnan GA, Fisher M, Macleod M, Davis SM. "Stroke". Lancet 2008 (9624): 1612–23. doi:10.1016/S0140-6736(08)60694-7. (Accessed: 16 April 2010).
- 	Chalela J.A, Chelsea S Kidwell, Lauren M Nentwich, Marie Luby, John A Butman, Andrew M Demchuk, Michael D Hill, Nicholas Patronas, Lawrence Latour, Steven Warach. Magnetic resonance imaging and computed tomography in emergency assessment of patients with suspected acute stroke: a prospective comparison. Lancet 2007; 369: 293–98. (Accessed: 20 April 2010)
- 	Copenhaver B.R, J. Shin, S. Warach, J. A. Butman, J. L. Saver and C. S. Kidwell. Gradient echo MRI: Implementation of a training tutorial for intracranial hemorrhage diagnosis. Neurology 2009; 72; 1576-1581. DOI: 10.1212/WNL.0b013e3181a411df (Accessed: 9 February 2010)
- Fiebach J.B. & P.D Schellinger (2003) Stroke MRI. Germany
- 	Copenhaver B.R, J. Shin, S. Warach, J. A. Butman, J. L. Saver and C. S. Kidwell. Gradient echo MRI: Implementation of a training tutorial for intracranial hemorrhage diagnosis. Neurology 2009; 72; 1576-1581. DOI: 10.1212/WNL.0b013e3181a411df (Accessed: 9 February 2010).

