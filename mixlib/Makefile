# Makefile.in generated by automake 1.16.2 from Makefile.am.
# mixlib/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2020 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# Copyright (C) 2000, 2001, 2006, 2014, 2019 Free Software Foundation, Inc.
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.


am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/mdk
pkgincludedir = $(includedir)/mdk
pkglibdir = $(libdir)/mdk
pkglibexecdir = $(libexecdir)/mdk
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-pc-linux-musl
host_triplet = x86_64-pc-linux-musl
subdir = mixlib
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/codeset.m4 \
	$(top_srcdir)/m4/gettext.m4 $(top_srcdir)/m4/glibc21.m4 \
	$(top_srcdir)/m4/iconv.m4 $(top_srcdir)/m4/intdiv0.m4 \
	$(top_srcdir)/m4/intmax.m4 $(top_srcdir)/m4/inttypes-pri.m4 \
	$(top_srcdir)/m4/inttypes.m4 $(top_srcdir)/m4/inttypes_h.m4 \
	$(top_srcdir)/m4/isc-posix.m4 $(top_srcdir)/m4/lcmessage.m4 \
	$(top_srcdir)/m4/lib-ld.m4 $(top_srcdir)/m4/lib-link.m4 \
	$(top_srcdir)/m4/lib-prefix.m4 $(top_srcdir)/m4/longdouble.m4 \
	$(top_srcdir)/m4/longlong.m4 $(top_srcdir)/m4/nls.m4 \
	$(top_srcdir)/m4/po.m4 $(top_srcdir)/m4/printf-posix.m4 \
	$(top_srcdir)/m4/progtest.m4 $(top_srcdir)/m4/signed.m4 \
	$(top_srcdir)/m4/size_max.m4 $(top_srcdir)/m4/stdint_h.m4 \
	$(top_srcdir)/m4/uintmax_t.m4 $(top_srcdir)/m4/ulonglong.m4 \
	$(top_srcdir)/m4/wchar_t.m4 $(top_srcdir)/m4/wint_t.m4 \
	$(top_srcdir)/m4/xsize.m4 $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
LIBRARIES = $(noinst_LIBRARIES)
AR = ar
ARFLAGS = cru
AM_V_AR = $(am__v_AR_$(V))
am__v_AR_ = $(am__v_AR_$(AM_DEFAULT_VERBOSITY))
am__v_AR_0 = @echo "  AR      " $@;
am__v_AR_1 = 
libmix_a_AR = $(AR) $(ARFLAGS)
libmix_a_LIBADD =
am_libmix_a_OBJECTS = completion.$(OBJEXT) mix.$(OBJEXT) \
	mix_types.$(OBJEXT) mix_ins.$(OBJEXT) mix_vm.$(OBJEXT) \
	xmix_vm.$(OBJEXT) mix_vm_dump.$(OBJEXT) mix_io.$(OBJEXT) \
	xmix_io.$(OBJEXT) mix_symbol_table.$(OBJEXT) \
	mix_file.$(OBJEXT) mix_code_file.$(OBJEXT) \
	mix_parser.$(OBJEXT) mix_scanner.$(OBJEXT) \
	mix_device.$(OBJEXT) xmix_device.$(OBJEXT) mix_eval.$(OBJEXT) \
	mix_eval_scanner.$(OBJEXT) mix_src_file.$(OBJEXT) \
	mix_vm_clock.$(OBJEXT) mix_vm_command.$(OBJEXT) \
	xmix_vm_command.$(OBJEXT) xmix_vm_handlers.$(OBJEXT) \
	mix_config.$(OBJEXT) mix_predicate.$(OBJEXT) \
	mix_predicate_list.$(OBJEXT)
