CLEANFILES = *.py{c,o} command/*.py{c,o} log/*.py{c,o}

morituridir = $(PYTHONLIBDIR)/morituri/extern

morituri_PYTHON = \
	__init__.py \
	asyncsub.py

logdir = $(PYTHONLIBDIR)/morituri/extern/log

log_PYTHON = \
	log/__init__.py \
	log/log.py

commanddir = $(PYTHONLIBDIR)/morituri/extern/command

command_PYTHON = \
	command/__init__.py \
	command/command.py

depsdir = $(PYTHONLIBDIR)/morituri/extern/deps

deps_PYTHON = \
	deps/__init__.py \
	deps/deps.py \
	deps/distro.py


taskdir = $(PYTHONLIBDIR)/morituri/extern/task

task_PYTHON = \
	task/__init__.py \
	task/task.py \
	task/taskgtk.py \
	task/gstreamer.py

musicbrainzngsdir = $(PYTHONLIBDIR)/morituri/extern/musicbrainzngs

musicbrainzngs_PYTHON = \
	musicbrainzngs/__init__.py \
	musicbrainzngs/musicbrainz.py \
	musicbrainzngs/mbxml.py

xdgdir = $(PYTHONLIBDIR)/morituri/extern/xdg

xdg_PYTHON = \
	xdg/__init__.py \
	xdg/BaseDirectory.py \
	xdg/Config.py \
	xdg/DesktopEntry.py \
	xdg/Exceptions.py \
	xdg/IconTheme.py \
	xdg/IniFile.py \
	xdg/Locale.py \
	xdg/Menu.py \
	xdg/MenuEditor.py \
	xdg/Mime.py \
	xdg/RecentFiles.py

EXTRA_DIST = python-command/scripts/help2man

musicbrainzngs/musicbrainz.py: all
