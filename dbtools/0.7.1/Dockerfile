FROM busybox:1.32

ENV TOOL_LIQUIBASE_VERSION="0.17.1.RELEASE"

ADD --chown=www-data:www-data https://nexus.choerodon.com.cn/repository/choerodon-maven/io/choerodon/choerodon-tool-liquibase/0.17.1.RELEASE/choerodon-tool-liquibase-0.17.1.RELEASE.jar \
    /var/choerodon/choerodon-tool-liquibase.jar

USER 33