libmix_a_OBJECTS = $(am_libmix_a_OBJECTS)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__maybe_remake_depfiles = depfiles
am__depfiles_remade = ./$(DEPDIR)/completion.Po ./$(DEPDIR)/mix.Po \
	./$(DEPDIR)/mix_code_file.Po ./$(DEPDIR)/mix_config.Po \
	./$(DEPDIR)/mix_device.Po ./$(DEPDIR)/mix_eval.Po \
	./$(DEPDIR)/mix_eval_scanner.Po ./$(DEPDIR)/mix_file.Po \
	./$(DEPDIR)/mix_ins.Po ./$(DEPDIR)/mix_io.Po \
	./$(DEPDIR)/mix_parser.Po ./$(DEPDIR)/mix_predicate.Po \
	./$(DEPDIR)/mix_predicate_list.Po ./$(DEPDIR)/mix_scanner.Po \
	./$(DEPDIR)/mix_src_file.Po ./$(DEPDIR)/mix_symbol_table.Po \
	./$(DEPDIR)/mix_types.Po ./$(DEPDIR)/mix_vm.Po \
	./$(DEPDIR)/mix_vm_clock.Po ./$(DEPDIR)/mix_vm_command.Po \
	./$(DEPDIR)/mix_vm_dump.Po ./$(DEPDIR)/xmix_device.Po \
	./$(DEPDIR)/xmix_io.Po ./$(DEPDIR)/xmix_vm.Po \
	./$(DEPDIR)/xmix_vm_command.Po ./$(DEPDIR)/xmix_vm_handlers.Po
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
am__skiplex = test -f $@ ||
LEXCOMPILE = $(LEX) $(AM_LFLAGS) $(LFLAGS)
AM_V_LEX = $(am__v_LEX_$(V))
am__v_LEX_ = $(am__v_LEX_$(AM_DEFAULT_VERBOSITY))
am__v_LEX_0 = @echo "  LEX     " $@;
am__v_LEX_1 = 
YLWRAP = $(top_srcdir)/ylwrap
SOURCES = $(libmix_a_SOURCES)
DIST_SOURCES = $(libmix_a_SOURCES)
RECURSIVE_TARGETS = all-recursive check-recursive cscopelist-recursive \
	ctags-recursive dvi-recursive html-recursive info-recursive \
	install-data-recursive install-dvi-recursive \
	install-exec-recursive install-html-recursive \
	install-info-recursive install-pdf-recursive \
	install-ps-recursive install-recursive installcheck-recursive \
	installdirs-recursive pdf-recursive ps-recursive \
	tags-recursive uninstall-recursive
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
RECURSIVE_CLEAN_TARGETS = mostlyclean-recursive clean-recursive	\
  distclean-recursive maintainer-clean-recursive
am__recursive_targets = \
  $(RECURSIVE_TARGETS) \
  $(RECURSIVE_CLEAN_TARGETS) \
  $(am__extra_recursive_targets)
AM_RECURSIVE_TARGETS = $(am__recursive_targets:-recursive=) TAGS CTAGS \
	distdir distdir-am
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DIST_SUBDIRS = $(SUBDIRS)
am__DIST_COMMON = $(srcdir)/Makefile.in $(top_srcdir)/depcomp \
	$(top_srcdir)/mkinstalldirs $(top_srcdir)/ylwrap \
	mix_eval_scanner.c mix_scanner.c
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
am__relativize = \
  dir0=`pwd`; \
  sed_first='s,^\([^/]*\)/.*$$,\1,'; \
  sed_rest='s,^[^/]*/*,,'; \
  sed_last='s,^.*/\([^/]*\)$$,\1,'; \
  sed_butlast='s,/*[^/]*$$,,'; \
  while test -n "$$dir1"; do \
    first=`echo "$$dir1" | sed -e "$$sed_first"`; \
    if test "$$first" != "."; then \
      if test "$$first" = ".."; then \
        dir2=`echo "$$dir0" | sed -e "$$sed_last"`/"$$dir2"; \
        dir0=`echo "$$dir0" | sed -e "$$sed_butlast"`; \
      else \
        first2=`echo "$$dir2" | sed -e "$$sed_first"`; \
        if test "$$first2" = "$$first"; then \
          dir2=`echo "$$dir2" | sed -e "$$sed_rest"`; \
        else \
          dir2="../$$dir2"; \
        fi; \
        dir0="$$dir0"/"$$first"; \
      fi; \
    fi; \
    dir1=`echo "$$dir1" | sed -e "$$sed_rest"`; \
  done; \
  reldir="$$dir2"
ACLOCAL = ${SHELL} /home/dante/pr/mdk-1.3.0/missing aclocal-1.16
ALLOCA = 
ALL_LINGUAS = 
AMTAR = $${TAR-tar}
AM_CFLAGS =  -Wall -fno-strict-aliasing -I/usr/include/glib-2.0 -I/usr/lib64/glib-2.0/include -DG_DISABLE_DEPRECATED -pthread -I/usr/include/gtk-3.0 -I/usr/include/at-spi2-atk/2.0 -I/usr/include/at-spi-2.0 -I/usr/include/dbus-1.0 -I/usr/lib/dbus-1.0/include -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0 -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/pango-1.0 -I/usr/include/libmount -I/usr/include/blkid -I/usr/include/fribidi -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/uuid -I/usr/include/harfbuzz -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/glib-2.0 -I/usr/lib64/glib-2.0/include -DGTK_DISABLE_DEPRECATED -DGDK_DISABLE_DEPRECATED -I$(includedir) -I$(top_srcdir) \
	-DG_LOG_DOMAIN=\"libmix\"
