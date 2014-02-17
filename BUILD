cc_library(
    name = 'ctemplate',
    warning = 'no',
    srcs = [
        'base/arena.cc',

        'htmlparser/htmlparser.cc',
        'htmlparser/jsparser.cc',
        'htmlparser/statemachine.cc',

        'per_expand_data.cc',
        'template_annotator.cc',
        'template_cache.cc',
        'template.cc',
        'template_dictionary.cc',
        'template_modifiers.cc',
        'template_namelist.cc',
        'template_pathops.cc',
        'template_string.cc',
    ],
    deps = '#pthread'
)

cc_binary(
    name = 'diff_tpl_auto_escape',
    srcs = [
        'diff_tpl_auto_escape.cc',
    ],
    deps = ':ctemplate'
)

cc_binary(
    name = 'make_tpl_varnames_h',
    srcs = [
        'make_tpl_varnames_h.cc',
    ],
    deps = ':ctemplate'
)
