FROM ansibleplaybookbundle/apb-base

LABEL "com.redhat.apb.spec"=\
""

COPY playbooks /opt/apb/actions
COPY . /opt/ansible/roles/test-apb-1
RUN chmod -R g=u /opt/{ansible,apb}
USER apb