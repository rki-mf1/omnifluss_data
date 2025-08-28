# VCF

## `test.spec_case.filtered.vcf`

- input to test the local process `INV_RESCUE_VARIANTS_PYTHON`
  - contains one variant that matches the filter for special treatment:
    - `QUAL > 9999` and
    - `FILTER != 'PASS'` and 
    - `AF >= 0.9`
  - contains one variant that does not match