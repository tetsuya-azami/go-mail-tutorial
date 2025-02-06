FROM dovecot/dovecot:2.4.0
COPY --from=busybox /bin/busybox /bin/busybox
CMD ["/dovecot/sbin/dovecot", "-F"]
