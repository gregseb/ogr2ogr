This version is for compatibility with older versions of ogr2ogr which can't yet write output to stdout, and writes to a file in the tmpdir instead.

## Troubleshooting

If you are using a Homebrew version of `ogr2ogr` along with MAMP, be sure to
add the Homebrew library path to the MAMP envvars file (/Applications/MAMP/Library/bin/envvars)

Under `DYLD_LIBRARY_PATH="/Applications/MAMP/Library/lib:$DYLD_LIBRARY_PATH"`
add `DYLD_LIBRARY_PATH="/usr/local/lib:$DYLD_LIBRARY_PATH"`
