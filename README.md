# DeepFRIer

Get GO terms predictions from DeepFRI JSON files.

```bash
usage: DeepFRIer [-h] -m MODEL -o OUTPUT directory

Extracts info from JSON files created by DeepFRI

positional arguments:
  directory             Directory containing DeepFRI JSON files

options:
  -h, --help            show this help message and exit
  -m MODEL, --model MODEL
                        DeepFRI model. One of: cnn_bp, cnn_cc, cnn_ec, cnn_mf, gcn_bp, gcn_cc, gcn_ec, gcn_mf
  -o OUTPUT, --output OUTPUT
                        Output file (TSV)
```
