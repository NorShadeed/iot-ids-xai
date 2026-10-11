# Dataset placement

The training data is intentionally not committed to this repository.

Set the input path before running the training notebook:

```bash
# PowerShell
$env:IOT_IDS_DATASET = "C:\path\to\iot-traffic.csv"

# macOS/Linux
export IOT_IDS_DATASET="/path/to/iot-traffic.csv"
```

The notebook expects a numeric feature table suitable for its clustering and binary-classification workflow. Review column types, missing values, provenance, and usage rights before training.
