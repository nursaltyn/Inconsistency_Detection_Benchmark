# Misleading through Inconsistency: A Benchmark for Political Inconsistencies Detection

This repository contains code for the paper Misleading through Inconsistency: A Benchmark for Political Inconsistencies Detection.

```
├── 📜 README.md
├── 📂 data
│   ├── 📄 df_gold.csv # The dataset file
│   ├── 📂 model_evaluations # Files with model evaluations results
│   │   ├── 📄 bootstrap_aggregated.pkl
│   │   ├── ...
│   │   └── 📄 prediction_ground_truth_tuples_majority_LLM_3_classes.json
│   └── 📂 qualtrics_survey
│       ├── 📄 change_per_class.pkl
│       └── 📄 question_repeated_trial.pkl
├── 📂 evaluating_models # Model predictions
│   ├── 📄 all_samples_to_responses.pkl
│   ├── 📄 chatgpt35_sample_to_runs.json
│   ├── 📄 chatgpt4_sample_to_runs.json
│   ├── 📄 llama_70B_sample_to_runs.json
│   └── 📄 llama_8B_sample_to_runs.json
├── 📂 notebooks
│   ├── 📝 all_models_evaluation.ipynb
│   ├── 📝 bootstrap_cross_validation_humans.ipynb
│   ├── 📝 interannotator_agreement.ipynb
│   ├── 📝 model_majority_label.ipynb
│   └── 📝 participants_shift.ipynb
└── 📂 visualizations
    ├── 📂 comparison_barplots
    └── 📂 confusion_matrices
```

## License

Code is licensed under the [MIT License](LICENSE).  
All non-code content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Please cite our paper if you use this repository. The citation will be provided soon.
