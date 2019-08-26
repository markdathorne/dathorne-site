ARG TOMCAT_VER
ARG JRE_VER
ARG DIST

FROM magnolia/magnolia-base:${TOMCAT_VER}-${JRE_VER}-${DIST}

ARG MGNL_VER

RUN wget -nv https://sourceforge.net/projects/magnolia/files/magnolia/Magnolia%20CE%206.1.1/magnolia-community-demo-webapp-6.1.1.war/download -O $CATALINA_HOME/webapps/ROOT.war