# hammerdb
Wrapper scripts for running hammerdb automatically.  These wrappers scripts may
be run from zathras by hand.

Note the versions directories should never have their content updated.

Files:
bin: Location of scripts
version_<#.#>: A specific version of the scripts
versions: File that maps the version numbers  
   format:
	version:<description>:<git path>

note the entry "latest" is expected to be in the file.

The version file is used by zathras to know what to pull down.
