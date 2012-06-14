!SLIDE

# Varför? #

!SLIDE bullets incremental transition=fade

# Agila metoder i utveckling 

* förändring är naturlig
* små men frekventa steg
* lean

!SLIDE bullets incremental transistion=fade

# Molnet #

* Verktyg för att hantera konfiguration
* API:er för att hantera infrastruktur

!SLIDE

# Vad #

!SLIDE smaller commandline incremental

    $ git branch 
      dev
    * master
      ops

    $ git merge dev
    Updating b0c5007..09a5ba3
    Fast-forward
    devops.pp |    1 +
    1 file changed, 1 insertion(+)

    $ git merge ops
    Auto-merging devops.pp
    CONFLICT (content): Merge conflict in devops.pp
    Automatic merge failed; fix conflicts and then commit the result.
    
    $ git mergetool
    
    $ git commit -a -m "Merged dev and ops"
    git commit -a -m "DevOps"
    [master b0449d4] DevOps

    $ cat devops.pp

!SLIDE smaller code

                              .sssssssss.
                        .sssssssssssssssssss
                      sssssssssssssssssssssssss
                     ssssssssssssssssssssssssssss
                      @@sssssssssssssssssssssss@ss
                      |s@@@@sssssssssssssss@@@@s|s
               _______|sssss@@@@@sssss@@@@@sssss|s
             /         sssssssss@sssss@sssssssss|s
            /  .------+.ssssssss@sssss@ssssssss.|
           /  /       |...sssssss@sss@sssssss...|
          |  |        |.......sss@sss@ssss......|
          |  |        |..........s@ss@sss.......|
          |  |        |...........@ss@..........|
           \  \       |............ss@..........|
            \  '------+...........ss@...........|
             \________ .........................|
                      |.........................|
                     /...........................\
                    |.............................|
                       |.......................|
                           |...............|


!SLIDE bullets incremental transition=fade
# Agil infrastruktur #
* "agility in coding, agility in systems"
* molnet har förändrat hur infrastrukturen skapas


!SLIDE bullets incremental transition=fade
# Infrastrukturen är en applikation #
* allt drivs av API:er
    * Applikationen är API:er
    * Infrastrukturen är API:er


!SLIDE bullets incremental transition=fade
# Infrastruktur som kod #
* deklarativ
* abstrahera hur
* förutsägbar
* återskapningsbar

