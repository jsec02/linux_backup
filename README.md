### backup_script

A comprehensive backup automation script built on [Restic](https://github.com/restic/restic) with dual-repository redundancy. Backs up configuration files, code, documents, and system state to both a local Raspberry Pi (SFTP) and [Backblaze B2](https://www.backblaze.com/cloud-storage) (cloud). Features include automated retention policies, integrity checking, and single-command execution of all backup jobs.

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell                1             72             36            203
Markdown                          1              8              4             20
--------------------------------------------------------------------------------
SUM:                              2             80             40            223
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
backup_system
├── backup
└── README.md

1 directory, 2 files
```
<!-- PROJECT_STRUCTURE_END -->
