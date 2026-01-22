# SELinux Policy Merger

SELinux Policy Merger is a small utility designed to merge two custom SELinux policy files into a single policy.

This utility is useful in scenarios where multiple custom SELinux policies need to be consolidated, for example to simplify deployment or policy management.

## Usage

The tool requires two input policy files and a destination file.
If the destination file already exists, it will be deleted before writing the merged output.

```bash
SelinuxPolicyMerger.py --file1 file1_to_merge --file2 file2_to_merge --dest file_merged
