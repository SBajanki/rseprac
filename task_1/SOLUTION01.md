Rename the file using the following bash script in linux

for f in *; do mv -- "$f" "${f%.\*}.dat"; done
