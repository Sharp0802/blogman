# BlogMan

![](https://img.shields.io/github/commit-activity/m/Sharp0802/blogman)
![](https://img.shields.io/github/languages/code-size/Sharp0802/blogman)
![](https://img.shields.io/github/license/Sharp0802/blogman)
![](https://img.shields.io/github/v/tag/Sharp0802/blogman)
![](https://img.shields.io/github/actions/workflow/status/Sharp0802/blogman/dotnet.yml?branch=master)
![](https://img.shields.io/github/repo-size/Sharp0802/blogman)

A cross-platform static blog webpage generator, written in C#.

## GETTING STARTED

See [wiki](https://github.com/Sharp0802/blogman/wiki/Getting-Started).

## PREVIEW

![](img/screenshot.png)

- My [blog](https://sharp0802.github.io) generated with `blogman`.

## SECURITY

`blogman` uses razor templating system.
Because of not only that razor template uses C# scripting internally
also that `RazorEngine` library has its own security vulnerability(remote code execution),
Using untrusted template file can be harmful to host computer.
Thus, do **NOT** use template file you cannot trust.
