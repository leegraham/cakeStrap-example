# CakePHP Template for OpenShift

## Template App Information
Product: CakePHP
Version: 2.1.1
Source:  https://github.com/cakephp/cakephp.git
Commit:  cc44130fc07abdc0faf438c5c98d636ad6ef1f1c

## Maintenance
This folder contains a diff file that includes the changes made to the
stock CakePHP package in order to make it OpenShift-Template-ready. If
you are a maintainer tasked with updating the CakePHP template, you
may be able to use this patch file on the updated CakePHP code to
automatically reapply these changes.

Here are the steps involved:
1. Under the 'php' directory, apply any patches required to update CakePHP.
2. From the template root directory, run 'git apply --check .openshift/template.patch' to test for patching problems.
3. Next run 'git am --signoff < .openshift/template.patch' to apply the patch to the template.

If this process succeeds, then the changes have been automatically
applied. Otherwise it may be necessary to manually apply the
changes. If the base package has changed enough, you may need to
re-audit the base code and generate a new patch file.
