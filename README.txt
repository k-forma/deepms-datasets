Download the verified data files from:
https://github.com/k-forma/deepms-datasets/releases/tag/paper-datasets-20261125

DeepMS synthetic machining datasets

Download all three_class-data-*.zip, six_class-data-*.zip, and dataset-splits-and-documentation.zip.
Extract ALL ZIPs into the SAME folder. Each shard is a standalone ZIP; do not concatenate files.
Each dataset contains 1,080,000 H5 samples at 128 x 128 x 128 resolution.
Sample IDs are relative to the corresponding seq_h5 folder, without the .h5 extension.

Use the supplied original split lists without reshuffling:
- Three-class baseline: 972000 train / 54000 validation / 54000 test.
- Three-class refinement: use refinement_train_val_test_split.json; 30000 test samples.
- Drill scorer subset: 10000 train / 1000 validation, listed separately.
- Six-class: 972000 train / 54000 validation / 54000 test.
Baseline validation results use validation; final refinement results use test.

See LICENSE.txt for reuse terms and CITATION_AND_SOURCE.txt for attribution.
Verify downloads using SHA256SUMS.json.
