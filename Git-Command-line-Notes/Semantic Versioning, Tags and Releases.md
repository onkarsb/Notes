# Semantic versioning, Tags and Releases

## Semantic versioning

Set of rules and requirements that dictate how version numbers are asigned and incremented.  
For users this indicates the degree of changes in code.

Format :
**MAJOR . MINOR . PATCH-\<pre-release\>**  
X.Y.Z  
X,Y and Z are non-negative integers  

X.Y.Z-alpha  
X.Y.Z-RC1  
pre-release : alpha/beta/release-candidate

1. **Patch**
    * Bug fixes:bug:
    * Bakwards compatible  
    e.g. 1.0.1 -> 1.0.2

2. **Minor changes**
    * Adding functionality (new:sparkles:/improvements:raised_hands:)
    * Backwards compatible  
    e.g. 1.0.2 -> 1.1.0
    
3. **Major changes**
    * Incompatible with previous versions
    * Foundational changes  
    e.g. 1.1.0 -> 2.0.0  
4. **Pre-release**
    * alpha
    * beta
    * release-candidate

## Tags
Tags are used to mark release points
### 1. Lightweight Tags
A basic named pointer to a specific commit
```bash
git tag <tag-name> [commit]
```
### 2. Annotated tags
Stored as full objects in Git database  
Contains tagger  and a tagging message
```bash
git tag -a <tag-name> -m "<annotation>" [commit]
```

## Release
Releases are deployable software iterations you can package and make available for a wider audience to download and use.

* Signifies important changes in your repository  
* Communicates degree of changes between tags  
* Straightforward way to track history of changes

A Release is created from an existing tag and exposes release notes and links to download the software or source code from GitHub. [Read more...](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)
### Release Notes
Should provide detailed information of changes made
1. Patch release
    * List of bug fixes:bug:
2. Minor release
    * List of changes  
        (features : new:sparkles:/improvements:raised_hands:)
    * Usage details
3. Major release
    * List of removals
    * List of additions
    * Upgrade 

## Changelog

* Added ✨ - For any new features that have been added since the last version was released
* Changed - To note any changes to the software's existing functionality
* Deprecated - To note any features that were once stable but are no longer and have thus been removed
* Fixed 🐛 - Any bugs or errors that have been fixed should be so noted
* Removed - This notes any features that have been deleted and removed from the software
* Security 🔒 - This acts as an invitation to users who want to upgrade and avoid any software vulnerabilities
> Or add a github link comparing two releases  

Checkout conventional changelog emojis [here](https://github.com/favoloso/conventional-changelog-emoji)


## Resources 
* [Semantic Versioning and Git Tags on Youtube](https://youtu.be/4wPjo5C-v8Y)
* [Semver.org](https://semver.org/)
* [Git tags](https://git-scm.com/book/en/v2/Git-Basics-Tagging)
* [Tag Generation script](https://github.com/mikemiles86/semtag-generator)
* [Changelog guidelines](https://changelog.md/)