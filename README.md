# ERP Test
Testing dsp, feature extraction, and classification with publicly available EEG dataset

[Multi-channel EEG recordings during a sustained-attention driving task (raw dataset)](https://www.nature.com/articles/s41597-019-0027-4)

[Datasets](https://figshare.com/articles/dataset/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task_preprocessed_dataset_/7666055/3)

[Matlab guide](https://figshare.com/articles/dataset/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task/6427334/5?file=14252852)

[MNE-Python Install](https://mne.tools/stable/install/manual_install.html#manual-install)

Papers:
- [A compact multi-branch 1D convolutional neural network for EEG-based motor imagery classification](https://www.sciencedirect.com/science/article/pii/S1746809422009107)
- [https://iopscience.iop.org/article/10.1088/1741-2552/ac4430/meta](https://iopscience.iop.org/article/10.1088/1741-2552/ac4430/meta)
- [P300 event-related potential detection using one-dimensional convolutional capsule networks](https://www.sciencedirect.com/science/article/pii/S0957417421001421)

Create a new conda environment named "bci-test"
```
conda create --strict-channel-priority --channel=conda-forge --name=bci-test mne-base h5io h5py pymatreader numpy matplotlib jupyterlab
conda activate bci-test
jupyter-lab
```
