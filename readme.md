# Git Pretty Stats

I didn't create this library, [Niklas Modess](https://github.com/modess) did. I extracted it from his [git-pretty-stats](https://github.com/modess/git-pretty-stats) project to include it in the [GitList](https://gitlist.org) project.

For that reason I do not include tests, publish this to [packagist](https://packagist.org), or anything but the files themselves seperated from his project that uses this and wraps it in a ready to go package.

If you use this, you are responsible to provide a way to read the file system, a respository object, and means of displaying the data. See orginal project to view what data this library provides.

License is MIT from the orginal project.

I removed the email alias dependency and added the ability get the commit data
for a single contributor via email address. I also modified the returned data
for a single contributor.
