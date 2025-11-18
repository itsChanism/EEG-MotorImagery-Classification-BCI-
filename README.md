# EEG Motor Imagery Time-Series Classification

**Description**  
This Python project processes EEG time-series for motor imagery (MI) classification. Two tasks were implemented:  
- Left vs Right Hand MI (~70% accuracy)  
- Hand vs Feet MI (~95% accuracy)  
The pipeline includes preprocessing (filtering, re-montaging, epoching), visualization (topographic maps, time-frequency plots), and classification (CSP+LDA, SVM, neural nets).

**Key Features**  
- Filtering (7–30 Hz), epoching, artifact removal  
- Extensive visualizations using MNE and Matplotlib/Seaborn  
- Model benchmarking with 10-fold cross-validation, channel-set comparisons  
- Architecture comparisons and result summaries  