AM_DEFAULT_VERBOSITY = 1
AUTOCONF = ${SHELL} /home/dante/pr/mdk-1.3.0/missing autoconf
AUTOHEADER = ${SHELL} /home/dante/pr/mdk-1.3.0/missing autoheader
AUTOMAKE = ${SHELL} /home/dante/pr/mdk-1.3.0/missing automake-1.16
AWK = gawk
BUILD_INCLUDED_LIBINTL = no
CATOBJEXT = .gmo
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
CPP = gcc -E
CPPFLAGS = 
CYGPATH_W = echo
DATADIRNAME = share
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
GENCAT = gencat
GETTEXT_PACKAGE = mdk
GLIBC21 = no
GLIB_CFLAGS = -I/usr/include/glib-2.0 -I/usr/lib64/glib-2.0/include
GLIB_LIBS = -L/usr/lib64 -lglib-2.0
GMSGFMT = /bin/msgfmt
GREP = /bin/grep
GTK_CFLAGS = -pthread -I/usr/include/gtk-3.0 -I/usr/include/at-spi2-atk/2.0 -I/usr/include/at-spi-2.0 -I/usr/include/dbus-1.0 -I/usr/lib/dbus-1.0/include -I/usr/include/gtk-3.0 -I/usr/include/gio-unix-2.0 -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/pango-1.0 -I/usr/include/libmount -I/usr/include/blkid -I/usr/include/fribidi -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/uuid -I/usr/include/harfbuzz -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/glib-2.0 -I/usr/lib64/glib-2.0/include
GTK_LIBS = -L/usr/lib64 -lgtk-3 -lgdk-3 -lpangocairo-1.0 -latk-1.0 -lcairo-gobject -lcairo -lgdk_pixbuf-2.0 -lgio-2.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lharfbuzz
GUILE_CFLAGS = 
GUILE_LIBS = 
HAVE_ASPRINTF = 1
HAVE_POSIX_PRINTF = 1
HAVE_SNPRINTF = 1
HAVE_WPRINTF = 0
INSTALL = /bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INSTOBJEXT = .mo
INTLBISON = :
INTLLIBS = -lintl
INTLOBJS = 
INTLTOOL_EXTRACT = /bin/intltool-extract
INTLTOOL_MERGE = /bin/intltool-merge
INTLTOOL_PERL = /bin/perl
INTLTOOL_UPDATE = /bin/intltool-update
INTLTOOL_V_MERGE = $(INTLTOOL__v_MERGE_$(V))
INTLTOOL_V_MERGE_OPTIONS = $(intltool__v_merge_options_$(V))
INTLTOOL__v_MERGE_ = $(INTLTOOL__v_MERGE_$(AM_DEFAULT_VERBOSITY))
INTLTOOL__v_MERGE_0 = @echo "  ITMRG " $@;
INTL_LIBTOOL_SUFFIX_PREFIX = 
LDFLAGS = 
LEX = ${SHELL} /home/dante/pr/mdk-1.3.0/missing flex
LEXLIB = 
LEX_OUTPUT_ROOT = 
LIBICONV = 
LIBINTL = -lintl
LIBOBJS = 
LIBS =  -L/usr/lib64 -lglib-2.0 -L/usr/lib64 -lgtk-3 -lgdk-3 -lpangocairo-1.0 -latk-1.0 -lcairo-gobject -lcairo -lgdk_pixbuf-2.0 -lgio-2.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lharfbuzz
LTLIBICONV = 
LTLIBINTL = -lintl
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /home/dante/pr/mdk-1.3.0/missing makeinfo
MAKE_GUILE = 
MKDIR_P = /bin/mkdir -p
MKINSTALLDIRS = $(top_builddir)/./mkinstalldirs
MSGFMT = /bin/msgfmt
MSGMERGE = /bin/msgmerge
OBJEXT = o
PACKAGE = mdk
PACKAGE_BUGREPORT = bug-mdk@gnu.org
PACKAGE_NAME = GNU MDK
PACKAGE_STRING = GNU MDK 1.3.0
PACKAGE_TARNAME = mdk
PACKAGE_URL = http://www.gnu.org/software/mdk/
PACKAGE_VERSION = 1.3.0
PATH_SEPARATOR = :
PKG_CONFIG = /bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
POSUB = po
RANLIB = ranlib
SET_MAKE = 
SHELL = /bin/sh
STRIP = 
USE_INCLUDED_LIBINTL = no
USE_NLS = yes
VERSION = 1.3.0
XGETTEXT = /bin/xgettext
abs_builddir = /home/dante/pr/mdk-1.3.0/mixlib
abs_srcdir = /home/dante/pr/mdk-1.3.0/mixlib
abs_top_builddir = /home/dante/pr/mdk-1.3.0
abs_top_srcdir = /home/dante/pr/mdk-1.3.0
ac_ct_CC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-pc-linux-musl
build_alias = 
build_cpu = x86_64
build_os = linux-musl
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-pc-linux-musl
host_alias = 
host_cpu = x86_64
host_os = linux-musl
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/dante/pr/mdk-1.3.0/install-sh
intltool__v_merge_options_ = $(intltool__v_merge_options_$(AM_DEFAULT_VERBOSITY))
intltool__v_merge_options_0 = -q
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
SUBDIRS = testsuite
CLEANFILES = mix_scanner.c mix_eval_scanner.c
noinst_LIBRARIES = libmix.a
libmix_a_SOURCES = gettext.h \
                   completion.h completion.c \
                   mix.h mix.c \
		   mix_types.h mix_types.c \
		   mix_ins.h mix_ins.c     \
	           mix_vm.h mix_vm.c xmix_vm.h xmix_vm.c \
		   mix_vm_dump.h mix_vm_dump.c \
		   mix_io.h mix_io.c xmix_io.h xmix_io.c \
		   mix_symbol_table.h mix_symbol_table.c \
		   mix_file.h mix_file.c \
                   mix_code_file.h mix_code_file.c \
		   mix_parser.h xmix_parser.h mix_parser.c mix_scanner.l \
                   mix_device.h mix_device.c xmix_device.h xmix_device.c \
                   mix_eval.h mix_eval.c xmix_eval.h mix_eval_scanner.l \
		   mix_src_file.c mix_src_file.h \
                   mix_vm_clock.c mix_vm_clock.h \
		   mix_vm_command.c mix_vm_command.h \
		   xmix_vm_command.c xmix_vm_command.h \
                   xmix_vm_handlers.h xmix_vm_handlers.c \
		   mix_config.c mix_config.h \
                   mix_predicate.c mix_predicate.h \
                   mix_predicate_list.c mix_predicate_list.h

