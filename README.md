# tf2-checkpoint-variable-rename (originally forked from https://gist.github.com/batzner/7c24802dd9c5e15870b4b56e22135c96)

A CLI to rename variables from a checkpoint model (updated for Tensorflow 2)

# Usage:

`python tf2-checkpoint-variable-rename.py --checkpoint_dir=[CHECKPOINT_DIR] --replace_from=[STRING_TO_REPLACE] --replace_to=[RESULT_STRING]`

Obs: you can check changes before applying them passing a `--dry_run` arg.
