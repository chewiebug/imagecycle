### note on this fork

This is just an exact copy of a7digital/imagecycle including the two pending pull requests [#3](https://github.com/a7digital/imagecycle/pull/3) and [#4](https://github.com/a7digital/imagecycle/pull/4) and a changed version. As soon as the pull requests are merged in the parent repository, this fork is not needed any more.

# TYPO3 Extension Imagecycle

This repository is a fork of the currently unmaintained TYPO3 Extension
[Imagecycle](https://typo3.org/extensions/repository/view/imagecycle).

## Remarks

The scope is to bring back functionality and compatibility in newer versions of TYPO3 CMS. There are no further aims to continue maintaining this extension on a voluntary basis. However, it's up to anybody to pick the source code and integrate further enhancements or changes - it's Open Source using GPLv2.

## Side notes

Various parts have been adjusted to be compatible with TYPO3 CMS 7 LTS and 8 LTS again. Besides that, the previous custom TCA user functions that have been used in the FlexForm structures have been replaced as much as possible by a cleaner way following the new FormEngine paradigms, that have been introduced during the development phase of TYPO3 CMS 7. Custom ExtJS components have been replaced by accordant TYPO3 Core functions, based on jQuery and Bootstrap.

However, a jQuery/TWBS color-picker is not yet implemented - neither in this extension nor in the TYPO3 Core. That's why the "old" color picker of the TYPO3 Core is being used again (find further details in issue [#73728](https://forge.typo3.org/issues/73728)).

## Inspiring People to Share

May this extension upgrade for TYPO3 CMS 7 LTS and 8 LTS be helpful to you... :-)
