findfile_path
=============

Find the first instance of a fine on a path of directories, with
possible file extensions.

::

  $ pip install findfile_path

::

findfile_path (fname, path, exts = None):

fname can be either a single string or Path object, or an iterable of
strings or Path objects.  The first matching file in the first
directory on path ( a list of strong or Path objects) with the first
extension is returned, else None.
