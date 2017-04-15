# Trilead API Plugin

A similar concept to the bouncycastle-api-plugin, this plugin provides the Trilead library to any dependent plugins in
an easily update-able manner.

Prior to this plugin being introduced, Trilead was bundled in Jenkins core and either required all plugins use the version
in core; or that plugins bundle Trilead and mask the Trilead classes, and potentially end up with broken compatibilties
between plugins.

Users should not generally need to install this plugin directly as it provides no extended features for Jenkins, instead
it should be installed as a dependency of other plugins that require access to Trilead classes, normally for performing
SSH client activities.
