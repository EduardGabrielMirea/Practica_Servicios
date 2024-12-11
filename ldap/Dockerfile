FROM osixia/openldap:1.5.0

ENV LDAP_ORGANISATION="minombreapellido.local"
ENV LDAP_DOMAIN="minombreapellido.local"
ENV LDAP_ADMIN_PASSWORD="ieselcaminas"
COPY ldap_init.ldif /container/service/slapd/assets/config/bootstrap/ldif/custom/

EXPOSE 389
