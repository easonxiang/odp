ACLOCAL_AMFLAGS=-I m4
AM_DISTCHECK_CONFIGURE_FLAGS = --enable-user-guides	\
			       --enable-helper-linux	\
			       --with-testdir

#@with_platform@ works alone in subdir but not as part of a path???
SUBDIRS = @platform_with_platform@ \
	  helper \
	  helper/test \
	  doc \
	  example . \
	  test

@DX_RULES@

EXTRA_DIST = bootstrap $(DX_CONFIG) CHANGELOG config/README
