# RNA-seq Training

## Quick Start

Run the nf-core/rnaseq test pipeline:

```bash
cd /workspaces/rnaseq-tutorial/training
nextflow run nf-core/rnaseq -r 3.12.0 -profile docker,test --outdir results_test -resume
```

## Options

- `-r 3.12.0` - Pipeline version
- `-profile docker,test` - Use Docker containers with test dataset
- `--outdir results_test` - Output directory
- `-resume` - Resume from cached results if available
- `-c nextflow.config` - Use custom config (optional, auto-detected in current directory)
