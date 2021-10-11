# Description

This repo contains BeSpoke patches listed through the following webapp : https://github.com/fredericlb/BespokeSynth-Sharing-Webapp .

# How it works

For every patch added the `create_manifest.py` script is to be called (with the project folder name as first argument). It will :

- Parse the bsk file (no specific name needed), searching for layout and scripts/comments
- Look for mp3 file for audio samples
- Read the mandatory `README.md` file to fill attributes used by the webapp

# Submitting a patch

1. To submit a patch you should fork this repository and add your patch in a new folder following this pattern : `{author_name}__{patch_name}`. 
3. You also need at least a `README.md` file with the following attributes : Title, Tags, Author and Summary. You can also provide a description after these attributes in a standard markdown format. 
4. You can then submit the PR, a maintainer will run the Python file once your patch has been merged
