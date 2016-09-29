# EMG_Analyzer
Matlab Toolbox for unsupervised classification of MUAPs and action potentials in EMG

 A complete Graphical interface, plug and play tool for single channel EMG processing and unsupervised MUAP identification and Action Potential classification. Just run LEMG_Analyzer.m and the GUI will be assisting you for the further processing steps. The toolbox is able to read files with '.mat','.wav' and '.txt'. The exported files from several EMG machines such as Nihon Kohden and Synergy are supported as well.
 
The scripts in this toolbox are based on the following paper:

%% Algorithm is based on the following paper :

H. Sedghamiz and D. Santonocito,''Unsupervised Detection and Classification of Motor Unit Action Potentials in Intramuscular Electromyography Signals'', The 5th IEEE International Conference on E-Health and Bioengineering - EHB 2015, At Iasi-Romania.

https://www.researchgate.net/publication/284362981_Unsupervised_Detection_and_Classification_of_Motor_Unit_Action_Potentials_in_Intramuscular_Electromyography_Signals

Please cite the paper in case you might find this toolbox helpful.

INSTRUCTIONS: 
1. Run LEMG_Analyzer.m, in order to invoke the interface; 
2. From the top left Corner of the software, click on the 'Folder' sign in order to select a file (Note, If you open a file with more than one channel only the first channel will be analyzed. '.mat','.wav', and '.txt' are supported). 
3. After loading your dataset, click on 'Optimize TH' in order to let the software estimate the appropriate analysis value for you signal automatically. Alternatively, you can use the scroll-bars in order to set the values manually, the first scroll is the detection sensitivity and the second is the template matching threshold. You can improve the results by tuning these values. 
4. After you are done with the tuning of the parameters, click on 'Start Clustering' and the software automatically identifies the unique MUAP templates in your signal. The templates appear in the lower left corner of the software. You can either select all the templates to be highlighted in your EMG plot or just select the one you are interested in.The window on the lower right corner is the zoomed version of the signal. You can move along the signal from the top panel. 
5. In order to save the analysis, simply click on the 'save' sign on the top left corner of the software. You can also zoom in to a part of your signal and repeat the analysis.

Here is a Youtube link of the software as well; 
https://www.youtube.com/watch?v=Eag2OGpa40M