all: all-recursive

.SUFFIXES:
.SUFFIXES: .c .l .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu mixlib/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu mixlib/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)

libmix.a: $(libmix_a_OBJECTS) $(libmix_a_DEPENDENCIES) $(EXTRA_libmix_a_DEPENDENCIES) 
	$(AM_V_at)-rm -f libmix.a
	$(AM_V_AR)$(libmix_a_AR) libmix.a $(libmix_a_OBJECTS) $(libmix_a_LIBADD)
	$(AM_V_at)$(RANLIB) libmix.a

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/completion.Po # am--include-marker
include ./$(DEPDIR)/mix.Po # am--include-marker
include ./$(DEPDIR)/mix_code_file.Po # am--include-marker
include ./$(DEPDIR)/mix_config.Po # am--include-marker
include ./$(DEPDIR)/mix_device.Po # am--include-marker
include ./$(DEPDIR)/mix_eval.Po # am--include-marker
include ./$(DEPDIR)/mix_eval_scanner.Po # am--include-marker
include ./$(DEPDIR)/mix_file.Po # am--include-marker
include ./$(DEPDIR)/mix_ins.Po # am--include-marker
include ./$(DEPDIR)/mix_io.Po # am--include-marker
include ./$(DEPDIR)/mix_parser.Po # am--include-marker
include ./$(DEPDIR)/mix_predicate.Po # am--include-marker
include ./$(DEPDIR)/mix_predicate_list.Po # am--include-marker
include ./$(DEPDIR)/mix_scanner.Po # am--include-marker
include ./$(DEPDIR)/mix_src_file.Po # am--include-marker
include ./$(DEPDIR)/mix_symbol_table.Po # am--include-marker
include ./$(DEPDIR)/mix_types.Po # am--include-marker
include ./$(DEPDIR)/mix_vm.Po # am--include-marker
include ./$(DEPDIR)/mix_vm_clock.Po # am--include-marker
include ./$(DEPDIR)/mix_vm_command.Po # am--include-marker
include ./$(DEPDIR)/mix_vm_dump.Po # am--include-marker
include ./$(DEPDIR)/xmix_device.Po # am--include-marker
include ./$(DEPDIR)/xmix_io.Po # am--include-marker
include ./$(DEPDIR)/xmix_vm.Po # am--include-marker
include ./$(DEPDIR)/xmix_vm_command.Po # am--include-marker
include ./$(DEPDIR)/xmix_vm_handlers.Po # am--include-marker

