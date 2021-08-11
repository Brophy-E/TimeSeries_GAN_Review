# TimeSeries_GAN_Review
A Survey and Taxonomy of recent GANs developments in time series. 

Please refer to the details in our recent review paper [“Generative Adversarial Networks in Time Series: A Survey and Taxonomy”](https://arxiv.org/pdf/2107.11098.pdf) available on ArXiv and submitted for peer-review. Authored by: [Eoin Brophy](https://scholar.google.com/citations?user=p23N6JkAAAAJ&hl=en&oi=ao), [Zhengwei Wang](https://scholar.google.com/citations?user=TaYR7cMAAAAJ&hl=en), [Qi She](https://scholar.google.com/citations?user=iHoGTt4AAAAJ&hl=en) and [Tomas E. Ward](https://scholar.google.com/citations?user=dL7lCKUAAAAJ&hl=en). We provide a list of papers related to GANs on time series. 


## Citation

If you find this repo helpful in any way please consider citing our paper:

    @misc{brophy2021generative,
      title={Generative adversarial networks in time series: A survey and taxonomy}, 
      author={Eoin Brophy and Zhengwei Wang and Qi She and Tomas Ward},
      year={2021},
      eprint={2107.11098},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
    }
    
    
We have classified the time series GAN-variants into two research lines based on recent GAN developments. We also provide a list of papers related to GANs on time series in the `GAN_TS.csv` file. Below, we provide a links to the code of novel methods listed in the review paper models. 

## Datasets
Unlike computer vision having lots of well-known and large-scale benchmarking datasets, time series benchmarking datasets are limited due to generalization and some privacy issues especially for clinical data. Below we provide some resources of well-known time series datasets. Hopefully it is useful. **Feel free to suggest any well-known time series datasets to this repo by opening new issue**. We will review it and add it to the list! We hope this can help push the time series research forward!

* [Oxford-Man Institute realised library (Updated Daily)](https://realized.oxford-man.ox.ac.uk/). Real Multivariate Time Series dataset contains 2,689,487 instances and 5 attributes.
* [EEG Motor Movement/Imagery Dataset (2004) ](https://physionet.org/content/eegmmidb/1.0.0/). Real Multivariate Time Series contains 1,500 instances and 64  attributes.
* [ECG 200 (2001)](http://www.timeseriesclassification.com/description.php?Dataset=ECG200). Real Univariate Time Series contains 200 instance and 1 attribute. 
* [Epileptic  Seizure  Recognition  Dataset (2001)](https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition). Real Multivariate Time Series dataset contains 11,500 instances and 179 attributes.
* [TwoLeadECG (2015)](http://www.timeseriesclassification.com/description.php?Dataset=TwoLeadECG). Real Multivariate Time Series dataset contains 1,162 instances and 2 attributes.
* [MIMIC-III Clinical Database (2016)](https://physionet.org/content/mimiciii/1.4/). Real, Integer & Categorical Multivariate Time Series.
* [MIMIC-III Clinical Database Demo (2019)](https://physionet.org/content/mimiciii-demo/1.4/). Real, Integer & Categorical Multivariate Time Series.
* [EPILEPSIAE project database](http://www.epilepsiae.eu/project_outputs/european_database_on_epilepsy). Real Multivariate Time Series dataset contains 30 instances.
* [PhysioNet/CinC](https://physionet.org/news/post/231). Lots of clinical data for challenging competition.
* [Wrist PPG During Exercise (2017)](https://physionet.org/content/wrist/1.0.0/). Real Multivariate Time Series dataset contains 19 instances and 14 attributes.
* [MIT-BIH Arrhythmia Database (2001)](https://physionet.org/content/mitdb/1.0.0/).  Real Multivariate Time Series dataset contains 201 instances and 2 attributes.
* [KDD Cup Dataset](https://kdd.org/kdd-cup). Lots of Real, Integer & Categorical  Multivariate Time Series datasets.
* [PeMS Database (updated daily)](https://dot.ca.gov/programs/traffic-operations/mpr/pems-source). Real, Integer & Categorical  Multivariate Time Series datasets.
* [Nottingham Music Database](http://abc.sourceforge.net/NMD/). Special Text Format Time Series. 

## Discrete-variant GANs
* [SeqGAN](https://arxiv.org/pdf/1609.05473.pdf): [TensorFlow](https://github.com/LantaoYu/SeqGAN); [PyTorch](https://github.com/suragnair/seqGAN)
* [ Quant GAN](https://arxiv.org/pdf/1907.06673.pdf): Code to be added

## Continuous-variant GANs
* [C-RNN-GAN](https://arxiv.org/pdf/1611.09904.pdf): [TensorFlow](https://github.com/olofmogren/c-rnn-gan); [PyTorch](https://github.com/cjbayron/c-rnn-gan.pytorch)
* [RCGAN](https://arxiv.org/pdf/1706.02633.pdf): [TensorFlow](https://github.com/ratschlab/RGAN)
* [SC-GAN](https://www.springerprofessional.de/en/continuous-patient-centric-sequence-generation-via-sequentially-/16671112): Code to be added
* [NR-GAN](https://dl.acm.org/doi/abs/10.1145/3366174.3366186): Code to be added
* [Time GAN](https://papers.nips.cc/paper/2019/file/c9efe5f26cd17ba6216bbe2a7d26d490-Paper.pdf): [TensorFlow](https://github.com/jsyoon0823/TimeGAN)
* [SigCWGAN](https://arxiv.org/pdf/2006.05421.pdf): [PyTorch](https://github.com/SigCGANs/Conditional-Sig-Wasserstein-GANs)
* [DAT-CGAN](https://arxiv.org/pdf/2009.12682.pdf): Code to be added
* [SynSigGAN](https://www.mdpi.com/2079-7737/9/12/441): Code to be added
