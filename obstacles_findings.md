# Obstakels en ondervindingen

## Ondervindingen
Hogere batch size  
* ✔ Accuracy improvement! (training)
* ✘ Overfit! 
	* Batch size gestopt voor early stopping kon stopzetten
	* Amper boven 50% op validatie data

Batch normalization + Dropout
 * ✘ Accuracy decreases

Batch normalization
 * ✘ Overfit

Dropout
 * ✘ Overfit

Augmentation
 * Weinig verandering, niet veel beter en niet veel slechter...

RMSProp Optimizer gebruiken
* ✘ Accuracy decreases

Early stopping hoger zetten
* Relu + Softmax
* Early stopping bijna na de 4e epoch…
* ✘ Overfit

Hogere dropout
* Vorige was een te lage dropout...
* ✘ Maximum ~37% acc

Long Short-Term Memory
* ✘ Overfit na 14 epochs...

## Ideeën:
* "Eigen random search" maken -> Combinaties testen
	* Pro: Goed overzicht
	* Contra: Weinig improvements(?), lange duur...