$(am__depfiles_remade):
	@$(MKDIR_P) $(@D)
	@echo '# dummy' >$@-t && $(am__mv) $@-t $@

am--depfiles: $(am__depfiles_remade)

.c.o:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ $<

.c.obj:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.l.c:
	$(AM_V_LEX)$(am__skiplex) $(SHELL) $(YLWRAP) $< $(LEX_OUTPUT_ROOT).c $@ -- $(LEXCOMPILE)

# This directory's subdirectories are mostly independent; you can cd
# into them and run 'make' without going through this Makefile.
# To change the values of 'make' variables: instead of editing Makefiles,
# (1) if the variable is set in 'config.status', edit 'config.status'
#     (which will cause the Makefiles to be regenerated when you run 'make');
# (2) otherwise, pass the desired values on the 'make' command line.
$(am__recursive_targets):
	@fail=; \
	if $(am__make_keepgoing); then \
	  failcom='fail=yes'; \
	else \
	  failcom='exit 1'; \
	fi; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	case "$@" in \
	  distclean-* | maintainer-clean-*) list='$(DIST_SUBDIRS)' ;; \
	  *) list='$(SUBDIRS)' ;; \
	esac; \
	for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-recursive
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	if ($(ETAGS) --etags-include --version) >/dev/null 2>&1; then \
	  include_option=--etags-include; \
	  empty_fix=.; \
	else \
	  include_option=--include; \
	  empty_fix=; \
	fi; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test ! -f $$subdir/TAGS || \
	      set "$$@" "$$include_option=$$here/$$subdir/TAGS"; \
	  fi; \
	done; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-recursive

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-recursive

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) distdir-am

distdir-am: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    $(am__make_dryrun) \
	      || test -d "$(distdir)/$$subdir" \
	      || $(MKDIR_P) "$(distdir)/$$subdir" \
	      || exit 1; \
	    dir1=$$subdir; dir2="$(distdir)/$$subdir"; \
	    $(am__relativize); \
	    new_distdir=$$reldir; \
	    dir1=$$subdir; dir2="$(top_distdir)"; \
	    $(am__relativize); \
	    new_top_distdir=$$reldir; \
	    echo " (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir="$$new_top_distdir" distdir="$$new_distdir" \\"; \
	    echo "     am__remove_distdir=: am__skip_length_check=: am__skip_mode_fix=: distdir)"; \
	    ($(am__cd) $$subdir && \
	      $(MAKE) $(AM_MAKEFLAGS) \
	        top_distdir="$$new_top_distdir" \
	        distdir="$$new_distdir" \
		am__remove_distdir=: \
		am__skip_length_check=: \
		am__skip_mode_fix=: \
	        distdir) \
	      || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-recursive
all-am: Makefile $(LIBRARIES)
installdirs: installdirs-recursive
installdirs-am:
install: install-recursive
install-exec: install-exec-recursive
install-data: install-data-recursive
uninstall: uninstall-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-recursive
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-rm -f mix_eval_scanner.c
	-rm -f mix_scanner.c
clean: clean-recursive

clean-am: clean-generic clean-noinstLIBRARIES mostlyclean-am

