# Iris Experiments

Azure ML demo using iris training experiments

## Dependencies

Install Azure ML Python SDK

```
pip install azureml-core
```

This experiment supports running the train script both locally and on a remote Azure ML compute.
Just remove `compute_name` parameter from `ScriptRunConfig` in the notebook.