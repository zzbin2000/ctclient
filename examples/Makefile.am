noinst_PROGRAMS = ctkey_gen ctkey_pub ctkey_der ctkey_skinfo ctkey_pkinfo

ctkey_gen_SOURCES = ctkey_gen.c b64file.c
ctkey_gen_CFLAGS = -Wall -I ../include -I $(prefix)/include/pbc $(CFLAGS)
ctkey_gen_LDADD = -L../src/.libs/ -lciphrtxt $(LDFLAGS)

ctkey_pub_SOURCES = ctkey_pub.c b64file.c
ctkey_pub_CFLAGS = -Wall -I ../include -I $(prefix)/include/pbc $(CFLAGS)
ctkey_pub_LDADD = -L../src/.libs/ -lciphrtxt $(LDFLAGS)

ctkey_der_SOURCES = ctkey_der.c b64file.c
ctkey_der_CFLAGS = -Wall -I ../include -I $(prefix)/include/pbc $(CFLAGS)
ctkey_der_LDADD = -L../src/.libs/ -lciphrtxt $(LDFLAGS)

ctkey_skinfo_SOURCES = ctkey_skinfo.c b64file.c
ctkey_skinfo_CFLAGS = -Wall -I ../include -I $(prefix)/include/pbc $(CFLAGS)
ctkey_skinfo_LDADD = -L../src/.libs/ -lciphrtxt $(LDFLAGS)

ctkey_pkinfo_SOURCES = ctkey_pkinfo.c b64file.c
ctkey_pkinfo_CFLAGS = -Wall -I ../include -I $(prefix)/include/pbc $(CFLAGS)
ctkey_pkinfo_LDADD = -L../src/.libs/ -lciphrtxt $(LDFLAGS)
