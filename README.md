# khadija_MachinLearning
For Master Projekt mappa:

Masterpro_MFCC_SVM_XGBoost_ANN utviklet på balansert dataset med like mange COVID-19 filer som friske. 
Features'ene som har blitt tatt hånd om er gjennomsnitt og standardverdien av MFCCs(mel-frequency cepstral coefficients). 
Modellene som er brukt er SVM(Support-vector machine), XGBoost og ANN (Artificial neural network).

Masterpro_Time-varying_features_BALANCED utviklet på balansert dataset med like mange COVID-19 filer som friske. 
Featursene har bitt tatt hånd er også MFCC men tidsdimensjonen er inkludert for å se om det gjør noe forskjell da hoste utvikles i tid. 
Modellen som er brukt er LSTM da det er en modell som er god på tid.

Masterpro_Time-varying_features_UNBALANCED utviklet på en ubalansert data med en fordeling 1:12 hvor COVID-19 er minoritetsklassen. 
For å unngå at modellen kun lærer på friske hoster har SMOTE blitt brukt som sampler like mange COVID-19 hoster som friske hoster. 
Modellen som er brukt er LSTM da det er en modell som er god på tid.

plot_master_project viser noe av visualiseringen som har blitt brukt underveis av utviklingen.


Andre filer:

TTT4185_assignment_2_2020-09-28: Klassifisering ved bruk av Bayes Decision Rule og Support Vector Machines. 

TTT4185_assignment_3a_2020-10-19: Klassifisering ved av Deep Neural Networks

TTT4185_assignment_3b_2020-10-19: Regresjonsanalyse
