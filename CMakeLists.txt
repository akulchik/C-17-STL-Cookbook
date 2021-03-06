cmake_minimum_required(VERSION 3.16)
project(C__17_STL_Cookbook)

set(CMAKE_CXX_STANDARD 17)

add_executable(C__17_STL_Cookbook main.cc

        stl_containers/vector_access.h
        stl_containers/keep_vector_sorted.h
        stl_containers/inserting_into_map.h
        stl_containers/map_insertion_hint_semantics.h
        stl_containers/efficiently_modifying_map.h
        stl_containers/unordered_map_with_custom_types.h
        stl_containers/filtering_duplicates.h
        stl_containers/rpn_calculator.h
        stl_containers/word_frequency_counter.h
        stl_containers/writing_style_helper.h
        stl_containers/personal_todo_list.h

        iterators/iterable_range.h
        iterators/iterator_categories.h
        iterators/iterator_adapters.h
        iterators/iterator_algorithms.h
        iterators/reverse_iterator_adapters.h
        iterators/iterator_sentinels.h
        iterators/checked_iterators.h
        iterators/zip_iterator.h

        lambda_expressions/defining_lambdas.h
        lambda_expressions/wrapping_lambdas.h
        lambda_expressions/function_concatenation.h
        lambda_expressions/complex_predicates.h
        lambda_expressions/multifunction_calling.h
        lambda_expressions/transform_if.h
        lambda_expressions/cartesian_product.h

        stl_algorithms/copying_items.h
        stl_algorithms/sorting_containers.h
        stl_algorithms/removing_specific_items.h
        stl_algorithms/transforming_contents.h
        stl_algorithms/finding_items.h
        stl_algorithms/limiting_values_to_range.h
        stl_algorithms/locating_patterns_in_strings.h
        stl_algorithms/sampling_large_vectors.h
        stl_algorithms/generating_permutations.h
        stl_algorithms/dictionary_merging.h

        stl_algorithms_advanced/implementing_trie.h
        stl_algorithms_advanced/search_input_suggestion.h
        stl_algorithms_advanced/fourier_transform.h
        stl_algorithms_advanced/vector_error_sum.h
        stl_algorithms_advanced/ascii_mandelbrot_renderer.h
        stl_algorithms_advanced/split.h
        stl_algorithms_advanced/gather.h
        stl_algorithms_advanced/removing_consecutive_whitespace.h
        stl_algorithms_advanced/compressing_decompressing_strings.h

        strings/create_concatenate_transform.h
        strings/trim_whitespace.h
        strings/comfort_without_constructing.h
        strings/reading_from_input.h
        strings/counting_words.h
        strings/formatting_output.h
        strings/initializing_objects_from_input.h

        utility_classes/replacing_void_ptr_with_std_any.h
        utility_classes/storing_different_types_with_std_variant.h
        utility_classes/unique_ptr.h
        utility_classes/shared_ptr.h
        utility_classes/weak_ptr.h
        utility_classes/legacy_apis_with_smart_pointers.h)
