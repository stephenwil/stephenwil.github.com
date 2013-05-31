---
layout: post
title: "Using GruntJS"
description: ""
category: "web-development"
tags: ["grunt, recess"]
---

Customising the default twitter bootstrap grid is really easy because of the use of less, which enables single point tweaks to change a lot of the grid CSS structure after compilation. Compiling less into CSS in easy on windows using node using the less compiler. Bootstrap recently came up with the recess compiler which also lints, compresses and combines CSS & less files.

Recess is available as a node package and now also available as a grunt package.

Grunt makes use of nodeJS as a build tool, negating the use of trying to get make files to run under windows.

Out-of-the-box grunt concatenates,compresses,lints & combines js files, as well as running a web server to allow unit tests to be run. It runs various tasks, all controlled via a single in-folder config file – grunt.js but when coupled with additional node packages, e.g. Grunt-recess, lots of build tasks can be performed in one operation. Grunt-recess is a grunt wrapper for recess allowing less & CSS compilation etc too.

Looks like lots of other grunt tasks are available for node, making it a popular node base package.