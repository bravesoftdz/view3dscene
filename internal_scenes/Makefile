# This requires file_to_pascal_string that is a trivial program
# that I made for pasdoc [http://pasdoc.sf.net/] project, see
# [https://pasdoc.svn.sourceforge.net/svnroot/pasdoc/trunk/source/tools/file_to_pascal_string.dpr]

ALL_TARGETS := ../welcome_scene.inc ../clear_scene.inc

default: $(ALL_TARGETS)

clean:
	rm -f $(ALL_TARGETS)

../welcome_scene.inc: welcome_scene.wrl
	file_to_pascal_string $< $@

../clear_scene.inc: clear_scene.wrl
	file_to_pascal_string $< $@