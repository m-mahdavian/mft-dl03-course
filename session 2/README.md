<p>
تمرین 1: در این تمرین منطق AND را توسط مدل بر پایه پرسپترون باید شبیه سازی کنیم. خروجی برنامه نشان می دهد مدل به خوبی قادر به پیشبینی است.
</p>
<p>

تمرین 2: در این تمرین باید gridsearch  بر روی هایپر پارامترهای MLPClassifier بر روی مجموعه داده‌های heart_failure_clinical_records_dataset انجام شود. خروجی نشان داد اگر هایپر پارامترها به طریق زیر تنظیم شوند، مدل بهترین جواب را به لحاظ f1-score می دهد:
{'cls__hidden_layer_sizes': 200, 'cls__learning_rate_init': 0.01, 'cls__max_iter': 1000, 'cls__random_state': 1404, 'cls__solver': 'adam'}
</p>
<p>
تمرین 3: در این تمرین باید gridsearch  بر روی هایپر پارامترهای LR و DT بر روی مجموعه داده‌های heart_failure_clinical_records_dataset انجام شود خروجی نشان داد اگر هایپر پارامترها به طریق زیر تنظیم شوند، مدل بهترین جواب را به لحاظ f1-score می دهد:
برای مدل LR: 
{'cls__max_iter': 200, 'cls__solver': 'lbfgs', 'cls__tol': 0.001}
برای مدل DT:
{'cls__criterion': 'gini', 'cls__max_depth': 5, 'cls__min_samples_split': 2}
</p>

