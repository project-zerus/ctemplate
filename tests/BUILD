cc_library(
    name = 'tests',
    warning = 'no',
    srcs = [
        'template_regtest.cc',
        'template_test_util.cc',
    ],
    deps = ['//essence/ctemplate:ctemplate']
)

cc_test(
    name = 'template_dictionary_unittest',
    warning = 'no',
    srcs = ['template_dictionary_unittest.cc'],
    deps = [':tests']
)

cc_test(
    name = 'template_modifiers_unittest',
    warning = 'no',
    srcs = ['template_modifiers_unittest.cc'],
    deps = [':tests']
)

cc_test(
    name = 'template_setglobals_unittest',
    warning = 'no',
    srcs = ['template_setglobals_unittest.cc'],
    deps = [':tests']
)

cc_test(
    name = 'template_unittest',
    warning = 'no',
    srcs = ['template_unittest.cc'],
    deps = [':tests']
)

cc_test(
    name = 'generate_fsm_c_test',
    warning = 'no',
    srcs = ['generate_fsm_c_test.cc'],
    deps = [':tests']
)

cc_test(
    name = 'statemachine_test',
    warning = 'no',
    srcs = ['statemachine_test.cc'],
    deps = [':tests']
)

cc_test(
    name = 'compile_test',
    warning = 'no',
    srcs = ['compile_test.cc'],
    deps = [':tests']
)

cc_test(
    name = 'htmlparser_cpp_test',
    warning = 'no',
    srcs = ['htmlparser_cpp_test.cc'],
    deps = [':tests'],
    testdata = 'htmlparser_testdata'
)

cc_test(
    name = 'template_cache_test',
    warning = 'no',
    srcs = ['template_cache_test.cc'],
    deps = [':tests']
)

cc_test(
    name = 'template_test_util_test',
    warning = 'no',
    srcs = ['template_test_util_test.cc'],
    deps = [':tests']
)
