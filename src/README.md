# Production Workflows Documentation

This document outlines the directory structure and organization of the production workflows used in the n8n_prod repository.

## Directory Structure

```
src/
└── workflows/
    ├── workflow1/
    │   ├── description.md     # Description of workflow1
    │   └── ...                # Additional files related to workflow1
    ├── workflow2/
    │   ├── description.md     # Description of workflow2
    │   └── ...                # Additional files related to workflow2
    └── ...
```

## Organization
- Each workflow resides in its own directory under `src/workflows/`.
- Each directory must contain a `description.md` file that provides details about the respective workflow.
- Additional files related to each workflow can be added as necessary to facilitate understanding and usage.

## Purpose
This structure is designed to allow for easy navigation and understanding of the various production workflows in this repository.

## Maintenance
Users are encouraged to update the organization and descriptions as workflows are added or modified.