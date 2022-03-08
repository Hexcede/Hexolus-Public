# Hexolus-Public
A public dump of most of "old-rewrite" Hexolus' existing code &amp; assets.

# License?
Currently this is licensed using the Creative Commons BY-NC-SA license which is somewhat strict. I might loosen this later. Please regard the license. You can find a human-readable breakdown of what this license entails here:
https://creativecommons.org/licenses/by-nc-sa/4.0/

## Package errors
There are a few errors you'll encounter when opening the place, primarily around some "package" stuff. You should be able to ignore these in theory, the reason is because I downloaded an unmodified copy of the place, which contains a `PackageLink` that isn't public. If you want (or need) to restore the functionality, you can republish the `Packages` module under `ServerStorage`, and the live-reloading should automatically find the package's ID from the `PackageLink`.

## What's the purpose of this dump?
This dump contains rewritten code from one of the original versions of a hobby project I worked on for two years (starting in late 2019). The original project, which was primarily just a (bad) POC of the game's concept was the result of a few months of work in early 2019.

I am releasing this code for a few reasons, one of the biggest reasons is mainly just because I would like it to be available for people to gain insight into the project and maybe learn some stuff, but, another reason is because I'd like to put this version of the project to rest somewhat.

I haven't worked on it in over a year, probably a bit closer to two. While I still want to eventually complete it, this version of the code is already not very reflective of my current skill level, and certainly has its fair share of problems. I think that I can all around do better, and should, I just don't really trust this codebase to hold up. (Especially because the live-reloading results in bigger and bigger files and therefore it takes significantly larger and larger amounts of time to update... Using asset version IDs correctly would have been the smart thing to do)

If and when I start up this project officially again, it will definitely be using Rojo & will exist on GitHub (not that it will necessarily be open source). This would give me an enormous amount of freedom to really allow the automated updates to work in a fluid way, and would allow me to bring on real collaborators, and take advantage of proper version control, and therefore all around just result in a better product.