distclean: distclean-recursive
		-rm -f ./$(DEPDIR)/completion.Po
	-rm -f ./$(DEPDIR)/mix.Po
	-rm -f ./$(DEPDIR)/mix_code_file.Po
	-rm -f ./$(DEPDIR)/mix_config.Po
	-rm -f ./$(DEPDIR)/mix_device.Po
	-rm -f ./$(DEPDIR)/mix_eval.Po
	-rm -f ./$(DEPDIR)/mix_eval_scanner.Po
	-rm -f ./$(DEPDIR)/mix_file.Po
	-rm -f ./$(DEPDIR)/mix_ins.Po
	-rm -f ./$(DEPDIR)/mix_io.Po
	-rm -f ./$(DEPDIR)/mix_parser.Po
	-rm -f ./$(DEPDIR)/mix_predicate.Po
	-rm -f ./$(DEPDIR)/mix_predicate_list.Po
	-rm -f ./$(DEPDIR)/mix_scanner.Po
	-rm -f ./$(DEPDIR)/mix_src_file.Po
	-rm -f ./$(DEPDIR)/mix_symbol_table.Po
	-rm -f ./$(DEPDIR)/mix_types.Po
	-rm -f ./$(DEPDIR)/mix_vm.Po
	-rm -f ./$(DEPDIR)/mix_vm_clock.Po
	-rm -f ./$(DEPDIR)/mix_vm_command.Po
	-rm -f ./$(DEPDIR)/mix_vm_dump.Po
	-rm -f ./$(DEPDIR)/xmix_device.Po
	-rm -f ./$(DEPDIR)/xmix_io.Po
	-rm -f ./$(DEPDIR)/xmix_vm.Po
	-rm -f ./$(DEPDIR)/xmix_vm_command.Po
	-rm -f ./$(DEPDIR)/xmix_vm_handlers.Po
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-recursive

dvi-am:

html: html-recursive

html-am:

info: info-recursive

info-am:

install-data-am:

install-dvi: install-dvi-recursive

install-dvi-am:

install-exec-am:

install-html: install-html-recursive

install-html-am:

install-info: install-info-recursive

install-info-am:

install-man:

install-pdf: install-pdf-recursive

install-pdf-am:

install-ps: install-ps-recursive

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-recursive
		-rm -f ./$(DEPDIR)/completion.Po
	-rm -f ./$(DEPDIR)/mix.Po
	-rm -f ./$(DEPDIR)/mix_code_file.Po
	-rm -f ./$(DEPDIR)/mix_config.Po
	-rm -f ./$(DEPDIR)/mix_device.Po
	-rm -f ./$(DEPDIR)/mix_eval.Po
	-rm -f ./$(DEPDIR)/mix_eval_scanner.Po
	-rm -f ./$(DEPDIR)/mix_file.Po
	-rm -f ./$(DEPDIR)/mix_ins.Po
	-rm -f ./$(DEPDIR)/mix_io.Po
	-rm -f ./$(DEPDIR)/mix_parser.Po
	-rm -f ./$(DEPDIR)/mix_predicate.Po
	-rm -f ./$(DEPDIR)/mix_predicate_list.Po
	-rm -f ./$(DEPDIR)/mix_scanner.Po
	-rm -f ./$(DEPDIR)/mix_src_file.Po
	-rm -f ./$(DEPDIR)/mix_symbol_table.Po
	-rm -f ./$(DEPDIR)/mix_types.Po
	-rm -f ./$(DEPDIR)/mix_vm.Po
	-rm -f ./$(DEPDIR)/mix_vm_clock.Po
	-rm -f ./$(DEPDIR)/mix_vm_command.Po
	-rm -f ./$(DEPDIR)/mix_vm_dump.Po
	-rm -f ./$(DEPDIR)/xmix_device.Po
	-rm -f ./$(DEPDIR)/xmix_io.Po
	-rm -f ./$(DEPDIR)/xmix_vm.Po
	-rm -f ./$(DEPDIR)/xmix_vm_command.Po
	-rm -f ./$(DEPDIR)/xmix_vm_handlers.Po
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-recursive

mostlyclean-am: mostlyclean-compile mostlyclean-generic

pdf: pdf-recursive

pdf-am:

ps: ps-recursive

ps-am:

uninstall-am:

.MAKE: $(am__recursive_targets) install-am install-strip

.PHONY: $(am__recursive_targets) CTAGS GTAGS TAGS all all-am \
	am--depfiles check check-am clean clean-generic \
	clean-noinstLIBRARIES cscopelist-am ctags ctags-am distclean \
	distclean-compile distclean-generic distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs installdirs-am \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-compile mostlyclean-generic pdf pdf-am ps ps-am \
	tags tags-am uninstall uninstall-am

.PRECIOUS: Makefile


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
