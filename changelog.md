# 1.1.5

-    New utils module.
-    Output syntax errors in stdout.

# 1.1.4

-    Fix: issue with MkDocs: raw svgs are now wrapped in div tag.

# 1.1.3

-    Fix: as_image takes effect only with `svg` format.

# 1.1.1

-    Remove src param. (Use includes instead)
-    Allow separate tags fail. Preprocessor would issue warning and continue work.

# 1.1.0

-    Paths from src attribute now are relative to current file (breaks backward compatibility)
-    svg images height\width are now set to 100% by default (switch off: set fix_svg_size option to false)

# 1.0.6

-    Added as_image option.

# 1.0.4

-    Moved combined_options out

# 1.0.2

-    Fixed external diagrams not reloading on change.
-    Fixed external diagrams are not crashing preprocessor if the file is missing.

# 1.0.1

-    Added 'src' tag option to load diagram source from external file.

# 1.0.0

-    Initial release