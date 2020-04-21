# typo3-classic

Install DDEV TYPO3 environment based on the classic symlink installation.

*Not an official TYPO3 package!*

```bash
mkdir my-typo3-site
cd my-typo3-site
ddev config --project-type=php
ddev start
ddev composer create zotornit/typo3-classic:^9.5 --no-interaction --prefer-dist
ddev config --docroot=htdocs --project-type=typo3
ddev restart
```

**Available versions:** 8.5.x, 9.5.x, 10.4.x


### Idea/sources:
* https://github.com/GsTYPO3/ddev-typo3-src
