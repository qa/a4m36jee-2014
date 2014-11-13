Advanced Java EE Lab
====================

Seminars for A4M36JEE course at CTU in Prague, FEE (2014).

https://developer.jboss.org/wiki/AdvancedJavaEELabpodzim2014

Checkout of the project:
------------------------

    git clone --recursive https://github.com/qa/a4m36jee-2014.git
    cd a4m36jee-2014/
    git submodule foreach 'git checkout $name-00'

Download maven dependencies & install
-------------------------------------

    mvn clean install -Dmaven.test.skip=true
