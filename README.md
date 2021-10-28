# Pawpularity contest
https://www.kaggle.com/c/petfinder-pawpularity-score


**ДЗ:**
<ol>
<li> Реализовать в PyTorch модель, которая предсказывала бы популярность на основе бинарных признаков (train.csv, test.csv). </li>
<li> Поправить код в файле Baseline (CNN):</li>
<ul>
<li>можно использовать OpenCV вместо PIL (import cv2, см. примеры в https://www.kaggle.com/c/petfinder-pawpularity-score/code) и посмотреть scikit-image;</li>
<li>научиться подгружать также бинарные признаки через класс (поправить PawpularDataset);</li>
<li>написать свою сверточную сеть вместо PretrainedCNN (назвать иначе, использовать больше слоев / использовать другую модель из torch.models или timm / убрать Dropout);</li>
<li>поиграть с transforms (например, оставить только Resize);</li>
<li>поиграть с гиперпараметрами обучения (hidden_size, learning_rate, num_epochs, weight_decay у Adam);</li>
</ul>
<li>После отладки модели дописать код, чтобы получить решение для test.csv. Возможно, для этого стоит переписать PawpularDataset, чтобы он возвращал ещё Id изображений, или же достаточно установить shuffle=False у DataLoader.</li>
<li>Отправить решение для test.csv. Сравнить RMSE с локальным.</li>
</ol>  
