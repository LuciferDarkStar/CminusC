add_executable(test_lex test_lex.c)
target_link_libraries(test_lex lex syntax syntax_tree)
add_executable(test_syntax test_syntax.c)
target_link_libraries(test_syntax syntax syntax_tree)
add_executable(test_syntax_tree test_syntax_tree.cpp)
target_link_libraries(test_syntax_tree syntax syntax_tree syntax_tree_cpp)
