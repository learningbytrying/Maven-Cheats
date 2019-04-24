# Maven-Cheats

some maven commands 
1) mvn clean install
2) mvn clean install -U  ( force update of repository , nukes the original repo)
3) mvn dependency:tree
4) mvn clean install -DskipTests ( to skip tests)
5) mvn versions:set -DnewVersion=1.0.1.178-AP-SNAPSHOT( to update POM versions across all depedent modules and the parent POM)
