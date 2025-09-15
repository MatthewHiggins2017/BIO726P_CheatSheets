## BIO726P Cheat Sheet


### Instructor Guidance

The practicals in this module are sequential and build upon one another. If a student misses a session, falls behind, or joins the module late, it may affect their ability to complete later practicals.

To help students catch up, please follow the steps below:

### Steps

1) Identify what practicals have not been successfully completed by the student. 

2) Log into Apocrita. Then for each missing practical you will need to scp the relevant tarball from the HPC into the students Virtual Machine (VM)

| Day         | Practical Name                | SCP Command                                                                                  |
|-------------|-------------------------------|---------------------------------------------------------------------------------------------|
| Day 2  | 2025-09-22-read_cleaning      | `scp /data/SBCS-MSc-BioInf/2025/BIO726P_CheatSheets/2025-09-22-read_cleaning.tar.gz bob@bob.genomicscourse.com:` |
| Day 3  | 2025-09-23-assembly           | `scp /data/SBCS-MSc-BioInf/2025/BIO726P_CheatSheets/2025-09-23-assembly.tar.gz bob@bob.genomicscourse.com:` |
| Day 4 | 2025-09-24-gene_prediction    | `scp /data/SBCS-MSc-BioInf/2025/BIO726P_CheatSheets/2025-09-24-gene_prediction.tar.gz bob@bob.genomicscourse.com:` |
| Day 6 | 2025-09-29-genotyping         | `scp /data/SBCS-MSc-BioInf/2025/BIO726P_CheatSheets/2025-09-29-genotyping.tar.gz bob@bob.genomicscourse.com:` |
| Day 6  | 2025-09-29-mapping            | `scp /data/SBCS-MSc-BioInf/2025/BIO726P_CheatSheets/2025-09-29-mapping.tar.gz bob@bob.genomicscourse.com:` |
| Day 7  | 2025-09-30-population_genetics| `scp /data/SBCS-MSc-BioInf/2025/BIO726P_CheatSheets/2025-09-30-population_genetics.tar.gz bob@bob.genomicscourse.com:` |


3) After scp the relevant tarball from Apocrita to the students VM. Log into the students VM and decompress the tarball with the following command:

`
tar -xzvf <Practical_ID>.tar.gz
`

