RUN      groupadd tomcat && \
        useradd -s /bin/false -g tomcat -d /opt/tomcat tomcat && \
        chown -R tomcat /opt/tomcat
ENV CATALINA_HOME /opt/tomcat
ENV PATH $CATALINA_HOME/bin:$PATH
# CMD catalina.sh run
