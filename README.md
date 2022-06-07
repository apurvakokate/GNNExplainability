# GNNExplainability

Use conda env create --file packages.txt to create conda environment with necessary packages

Run python experiment_replication.py to run experiment.

Configs are present in the config directory. Look at ExplanationEvaluation/configs/replication/explainers/pgexplainer/ba2motifs.json to update configuration if necessary (such as changing logging folder)

Graphical results will be generated in runs/<config.log_folder>

Quanlitative results will be generated in qualitative/ directory

You can visualize the results by running  tensorboard --logdir=runs/<config.log_folder>/ --reload_multifile=true --reload_multifile_inactive_secs=-1
