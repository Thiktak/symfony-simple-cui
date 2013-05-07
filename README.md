Symfony Simple CUI
------------------

This is a program which simplify the creation of Symfony2 project and its use (console mode)

# What I can do ?

* Install/update __composer.phar__
* Install (init) new __symfony__ project (symfony/framework-standard-edition)
* Symfony commands ... shorter !

## How to use ?

    sf 

or

    sf cmd

or

    sf cmd more options


And the CUi :


    This is a bash script to simplify the symfony commands.

    Version v0.0.1 2013-05-08 @author Olivares Georges [http://github.com/Thiktak]

    Usage : sf [cmd] [more]

    Help :
        e             execute 'php app/console' command 

        ai            assets:install

        ad            assetic:dump

        cc            cache:clear

        dgc           doctrine:generate:crud
        dgey          doctrine:generate:entity
        dges          doctrine:generate:entities
        dgf           doctrine:generate:form
        dsu           doctrine:schema:update
        dsv           doctrine:schema:validate

        gb            generate:bundle
        gc            generate:controller

        rd            router:debug

        cp            Execute composer.phar command
        cp:d          Download composer.phar
        cp:u          php composer.phar update

        sf:chm        Apply chmod to app/logs and app/cache
        sf:env        Update environment
        sf:init       Initialize symfony

        self-update   Update script


# How to install ?

## With CURL
  
    curl -L -sS http://goo.gl/6QaT7 > sf
