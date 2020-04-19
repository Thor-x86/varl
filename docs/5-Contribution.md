

**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | [2](https://github.com/Thor-x86/varl/blob/master/docs/2-Data_Types.md) | [3](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md) | [4](https://github.com/Thor-x86/varl/blob/master/docs/4-Do_and_Dont.md) | 5 |  
  
# Contribution  

Everyone has the right to contribute. However, we need rules to make sure this project tidy as possible.

## Version Scheme System

The standard versioning system :

> **aa.bb.cc-dddd**

Those **a**, **b**, and **c** must be **unsigned integer**. There are explanations for each indicator:

- **a = Major Version**
The major version will be increased if new feature or big change happens. Only maintainer who allowed to increase major version

- **b = Minor Version**
Minor version should be increased if big fix happens. If you feels your commit is considered big fix, you may increase the minor version. However, maintainer can move the increment as revision instead, if the fix isn't big enough.

- **c = Revision Number**
Small fix, typo fix, and little optimization will increases the revision number. Each time you commit for those, please increase the revision number.

- **d = Release Flag**
The release flag only either **LTS** (Long Term Support) or **beta** (for experimental public version). Otherwise, the "-dddd" part must be omitted.

## Long Term Support (LTS)

We need to carefully handle LTS because this is what business people and newbies rely on. One big problem on this release flag, everyone will start blame on .varl as unreliable. Therefore, we need rules for LTS:

- Only maintainer that set a live version as LTS under community approvement.
- To keep maintain stability, the revision number must be replaced as "x", as example **3.2.x-LTS** instead of **3.2.4-LTS**
- Latest LTS cannot older than 3 years. If this break, please remind maintainer.
- Every .varl related repositories can **have their own version** and LTS flag, but they must state which version of this repository that they follow.

## Git Branch

Branch of every .varl related repository should be reserved for master (for working branch) and their own LTS version including this repository. So, other contributors can understand which version to follow.

## Before you do commit

To make commit history looks a lot consistent, please follow this commit message formatting:

    [aa.bb.cc-dddd]
    - The 1st change and its reasons
    - The 2nd change and its reasons
    - The 3rd change and its reasons
    - ...

Where **aa.bb.cc-dddd** is version which follows as explained above. The [changelogs](https://github.com/Thor-x86/varl/blob/master/CHANGELOGS.md) will be written by maintainer. However, anyone can also write the changelogs before commit. That's really helpful :)
  
##
  
**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | [2](https://github.com/Thor-x86/varl/blob/master/docs/2-Data_Types.md) | [3](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md) | [4](https://github.com/Thor-x86/varl/blob/master/docs/4-Do_and_Dont.md) | 5 |  