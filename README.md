## cakeStrap on OpenShift

Easily deploy cakeStrap (CakePHP + Twitter Bootstrap) on OpenShift


## Version Used
 - cakeStrap v0.5
    - Twitter Bootstrap v2.1.0
    - HTML5 Boilerplate v4.0.0
    - Normalize v1.0.1
    - Modernizr v2.6.1
 - CakePHP v2.2
 - openshift/cakephp-example


## Steps-To-Deploy

### From the OpenShift Web UI

See these instructions from the wiki: https://github.com/leegraham/cakeStrap-example/wiki

### From the Command Line

Simply run the following:

`rhc create-app cakestrap php-5.3 mysql-5.1 --from-code https://github.com/leegraham/cakeStrap-example.git -p <password>`

## Notes

CakePHP Security:
    If you're doing more than just 'playing' be sure to edit `app/config/core.php`
    and modify `Security.salt` and `Security.cipherSeed`.


## Questions / Bugs

Have a question or found a bug? Please create an issue [here][] on GitHub!
[here]: https://github.com/leegraham/cakeStrap-example/issues
