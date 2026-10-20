# DPT-data
Delay-Dependent Turn-Off Energy Modeling and Sparse Calibration of Si/SiC Hybrid Switches
# IKW25 and IKW40 raw waveform CSV files

This package contains all CSV files found in the IKW25 and IKW40 source
directories at packaging time. Original CSV bytes, filenames, and relative
directory structure are preserved. Excel, MATLAB, and PDF files are excluded.

## Files

- `IKW25-raw-waveforms.zip`: 264 original CSV files.
- `IKW40-raw-waveforms.zip`: 275 original CSV files.
- `file-manifest.csv`: relative path, byte size, and SHA-256 for every CSV.
- `SHA256SUMS.txt`: SHA-256 checksums for the two ZIP archives.

Extract both archives into the same directory to obtain the IKW25 and IKW40
folders. Every archived CSV was read back and its SHA-256 compared against
the source bytes used during packaging.

## Publication metadata to complete before publishing

Add the paper title, authors, affiliations, dataset description, waveform
column definitions and units, experimental conditions, filename conventions,
relationship to paper figures, and a selected data license. These scientific
details have not been inferred from filenames.

Companion repository: https://github.com/ZYGM233/DPT-data

Upload the ZIP archives, file manifest, and checksum file as GitHub Release
assets. They are prepared locally and have not yet been uploaded.
For DOI-based citation, optionally archive the dataset on Zenodo and add its
published DOI to the repository README.
