# Arrhythmia-identification-from-ECG

## Product Overview
Early detection of arrythmia is crucial as it could be life threatening while showing no symptoms. This solution helps in classifying each peak in the Electrocardiogram waveform data (even from multiple leads) into the following categories: Normal, Premature ventricular contraction, Paced beat, Right bundle branch, Left bundle branch, Atrial premature beat, Ventricular flutter wave, Ventricular escape beat. The input format for training and inference is standard Waveform Database Format (WFDB). The solution uses a CNN based deep learning model that can be personalised for each patient. On the inference data each peak is timestamped and classified into the above mentioned categories and presented as a json. The solution is intended to be used for auxillary/support only.

## Product Highlight
* The solution can be used for remote patient monitoring by providing early warning and alerts. With wearable devices collecting ECG data, the solution also extends to Federated Machine Learning scenarios with hyper-personalised models for patients. 
* The solution adheres to standard Waveform Database file format which can be easily integrated with other healthcare data platforms. The pre-processing mechanism can identify peaks in the waveform data and automatically split in format required for the deep learning format.
* Mphasis DeepInsights is a cloud-based cognitive computing platform that offers data extraction & predictive analytics capabilities. Need customized Machine Learning and Deep Learning solutions? Get in touch!
