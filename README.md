# DeepfakeDetection
In questo progetto per l'esame di ML-SII 2019/20 cerco di risolvere il problema dei Deepfake attraverso l'uso di reti neurali.

# Usage

Per l'utilizzo del codice bisogna utilizzare :
1-Una porzione di video presi dalla challange di kaggle sui deepfake:
https://www.kaggle.com/c/deepfake-detection-challenge

2- Oppure utilizzando il dataset di Google:
https://ai.googleblog.com/2019/09/contributing-data-to-deepfake-detection.html

3- Oppure si possono creare 2 folder dove vengono suddivisi i video veri da quelli Deepfake 

Per cominciare l'esperimento bisogna utilizzare i notebook all'interno di  "preprocess" e poi successivamente modificare il path all'interno delle variabili globali, settando il proprio path ai video.

Una volta lanciato preprocess quello che si ottiene è una serie di directory di video contenenti tutti i frame del video.

A questo punto è possibile far partire il notebook su kaggle se si sono utilizzati i video della competizione di kaggle oppure il notebook di google se invece si è diviso a mano i rispettivi video.

Una volta addestrata la rete il notebook salva automaticamente il modello della rete che è possibile ricaricare per procedere alla predizione sui video di test
