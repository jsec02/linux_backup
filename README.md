### backup_system

A comprehensive backup automation system built on [Restic](https://github.com/restic/restic) with dual-repository redundancy. Backs up configuration files, code, documents, and system state to both a local Raspberry Pi (SFTP) and [Backblaze B2](https://www.backblaze.com/cloud-storage) (cloud). Features include automated retention policies, integrity checking, and single-command execution of all backup jobs.

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell               18            160            183            360
Markdown                          1              8              4             38
--------------------------------------------------------------------------------
SUM:                             19            168            187            398
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
backup_system
├── logs
├── README.md
└── scripts
    ├── backup-all
    ├── backup-check
    ├── bash-backup
    ├── database-backup
    ├── direnv-backup
    ├── helix-backup
    ├── nvim-backup
    ├── package-backup
    ├── powershell-backup
    ├── python-backup
    ├── sql-backup
    ├── sqliterc-backup
    ├── ssh-backup
    ├── vault-backup
    ├── wsl-backup
    ├── wt-backup
    ├── zellij-backup
    └── zshrc-backup

3 directories, 19 files
```
<!-- PROJECT_STRUCTURE_END -->
