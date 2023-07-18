# dirmark

This is (to be) a directory bookmarker. I wrote (am writing) it to integrate into xplr.

Usage:

    dirmark add <directory> /path/to/dirmarks.yaml

    # Pipe the output into FZF
    dirmark list <current_directory> /path/to/dirmarks.yaml

    dirmark choose <directory> /path/to/dirmark.yaml

What sets this apart from all the zillions of existing directory bookmarkers? "dirmark list" filters current_directory out of the list, and "dirmark choose" moves directory to the top of the list. This
allows you to very quickly jump back and forth between two directories, and thus get what you actually
want from a Miller Columns user experience without actually needing one.