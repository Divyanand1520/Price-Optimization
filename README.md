# Price-Optimization

artifact_path: pricing_model
flavors:
  python_function:
    env:
      conda: conda.yaml
      virtualenv: python_env.yaml
    loader_module: mlflow.sklearn
    model_path: model.pkl
    predict_fn: predict
    python_version: 3.11.11
  sklearn:
    code: null
    pickled_model: model.pkl
    serialization_format: cloudpickle
    sklearn_version: 1.6.1
mlflow_version: 2.22.0
model_size_bytes: 6354463
model_uuid: b170b28517194a6ea1c062cfd7214610
prompts: null
run_id: 4e43453fbbc14286a863fbbbe5b999fe
utc_time_created: '2025-09-13 08:20:59.604982'
