````
Performing configuration checks

    - default address-model    : 64-bit [1]
    - default architecture     : arm [1]

Building the Boost C++ Libraries.


warning: Graph library does not contain MPI-based parallel components.
note: to enable them, add "using mpi ;" to your user-config.jam.
note: to suppress this message, pass "--without-graph_parallel" to bjam.
    - std_wstreambuf builds    : yes [2]
    - std_wstreambuf           : yes [2]
    - cxx11_constexpr          : yes [2]
    - cxx11_variadic_templates : yes [2]
    - cxx11_rvalue_references  : yes [2]
    - cxx11_hdr_thread         : yes [2]
    - cxx11_hdr_mutex          : yes [2]
    - cxx11_hdr_regex          : yes [2]
    - has std::atomic_ref      : no [2]
    - has -Wl,--no-undefined   : yes [2]
    - has statx                : yes [2]
    - cxx11_scoped_enums       : yes [2]
    - cxx11_noexcept           : yes [2]
    - cxx11_nullptr            : yes [2]
    - cxx11_defaulted_functions : yes [2]
    - cxx11_defaulted_moves    : yes [2]
    - cxx11_deleted_functions  : yes [2]
    - cxx11_function_template_default_args : yes [2]
    - cxx11_unified_initialization_syntax : yes [2]
    - cxx11_final              : yes [2]
    - cxx11_override           : yes [2]
    - has init_priority attribute : yes [2]
    - has stat::st_blksize     : yes [2]
    - has stat::st_mtim        : yes [2]
    - has stat::st_mtimensec   : no [2]
    - has stat::st_mtimespec   : no [2]
    - has stat::st_birthtim    : no [2]
    - has stat::st_birthtimensec : no [2]
    - has stat::st_birthtimespec : no [2]
    - has fdopendir(O_NOFOLLOW) : yes [2]
    - has dirent::d_type       : yes [2]
    - has POSIX *at APIs       : yes [2]
    - has fallocate            : yes [2]
    - has pthread_cond_clockwait : yes [2]
    - cxx11_decltype           : yes [2]
    - cxx11_decltype_n3276     : yes [2]
    - cxx11_template_aliases   : yes [2]
    - cxx11_static_assert      : yes [2]
    - cxx11_hdr_ratio          : yes [2]
    - cxx11_hdr_chrono         : yes [2]
    - has unions with non-trivial members : yes [2]
    - has <type_traits> sufficient for Boost.Atomic : yes [2]
    - exceptions               : yes [2]
    - sfinae_expr              : yes [2]
    - has <type_traits> sufficient for Boost.Scope : yes [2]
    - has_icu builds           : no [2]
    - lockfree boost::atomic_flag : yes [2]
    - cxx11_char16_t           : yes [2]
    - cxx11_char32_t           : yes [2]
    - cxx11_hdr_tuple          : yes [2]
    - BOOST_COMP_GNUC >= 4.3.0 : no [2]
    - BOOST_COMP_GNUC >= 4.3.0 : no [3]
    - boost.stacktrace.addr2line : yes [2]
    - cxx11_rvalue_references  : yes [3]
    - boost.stacktrace.backtrace : yes [2]
    - boost.stacktrace.basic   : no [2]
    - boost.stacktrace.from_exception : no
    - boost.stacktrace.from_exception : no
    - boost.stacktrace.windbg  : no [2]
    - boost.stacktrace.windbg  : no [4]
    - boost.stacktrace.windbg_cached : no [2]
    - boost.stacktrace.windbg_cached : no [4]
    - cxx11_auto_declarations  : yes [2]
    - cxx11_lambdas            : yes [2]
    - cxx11_hdr_initializer_list : yes [2]
    - cxx11_numeric_limits     : yes [2]
    - cxx11_hdr_array          : yes [2]
    - cxx11_hdr_type_traits    : yes [2]
    - cxx11_explicit_conversion_operators : yes [2]
warning: No python installation configured and autoconfiguration
note: failed.  See http://www.boost.org/libs/python/doc/building.html
note: for configuration instructions or pass --without-python to
note: suppress this message and silently skip all Boost.Python targets
    - BOOST_ARCH_WORD_BITS == 0.0.16 : no [5]
    - BOOST_ARCH_WORD_BITS == 0.0.32 : no [5]
    - BOOST_ARCH_WORD_BITS == 0.0.64 : no [5]
    - BOOST_ARCH_X86           : no [5]
    - BOOST_ARCH_IA64          : no [5]
    - BOOST_ARCH_SPARC         : no [5]
    - BOOST_ARCH_LOONGARCH     : no [5]
    - BOOST_ARCH_MIPS          : no [5]
    - BOOST_ARCH_PARISC        : no [5]
    - BOOST_ARCH_ARM           : no [5]
    - BOOST_ARCH_RISCV         : no [5]
    - BOOST_ARCH_PPC           : no [5]
    - BOOST_ARCH_SYS390        : no [5]
    - has std::atomic_ref      : no [5]
    - has -Wl,--no-undefined   : yes [5]
    - has statx                : yes [5]
    - cxx11_rvalue_references  : yes [5]
    - cxx11_scoped_enums       : yes [5]
    - cxx11_noexcept           : yes [5]
    - cxx11_nullptr            : yes [5]
    - cxx11_defaulted_functions : yes [5]
    - cxx11_defaulted_moves    : yes [5]
    - cxx11_deleted_functions  : yes [5]
    - cxx11_function_template_default_args : yes [5]
    - cxx11_unified_initialization_syntax : yes [5]
    - cxx11_final              : yes [5]
    - cxx11_override           : yes [5]
    - has init_priority attribute : yes [5]
    - has stat::st_blksize     : yes [5]
    - has stat::st_mtim        : yes [5]
    - has stat::st_mtimensec   : no [5]
    - has stat::st_mtimespec   : no [5]
    - has stat::st_birthtim    : no [5]
    - has stat::st_birthtimensec : no [5]
    - has stat::st_birthtimespec : no [5]
    - has fdopendir(O_NOFOLLOW) : yes [5]
    - has dirent::d_type       : yes [5]
    - has POSIX *at APIs       : yes [5]
    - has fallocate            : yes [5]
    - has pthread_cond_clockwait : yes [5]
    - cxx11_constexpr          : yes [5]
    - cxx11_decltype           : yes [5]
    - cxx11_decltype_n3276     : yes [5]
    - cxx11_template_aliases   : yes [5]
    - cxx11_static_assert      : yes [5]
    - cxx11_hdr_ratio          : yes [5]
    - cxx11_hdr_chrono         : yes [5]
    - has unions with non-trivial members : yes [5]
    - has <type_traits> sufficient for Boost.Atomic : yes [5]
    - exceptions               : yes [5]
    - sfinae_expr              : yes [5]
    - cxx11_variadic_templates : yes [5]
    - has <type_traits> sufficient for Boost.Scope : yes [5]
    - Has Large File Support   : yes [2]
    - Has attribute init_priority : yes [2]
error: No best alternative for /home/ubuntu/boost_1_90_0/libs/mpi/build/boost_mpi with <abi>aapcs <address-model>64 <architecture>arm <asynch-exceptions>off <binary-format>elf <boost.beast.allow-deprecated>on <boost.beast.separate-compilation>on <boost.cobalt.executor>any_io_executor <boost.cobalt.pmr>std <context-impl>fcontext <coverage>off <debug-symbols>off <exception-handling>on <extern-c-nothrow>off <inlining>full <known-warnings>hide <link>shared <optimization>speed <os>LINUX <pch>on <preserve-test-targets>on <profiling>off <python-debugging>off <rtti>on <runtime-debugging>off <runtime-link>shared <stdlib>native <strip>off <target-os>linux <testing.execute>on <threadapi>pthread <threading>multi <toolset-gcc:version>11 <toolset>gcc <variant>release <vectorize>off <visibility>hidden <warnings-as-errors>off <warnings>on <x-deduced-platform>arm_64
    matched: (empty)
    matched: (empty)
    - gcc visibility           : yes [2]
    - cxx11_thread_local       : yes [2]
    - cxx11_hdr_atomic         : yes [2]
    - cxx11_allocator          : yes [2]
    - cxx14_constexpr          : yes [2]
    - cxx14_decltype_auto      : yes [2]
    - cxx14_generic_lambdas    : yes [2]
    - cxx14_return_type_deduction : yes [2]
    - cxx14_variable_templates : yes [2]
    - cxx14_type_traits        : yes [2]
    - long double support      : yes [2]
    - BOOST_ARCH_WORD_BITS == 0.0.16 : no [6]
    - BOOST_ARCH_WORD_BITS == 0.0.32 : no [6]
    - BOOST_ARCH_WORD_BITS == 0.0.64 : no [6]
    - BOOST_ARCH_X86           : no [6]
    - BOOST_ARCH_IA64          : no [6]
    - BOOST_ARCH_SPARC         : no [6]
    - BOOST_ARCH_LOONGARCH     : no [6]
    - BOOST_ARCH_MIPS          : no [6]
    - BOOST_ARCH_PARISC        : no [6]
    - BOOST_ARCH_ARM           : no [6]
    - BOOST_ARCH_RISCV         : no [6]
    - BOOST_ARCH_PPC           : no [6]
    - BOOST_ARCH_SYS390        : no [6]
    - has pthread_cond_clockwait : yes [6]
    - cxx11_constexpr          : yes [6]
    - cxx11_noexcept           : yes [6]
    - cxx11_nullptr            : yes [6]
    - cxx11_decltype           : yes [6]
    - cxx11_decltype_n3276     : yes [6]
    - cxx11_template_aliases   : yes [6]
    - cxx11_static_assert      : yes [6]
    - cxx11_rvalue_references  : yes [6]
    - cxx11_scoped_enums       : yes [6]
    - cxx11_defaulted_functions : yes [6]
    - cxx11_deleted_functions  : yes [6]
    - cxx11_hdr_ratio          : yes [6]
    - cxx11_hdr_chrono         : yes [6]
    - has unions with non-trivial members : yes [6]
    - has <type_traits> sufficient for Boost.Atomic : yes [6]
    - native atomic int32 supported : yes [2]
    - native syslog supported  : yes [2]
    - pthread supports robust mutexes : yes [2]
    - BOOST_ARCH_WORD_BITS == 0.0.16 : no [2]
    - BOOST_ARCH_WORD_BITS == 0.0.32 : no [2]
    - BOOST_ARCH_WORD_BITS == 0.0.64 : no [2]
    - BOOST_ARCH_X86           : no [2]
    - BOOST_ARCH_IA64          : no [2]
    - BOOST_ARCH_SPARC         : no [2]
    - BOOST_ARCH_LOONGARCH     : no [2]
    - BOOST_ARCH_MIPS          : no [2]
    - BOOST_ARCH_PARISC        : no [2]
    - BOOST_ARCH_ARM           : no [2]
    - BOOST_ARCH_RISCV         : no [2]
    - BOOST_ARCH_PPC           : no [2]
    - BOOST_ARCH_SYS390        : no [2]
    - has_icu builds           : no [6]
    - Boost.Regex is header-only : yes [2]
    - icu                      : no [2]
    - iconv (libc)             : yes [2]
    - GCC libquadmath and __float128 support : no [2]
    - cxx11_alignas            : yes [2]
    - zlib                     : yes [2]
    - bzip2                    : no [2]
    - lzma                     : no [2]
    - zstd                     : no [2]
    - has_lzma_cputhreads builds : no [2]
    - cxx20_hdr_concepts       : no [2]
    - cxx20_hdr_concepts       : no [4]
    - ssl                      : no [2]
    - std_wstreambuf builds    : yes [3]
    - std_wstreambuf           : yes [3]
    - cxx11_constexpr          : yes [3]
    - cxx11_variadic_templates : yes [3]
    - cxx11_hdr_thread         : yes [3]
    - cxx11_hdr_mutex          : yes [3]
    - cxx11_hdr_regex          : yes [3]
    - has std::atomic_ref      : no [3]
    - has statx                : yes [3]
    - cxx11_scoped_enums       : yes [3]
    - cxx11_noexcept           : yes [3]
    - cxx11_nullptr            : yes [3]
    - cxx11_defaulted_functions : yes [3]
    - cxx11_defaulted_moves    : yes [3]
    - cxx11_deleted_functions  : yes [3]
    - cxx11_function_template_default_args : yes [3]
    - cxx11_unified_initialization_syntax : yes [3]
    - cxx11_final              : yes [3]
    - cxx11_override           : yes [3]
    - has init_priority attribute : yes [3]
    - has stat::st_blksize     : yes [3]
    - has stat::st_mtim        : yes [3]
    - has stat::st_mtimensec   : no [3]
    - has stat::st_mtimespec   : no [3]
    - has stat::st_birthtim    : no [3]
    - has stat::st_birthtimensec : no [3]
    - has stat::st_birthtimespec : no [3]
    - has fdopendir(O_NOFOLLOW) : yes [3]
    - has dirent::d_type       : yes [3]
    - has POSIX *at APIs       : yes [3]
    - has fallocate            : yes [3]
    - has pthread_cond_clockwait : yes [3]
    - cxx11_decltype           : yes [3]
    - cxx11_decltype_n3276     : yes [3]
    - cxx11_template_aliases   : yes [3]
    - cxx11_static_assert      : yes [3]
    - cxx11_hdr_ratio          : yes [3]
    - cxx11_hdr_chrono         : yes [3]
    - has unions with non-trivial members : yes [3]
    - has <type_traits> sufficient for Boost.Atomic : yes [3]
    - exceptions               : yes [3]
    - sfinae_expr              : yes [3]
    - has <type_traits> sufficient for Boost.Scope : yes [3]
    - has_icu builds           : no [3]
    - lockfree boost::atomic_flag : yes [3]
    - cxx11_char16_t           : yes [3]
    - cxx11_char32_t           : yes [3]
    - cxx11_hdr_tuple          : yes [3]
    - boost.stacktrace.addr2line : yes [3]
    - boost.stacktrace.backtrace : yes [3]
    - boost.stacktrace.basic   : no [3]
    - boost.stacktrace.from_exception : no
    - boost.stacktrace.from_exception : no
    - boost.stacktrace.windbg  : no [3]
    - boost.stacktrace.windbg  : no [7]
    - boost.stacktrace.windbg_cached : no [3]
    - boost.stacktrace.windbg_cached : no [7]
    - cxx11_auto_declarations  : yes [3]
    - cxx11_lambdas            : yes [3]
    - cxx11_hdr_initializer_list : yes [3]
    - cxx11_numeric_limits     : yes [3]
    - cxx11_hdr_array          : yes [3]
    - cxx11_hdr_type_traits    : yes [3]
    - cxx11_explicit_conversion_operators : yes [3]
    - BOOST_ARCH_WORD_BITS == 0.0.16 : no [8]
    - BOOST_ARCH_WORD_BITS == 0.0.32 : no [8]
    - BOOST_ARCH_WORD_BITS == 0.0.64 : no [8]
    - BOOST_ARCH_X86           : no [8]
    - BOOST_ARCH_IA64          : no [8]
    - BOOST_ARCH_SPARC         : no [8]
    - BOOST_ARCH_LOONGARCH     : no [8]
    - BOOST_ARCH_MIPS          : no [8]
    - BOOST_ARCH_PARISC        : no [8]
    - BOOST_ARCH_ARM           : no [8]
    - BOOST_ARCH_RISCV         : no [8]
    - BOOST_ARCH_PPC           : no [8]
    - BOOST_ARCH_SYS390        : no [8]
    - has std::atomic_ref      : no [8]
    - has statx                : yes [8]
    - cxx11_rvalue_references  : yes [8]
    - cxx11_scoped_enums       : yes [8]
    - cxx11_noexcept           : yes [8]
    - cxx11_nullptr            : yes [8]
    - cxx11_defaulted_functions : yes [8]
    - cxx11_defaulted_moves    : yes [8]
    - cxx11_deleted_functions  : yes [8]
    - cxx11_function_template_default_args : yes [8]
    - cxx11_unified_initialization_syntax : yes [8]
    - cxx11_final              : yes [8]
    - cxx11_override           : yes [8]
    - has init_priority attribute : yes [8]
    - has stat::st_blksize     : yes [8]
    - has stat::st_mtim        : yes [8]
    - has stat::st_mtimensec   : no [8]
    - has stat::st_mtimespec   : no [8]
    - has stat::st_birthtim    : no [8]
    - has stat::st_birthtimensec : no [8]
    - has stat::st_birthtimespec : no [8]
    - has fdopendir(O_NOFOLLOW) : yes [8]
    - has dirent::d_type       : yes [8]
    - has POSIX *at APIs       : yes [8]
    - has fallocate            : yes [8]
    - has pthread_cond_clockwait : yes [8]
    - cxx11_constexpr          : yes [8]
    - cxx11_decltype           : yes [8]
    - cxx11_decltype_n3276     : yes [8]
    - cxx11_template_aliases   : yes [8]
    - cxx11_static_assert      : yes [8]
    - cxx11_hdr_ratio          : yes [8]
    - cxx11_hdr_chrono         : yes [8]
    - has unions with non-trivial members : yes [8]
    - has <type_traits> sufficient for Boost.Atomic : yes [8]
    - exceptions               : yes [8]
    - sfinae_expr              : yes [8]
    - cxx11_variadic_templates : yes [8]
    - has <type_traits> sufficient for Boost.Scope : yes [8]
    - Has Large File Support   : yes [3]
    - Has attribute init_priority : yes [3]
error: No best alternative for /home/ubuntu/boost_1_90_0/libs/mpi/build/boost_mpi with <abi>aapcs <address-model>64 <architecture>arm <asynch-exceptions>off <binary-format>elf <boost.beast.allow-deprecated>on <boost.beast.separate-compilation>on <boost.cobalt.executor>any_io_executor <boost.cobalt.pmr>std <context-impl>fcontext <coverage>off <debug-symbols>off <exception-handling>on <extern-c-nothrow>off <inlining>full <known-warnings>hide <link>static <optimization>speed <os>LINUX <pch>on <preserve-test-targets>on <profiling>off <python-debugging>off <rtti>on <runtime-debugging>off <runtime-link>shared <stdlib>native <strip>off <target-os>linux <testing.execute>on <threadapi>pthread <threading>multi <toolset-gcc:version>11 <toolset>gcc <variant>release <vectorize>off <visibility>hidden <warnings-as-errors>off <warnings>on <x-deduced-platform>arm_64
    matched: (empty)
    matched: (empty)
    - gcc visibility           : yes [3]
    - cxx11_thread_local       : yes [3]
    - cxx11_hdr_atomic         : yes [3]
    - cxx11_allocator          : yes [3]
    - cxx14_constexpr          : yes [3]
    - cxx14_decltype_auto      : yes [3]
    - cxx14_generic_lambdas    : yes [3]
    - cxx14_return_type_deduction : yes [3]
    - cxx14_variable_templates : yes [3]
    - cxx14_type_traits        : yes [3]
    - long double support      : yes [3]
    - BOOST_ARCH_WORD_BITS == 0.0.16 : no [9]
    - BOOST_ARCH_WORD_BITS == 0.0.32 : no [9]
    - BOOST_ARCH_WORD_BITS == 0.0.64 : no [9]
    - BOOST_ARCH_X86           : no [9]
    - BOOST_ARCH_IA64          : no [9]
    - BOOST_ARCH_SPARC         : no [9]
    - BOOST_ARCH_LOONGARCH     : no [9]
    - BOOST_ARCH_MIPS          : no [9]
    - BOOST_ARCH_PARISC        : no [9]
    - BOOST_ARCH_ARM           : no [9]
    - BOOST_ARCH_RISCV         : no [9]
    - BOOST_ARCH_PPC           : no [9]
    - BOOST_ARCH_SYS390        : no [9]
    - has pthread_cond_clockwait : yes [9]
    - cxx11_constexpr          : yes [9]
    - cxx11_noexcept           : yes [9]
    - cxx11_nullptr            : yes [9]
    - cxx11_decltype           : yes [9]
    - cxx11_decltype_n3276     : yes [9]
    - cxx11_template_aliases   : yes [9]
    - cxx11_static_assert      : yes [9]
    - cxx11_rvalue_references  : yes [9]
    - cxx11_scoped_enums       : yes [9]
    - cxx11_defaulted_functions : yes [9]
    - cxx11_deleted_functions  : yes [9]
    - cxx11_hdr_ratio          : yes [9]
    - cxx11_hdr_chrono         : yes [9]
    - has unions with non-trivial members : yes [9]
    - has <type_traits> sufficient for Boost.Atomic : yes [9]
    - native atomic int32 supported : yes [3]
    - native syslog supported  : yes [3]
    - pthread supports robust mutexes : yes [3]
    - BOOST_ARCH_WORD_BITS == 0.0.16 : no [3]
    - BOOST_ARCH_WORD_BITS == 0.0.32 : no [3]
    - BOOST_ARCH_WORD_BITS == 0.0.64 : no [3]
    - BOOST_ARCH_X86           : no [3]
    - BOOST_ARCH_IA64          : no [3]
    - BOOST_ARCH_SPARC         : no [3]
    - BOOST_ARCH_LOONGARCH     : no [3]
    - BOOST_ARCH_MIPS          : no [3]
    - BOOST_ARCH_PARISC        : no [3]
    - BOOST_ARCH_ARM           : no [3]
    - BOOST_ARCH_RISCV         : no [3]
    - BOOST_ARCH_PPC           : no [3]
    - BOOST_ARCH_SYS390        : no [3]
    - has_icu builds           : no [9]
    - Boost.Regex is header-only : yes [3]
    - icu                      : no [3]
    - iconv (libc)             : yes [3]
    - GCC libquadmath and __float128 support : no [3]
    - cxx11_alignas            : yes [3]
    - zlib                     : yes [3]
    - bzip2                    : no [3]
    - lzma                     : no [3]
    - zstd                     : no [3]
    - has_lzma_cputhreads builds : no [3]
    - cxx20_hdr_concepts       : no [3]
    - cxx20_hdr_concepts       : no [7]
    - ssl                      : no [3]

[1] gcc-11
[2] gcc-11/release/arm_64/threading-multi/visibility-hidden
[3] gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden
[4] gcc-11/release/arm_64/build-no/threading-multi/visibility-hidden
[5] gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden
[6] gcc-11/release/arm_64/pch-off/threading-multi/visibility-hidden
[7] gcc-11/release/arm_64/build-no/link-static/threading-multi/visibility-hidden
[8] gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden
[9] gcc-11/release/arm_64/link-static/pch-off/threading-multi/visibility-hidden

Component configuration:

    - date_time                : building
    - exception                : building
    - graph                    : building
    - graph_parallel           : building
    - serialization            : building
    - yap                      : building
    - winapi                   : building
    - wave                     : building
    - variant2                 : building
    - variant                  : building
    - uuid                     : building
    - utility                  : building
    - url                      : building
    - unordered                : building
    - typeof                   : building
    - type_traits              : building
    - type_index               : building
    - type_erasure             : building
    - tuple                    : building
    - tokenizer                : building
    - timer                    : building
    - throw_exception          : building
    - thread                   : building
    - test                     : building
    - system                   : building
    - stl_interfaces           : building
    - static_string            : building
    - static_assert            : building
    - stacktrace               : building
    - spirit                   : building
    - sort                     : building
    - smart_ptr                : building
    - signals2                 : building
    - scope                    : building
    - regex                    : building
    - redis                    : building
    - rational                 : building
    - ratio                    : building
    - random                   : building
    - python                   : building
    - ptr_container            : building
    - property_tree            : building
    - property_map             : building
    - program_options          : building
    - process                  : building
    - preprocessor             : building
    - predef                   : building
    - pool                     : building
    - poly_collection          : building
    - pfr                      : building
    - parser                   : building
    - parameter                : building
    - outcome                  : building
    - optional                 : building
    - openmethod               : building
    - nowide                   : building
    - mysql                    : building
    - multiprecision           : building
    - multi_index              : building
    - msm                      : building
    - mqtt5                    : building
    - mpl                      : building
    - mpi                      : building
    - mp11                     : building
    - move                     : building
    - metaparse                : building
    - math                     : building
    - logic                    : building
    - log                      : building
    - lockfree                 : building
    - locale                   : building
    - lexical_cast             : building
    - leaf                     : building
    - lambda2                  : building
    - lambda                   : building
    - json                     : building
    - iterator                 : building
    - iostreams                : building
    - intrusive                : building
    - interprocess             : building
    - integer                  : building
    - histogram                : building
    - heap                     : building
    - headers                  : building
    - hash2                    : building
    - hana                     : building
    - geometry                 : building
    - function_types           : building
    - function                 : building
    - format                   : building
    - flyweight                : building
    - filesystem               : building
    - fiber                    : building
    - endian                   : building
    - dynamic_bitset           : building
    - dll                      : building
    - detail                   : building
    - describe                 : building
    - crc                      : building
    - coroutine2               : building
    - coroutine                : building
    - core                     : building
    - conversion               : building
    - contract                 : building
    - context                  : building
    - container_hash           : building
    - container                : building
    - config                   : building
    - concept_check            : building
    - compat                   : building
    - cobalt                   : building
    - chrono                   : building
    - charconv                 : building
    - bloom                    : building
    - bind                     : building
    - bimap                    : building
    - beast                    : building
    - atomic                   : building
    - assign                   : building
    - assert                   : building
    - asio                     : building
    - array                    : building
    - any                      : building
    - accumulators             : building

...patience...
...patience...
...patience...
...patience...
...patience...
...found 26641 targets...
...updating 2197 targets...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/BoostDetectToolset-1.90.0.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/Boost-1.90.0/BoostConfig.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/Boost-1.90.0/BoostConfigVersion.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_headers-1.90.0/boost_headers-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_headers-1.90.0/boost_headers-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_graph_parallel-1.90.0/boost_graph_parallel-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_graph_parallel-1.90.0/boost_graph_parallel-config-version.cmake
gcc.compile.c++ bin.v2/libs/date_time/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/gregorian/greg_month.o
gcc.compile.c++ bin.v2/libs/exception/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/clone_current_exception_non_intrusive.o
gcc.archive bin.v2/libs/exception/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_exception.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_exception.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_exception-1.90.0/boost_exception-config.cmake
gcc.link.dll bin.v2/libs/date_time/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_date_time.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_date_time.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_date_time.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_date_time-1.90.0/boost_date_time-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_date_time-1.90.0/boost_date_time-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_date_time-1.90.0/libboost_date_time-variant-shared.cmake
...on 100th target...
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_archive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/archive_exception.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/codecvt_error_category.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_iarchive.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/exception.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/directory.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/portability.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/path_traits.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/path.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_iserializer.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_oserializer.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_pointer_oserializer.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_pointer_iserializer.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_serializer_map.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/unique_path.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/operations.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_xml_archive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_text_iprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_text_oprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/extended_type_info.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/extended_type_info_no_rtti.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/stl_port.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/extended_type_info_typeid.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/binary_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/binary_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_text_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_text_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_binary_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_binary_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_archive_exception.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_xml_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/void_cast.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_xml_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/codecvt_null.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_text_wiprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic_text_woprimitive.o
gcc.compile.c++ bin.v2/libs/graph/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/graphml.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_wiarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_text_wiarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_woarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_text_woarchive.o
gcc.compile.c++ bin.v2/libs/atomic/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lock_pool.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_woarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_xml_wiarchive.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_exception-1.90.0/boost_exception-config-version.cmake
gcc.link.dll bin.v2/libs/atomic/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_atomic.so.1.90.0
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/polymorphic_xml_woarchive.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_regex.so.1.90.0
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_wiarchive.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/dlmalloc.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/global_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/monotonic_buffer_resource.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_atomic.so.1.90.0
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/synchronized_pool_resource.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_grammar.o
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_atomic.so
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_regex.so
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/pool_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/unsynchronized_pool_resource.o
gcc.link.dll bin.v2/libs/filesystem/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_filesystem.so.1.90.0
gcc.link.dll bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_serialization.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_filesystem.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_filesystem.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_serialization.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_serialization-1.90.0/boost_serialization-config.cmake
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_serialization.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_serialization-1.90.0/boost_serialization-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_serialization-1.90.0/libboost_serialization-variant-shared.cmake
...on 200th target...
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/pthread/once.o
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/future.o
gcc.compile.c++ bin.v2/libs/chrono/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/thread_clock.o
gcc.compile.c++ bin.v2/libs/chrono/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/chrono.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_wgrammar.o
gcc.compile.c bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/alloc_lib.o
gcc.compile.c++ bin.v2/libs/chrono/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/process_cpu_clocks.o
gcc.link.dll bin.v2/libs/serialization/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_wserialization.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_wserialization.so.1.90.0
gcc.link.dll bin.v2/libs/container/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_container.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_wserialization.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_container.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_container.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wserialization-1.90.0/boost_wserialization-config.cmake
gcc.link.dll bin.v2/libs/chrono/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_chrono.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_chrono.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_chrono.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wserialization-1.90.0/libboost_wserialization-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wserialization-1.90.0/boost_wserialization-config-version.cmake
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/pthread/thread.o
gcc.link.dll bin.v2/libs/thread/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_thread.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_thread.so.1.90.0
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_cpp_literalgrs.o
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_thread.so
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_predef_macros.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_defined_grammar.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_cpp_grammar.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_has_include_grammar.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/wave_config_constant.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/token_ids.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cpplexer/re2clex/aq.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_filesystem-1.90.0/libboost_filesystem-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_filesystem-1.90.0/boost_filesystem-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_filesystem-1.90.0/boost_filesystem-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_atomic-1.90.0/boost_atomic-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_atomic-1.90.0/libboost_atomic-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_atomic-1.90.0/boost_atomic-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_container-1.90.0/boost_container-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_regex-1.90.0/libboost_regex-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_regex-1.90.0/boost_regex-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_container-1.90.0/boost_container-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_regex-1.90.0/boost_regex-config-version.cmake
...on 300th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_container-1.90.0/libboost_container-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cpplexer/re2clex/cpp_re.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_thread-1.90.0/libboost_thread-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_thread-1.90.0/boost_thread-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_thread-1.90.0/boost_thread-config.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_cpp_exprgrammar.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_chrono-1.90.0/libboost_chrono-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_chrono-1.90.0/boost_chrono-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_chrono-1.90.0/boost_chrono-config-version.cmake
gcc.compile.c++ bin.v2/libs/graph/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/read_graphviz_new.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/url_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/url.o
gcc.link.dll bin.v2/libs/graph/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_graph.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_graph.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_graph.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_graph-1.90.0/boost_graph-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_graph-1.90.0/boost_graph-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_graph-1.90.0/libboost_graph-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/url_view_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/segments_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/static_url.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/segments_encoded_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/segments_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/scheme.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/url_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/segments_encoded_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/segments_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/segments_encoded_ref.o
gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/dynamic_binding.o
gcc.link.dll bin.v2/libs/type_erasure/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_type_erasure.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_type_erasure.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_type_erasure.so
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/parse_query.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/pct_string_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/parse_path.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/parse.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/params_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/params_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/params_encoded_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/params_encoded_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/params_encoded_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/params_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ipv6_address.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/error.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ipv4_address.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/decode_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/authority_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/uri_reference_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/query_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/uri_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/relative_ref_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/ipv6_address_rule.o
...on 400th target...
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/string_view_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/origin_form_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/ipv4_address_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/authority_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/absolute_uri_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/error.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/delim_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/literal_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/ci_string.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/dec_octet_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/vformat.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/url_impl.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/segments_iter_impl.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/pct_format.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/replacement_field_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/params_iter_impl.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/except.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/decode.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/normalize.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/pattern.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/format_args.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/any_segments_iter.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/userinfo_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/scheme_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/any_params_iter.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/relative_part_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/port_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/ipvfuture_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/grammar/detail/recycled.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_type_erasure-1.90.0/boost_type_erasure-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_type_erasure-1.90.0/boost_type_erasure-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_type_erasure-1.90.0/libboost_type_erasure-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/ipv6_addrz_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/host_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/h16_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/ip_literal_rule.o
gcc.compile.c++ bin.v2/libs/timer/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/auto_timers_construction.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/rfc/detail/hier_part_rule.o
gcc.link.dll bin.v2/libs/url/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_url.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_url.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_url.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_url-1.90.0/boost_url-config.cmake
gcc.compile.c++ bin.v2/libs/timer/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cpu_timer.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_url-1.90.0/boost_url-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_url-1.90.0/libboost_url-variant-shared.cmake
gcc.link.dll bin.v2/libs/timer/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_timer.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_timer.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_timer.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_timer-1.90.0/boost_timer-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_timer-1.90.0/boost_timer-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_timer-1.90.0/libboost_timer-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/backtrace.o
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/addr2line.o
gcc.link.dll bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_stacktrace_addr2line.so.1.90.0
...on 500th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_addr2line.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_addr2line.so
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/compiler_log_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/debug.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/execution_monitor.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/decorator.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/execution_monitor.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/test_framework_init_observer.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/progress_monitor.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/results_reporter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/results_collector.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/plain_report_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/test_main.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/unit_test_main.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/unit_test_log.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/unit_test_monitor.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/test_tree.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/test_tools.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/framework.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_report_formatter.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_re2c_lexer_str.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/instantiate_re2c_lexer.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_log_formatter.o
gcc.link.dll bin.v2/libs/wave/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_wave.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_wave.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_wave.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wave-1.90.0/boost_wave-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wave-1.90.0/boost_wave-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wave-1.90.0/libboost_wave-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cpp_main.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/debug.o
gcc.link.dll bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_prg_exec_monitor.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_prg_exec_monitor.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_prg_exec_monitor.so
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/compiler_log_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/decorator.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/junit_log_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/test_framework_init_observer.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/results_collector.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/progress_monitor.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/plain_report_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/results_reporter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/unit_test_monitor.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/unit_test_main.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/unit_test_log.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/test_tree.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_prg_exec_monitor-1.90.0/boost_prg_exec_monitor-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_prg_exec_monitor-1.90.0/boost_prg_exec_monitor-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_prg_exec_monitor-1.90.0/libboost_prg_exec_monitor-variant-shared.cmake
gcc.link.dll bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_stacktrace_backtrace.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_backtrace.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_backtrace.so
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/test_tools.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_report_formatter.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_addr2line-1.90.0/boost_stacktrace_addr2line-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_addr2line-1.90.0/boost_stacktrace_addr2line-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_addr2line-1.90.0/libboost_stacktrace_addr2line-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/noop.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/xml_log_formatter.o
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/basic.o
gcc.link.dll bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_stacktrace_noop.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_noop.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_backtrace-1.90.0/boost_stacktrace_backtrace-config.cmake
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_noop.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_backtrace-1.90.0/boost_stacktrace_backtrace-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_backtrace-1.90.0/libboost_stacktrace_backtrace-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_noop-1.90.0/boost_stacktrace_noop-config.cmake
gcc.link.dll bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_stacktrace_basic.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_basic.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_noop-1.90.0/boost_stacktrace_noop-config-version.cmake
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_basic.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_basic-1.90.0/boost_stacktrace_basic-config.cmake
...on 600th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_basic-1.90.0/boost_stacktrace_basic-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_noop-1.90.0/libboost_stacktrace_noop-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_basic-1.90.0/libboost_stacktrace_basic-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_random.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_random.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_random-1.90.0/libboost_random-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_random-1.90.0/boost_random-config-version.cmake
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/framework.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_random-1.90.0/boost_random-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_python-1.90.0/boost_python-config.cmake
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/unit_test_parameters.o
gcc.archive bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_test_exec_monitor.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_test_exec_monitor.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_test_exec_monitor-1.90.0/boost_test_exec_monitor-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_test_exec_monitor-1.90.0/boost_test_exec_monitor-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_test_exec_monitor-1.90.0/libboost_test_exec_monitor-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/junit_log_formatter.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/positional_options.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/config_file.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/variables_map.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/convert.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/asm/make_arm64_aapcs_elf_gas.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/asm/jump_arm64_aapcs_elf_gas.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/asm/ontop_arm64_aapcs_elf_gas.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/options_description.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/winmain.o
gcc.compile.c++ bin.v2/libs/context/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fcontext.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_python-1.90.0/boost_python-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_numpy-1.90.0/boost_numpy-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_numpy-1.90.0/boost_numpy-config-version.cmake
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/parsers.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cmdline.o
gcc.compile.c++ bin.v2/libs/context/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/stack_traits.o
gcc.link.dll bin.v2/libs/context/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_context.so.1.90.0
...on 700th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_context.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_context.so
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/split.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/detail/environment_win.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/detail/last_error.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/detail/process_handle_windows.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/detail/environment_posix.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/value_semantic.o
gcc.link.dll bin.v2/libs/program_options/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_program_options.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_program_options.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_program_options.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_program_options-1.90.0/boost_program_options-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_program_options-1.90.0/boost_program_options-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_program_options-1.90.0/libboost_program_options-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/unit_test_parameters.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/detail/throw_error.o
gcc.link.dll bin.v2/libs/test/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_unit_test_framework.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_unit_test_framework.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_unit_test_framework.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_unit_test_framework-1.90.0/boost_unit_test_framework-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_unit_test_framework-1.90.0/boost_unit_test_framework-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_unit_test_framework-1.90.0/libboost_unit_test_framework-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/detail/utf8.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/ext/proc_info.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/ext/cmd.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/ext/cwd.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/posix/close_handles.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_context-1.90.0/boost_context-config.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/ext/exe.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_context-1.90.0/boost_context-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_context-1.90.0/libboost_context-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/windows/default_launcher.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cstdlib.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/ext/env.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cstdio.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/stat.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/console_buffer.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_mpi-1.90.0/boost_mpi-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_mpi-1.90.0/boost_mpi-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_mpi_python-1.90.0/boost_mpi_python-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_mpi_python-1.90.0/boost_mpi_python-config-version.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/error.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/filebuf.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/environment.o
...on 800th target...
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/iostream.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/pid.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math-1.90.0/boost_math-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math-1.90.0/boost_math-config-version.cmake
gcc.link.dll bin.v2/libs/nowide/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_nowide.so.1.90.0
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/shell.o
gcc.link.dll bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/threading-multi/visibility-hidden/libboost_process.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_process.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_process.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_process-1.90.0/boost_process-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_process-1.90.0/boost_process-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_process-1.90.0/libboost_process-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/attribute_set.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/attribute_value_set.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/encoding/codepage.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/code_conversion.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/attribute_name.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/date_time.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/named_scope.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/global_logger_storage.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/process_id.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/process_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/thread_id.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/severity_level.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/default_attribute_names.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/timer.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_ostream_backend.o
gcc.compile.c++.pch bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/pch.gch
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/core.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/record_ostream.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/acosh.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/asinh.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/atanh.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cbrt.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/copysign.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_multifile_backend.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/thread_specific.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/erfc.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/expm1.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fmax.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/erf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fmin.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fpclassify.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/hypot.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/llround.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/log1p.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lround.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/nextafter.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lgamma.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/round.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/nexttoward.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/trunc.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/acoshf.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/default_sink.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/tgamma.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/atanhf.o
gcc.link.dll bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_math_c99.so.1.90.0
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/asinhf.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99-1.90.0/boost_math_c99-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99-1.90.0/boost_math_c99-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99-1.90.0/libboost_math_c99-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/copysignf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cbrtf.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/exceptions.o
...on 900th target...
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/erfcf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/erff.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fmaxf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fminf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/expm1f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fpclassifyf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/hypotf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/llroundf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/log1pf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lgammaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lroundf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/roundf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/nextafterf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/nexttowardf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/truncf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/tgammaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/acoshl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/atanhl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/asinhl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/copysignl.o
gcc.link.dll bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_math_c99f.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99f.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99f.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99f-1.90.0/boost_math_c99f-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99f-1.90.0/boost_math_c99f-config-version.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cbrtl.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99f-1.90.0/libboost_math_c99f-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fmaxl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/expm1l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fminl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fpclassifyl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/erfcl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/hypotl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/llroundl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/erfl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/log1pl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lroundl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/nextafterl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/lgammal.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/nexttowardl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/roundl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/truncl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/tgammal.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/assoc_laguerre.o
gcc.link.dll bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_math_c99l.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99l.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99l.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99l-1.90.0/boost_math_c99l-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99l-1.90.0/boost_math_c99l-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99l-1.90.0/libboost_math_c99l-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/beta.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_1.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_2.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_3.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/assoc_legendre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_1.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_i.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_2.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_k.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/expint.o
In file included from ./boost/math/special_functions.hpp:41,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/expint.hpp: In instantiation of ‘std::pair<_FIter, _FIter> boost::math::detail::expint_fraction<T>::operator()() [with T = long double]’:
./boost/math/tools/fraction.hpp:134:20:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::detail::continued_fraction_b_impl(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/tools/fraction.hpp:172:44:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::continued_fraction_b(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/special_functions/expint.hpp:394:42:   required from ‘T boost::math::detail::expint_as_fraction(unsigned int, T, const Policy&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:499:34:   required from ‘T boost::math::detail::expint_imp(unsigned int, T, const Policy&, const Tag&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; Tag = std::integral_constant<int, 53>]’
./boost/math/special_functions/expint.hpp:554:25:   required from ‘T boost::math::detail::expint_i_imp(T, const Policy&, const std::integral_constant<int, 53>&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:1552:96:   required from ‘typename boost::math::tools::promote_args<T>::type boost::math::detail::expint_forwarder(T, const Policy&, const true_type&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::tools::promote_args<T>::type = double; std::true_type = std::integral_constant<bool, true>]’
./boost/math/special_functions/expint.hpp:1596:35:   required from ‘typename boost::math::detail::expint_result<T, U>::type boost::math::expint(T, U) [with T = double; U = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::detail::expint_result<T, U>::type = double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/c_policy.hpp:129:1:   required from ‘boost::math::tools::promote_args_t<RT> c_policies::expint(T) [with T = double; boost::math::tools::promote_args_t<RT> = double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/expint.cpp:16:67:   required from here
./boost/math/special_functions/expint.hpp:374:50: note: parameter passing for argument of type ‘std::pair<long double, long double>’ when C++17 is enabled changed to match C++14 in GCC 10.1
  374 |    BOOST_MATH_GPU_ENABLED boost::math::pair<T,T> operator()()
      |                                                  ^~~~~~~~
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/hermite.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/laguerre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/legendre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_3.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_j.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/assoc_laguerref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_neumann.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/betaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_legendre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/riemann_zeta.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_1f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_2f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/assoc_legendref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_3f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_bessel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_if.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_neumann.o
gcc.link.dll bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_math_tr1.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1-1.90.0/boost_math_tr1-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1-1.90.0/boost_math_tr1-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1-1.90.0/libboost_math_tr1-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_1f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_kf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/expintf.o
In file included from ./boost/math/special_functions.hpp:41,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/expint.hpp: In instantiation of ‘std::pair<_FIter, _FIter> boost::math::detail::expint_fraction<T>::operator()() [with T = double]’:
./boost/math/tools/fraction.hpp:134:20:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::detail::continued_fraction_b_impl(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<double>; U = double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = double; uintmax_t = long unsigned int]’
./boost/math/tools/fraction.hpp:172:44:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::continued_fraction_b(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<double>; U = double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = double; uintmax_t = long unsigned int]’
./boost/math/special_functions/expint.hpp:394:42:   required from ‘T boost::math::detail::expint_as_fraction(unsigned int, T, const Policy&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:499:34:   required from ‘T boost::math::detail::expint_imp(unsigned int, T, const Policy&, const Tag&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; Tag = std::integral_constant<int, 53>]’
./boost/math/special_functions/expint.hpp:554:25:   required from ‘T boost::math::detail::expint_i_imp(T, const Policy&, const std::integral_constant<int, 53>&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:1552:96:   required from ‘typename boost::math::tools::promote_args<T>::type boost::math::detail::expint_forwarder(T, const Policy&, const true_type&) [with T = float; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::tools::promote_args<T>::type = float; std::true_type = std::integral_constant<bool, true>]’
./boost/math/special_functions/expint.hpp:1596:35:   required from ‘typename boost::math::detail::expint_result<T, U>::type boost::math::expint(T, U) [with T = float; U = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::detail::expint_result<T, U>::type = float]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/c_policy.hpp:129:1:   required from ‘boost::math::tools::promote_args_t<RT> c_policies::expint(T) [with T = float; boost::math::tools::promote_args_t<RT> = float]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/expintf.cpp:16:67:   required from here
./boost/math/special_functions/expint.hpp:374:50: note: parameter passing for argument of type ‘std::pair<double, double>’ when C++17 is enabled changed to match C++14 in GCC 10.1
  374 |    BOOST_MATH_GPU_ENABLED boost::math::pair<T,T> operator()()
      |                                                  ^~~~~~~~
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/laguerref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_jf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/hermitef.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_2f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/legendref.o
...on 1000th target...
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_neumannf.o
In file included from ./boost/math/tools/roots.hpp:22,
                 from ./boost/math/special_functions/bessel.hpp:22,
                 from ./boost/math/special_functions/airy.hpp:16,
                 from ./boost/math/special_functions.hpp:15,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/policies/error_handling.hpp: In function ‘float boost_cyl_neumannf(float, float)’:
./boost/math/policies/error_handling.hpp:792:22: warning: ‘y’ may be used uninitialized in this function [-Wmaybe-uninitialized]
  792 |    if((val != 0) && (static_cast<R>(val) == 0))
      |                      ^~~~~~~~~~~~~~~~~~~
In file included from ./boost/math/special_functions/airy.hpp:16,
                 from ./boost/math/special_functions.hpp:15,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/bessel.hpp:316:16: note: ‘y’ was declared here
  316 |    T result_J, y; // LCOV_EXCL_LINE
      |                ^
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_3f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/assoc_laguerrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/betal.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_1l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/riemann_zetaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_legendref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_neumannf.o
In file included from ./boost/math/special_functions/airy.hpp:16,
                 from ./boost/math/special_functions.hpp:15,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/bessel.hpp: In function ‘float boost_sph_neumannf(unsigned int, float)’:
./boost/math/special_functions/bessel.hpp:371:53: warning: ‘y’ may be used uninitialized in this function [-Wmaybe-uninitialized]
  371 |    if((tx > 1) && (tools::max_value<T>() / tx < fabs(result)))
      |                                                 ~~~~^~~~~~~~
./boost/math/special_functions/bessel.hpp:316:16: note: ‘y’ was declared here
  316 |    T result_J, y; // LCOV_EXCL_LINE
      |                ^
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_besself.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_2l.o
gcc.link.dll bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_math_tr1f.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1f.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1f.so
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/assoc_legendrel.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1f-1.90.0/boost_math_tr1f-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1f-1.90.0/boost_math_tr1f-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1f-1.90.0/libboost_math_tr1f-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/comp_ellint_3l.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/text_file_backend.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_1l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_2l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_il.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/hermitel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_kl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/laguerrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/legendrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/expintl.o
In file included from ./boost/math/special_functions.hpp:41,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/expint.hpp: In instantiation of ‘std::pair<_FIter, _FIter> boost::math::detail::expint_fraction<T>::operator()() [with T = long double]’:
./boost/math/tools/fraction.hpp:134:20:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::detail::continued_fraction_b_impl(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/tools/fraction.hpp:172:44:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::continued_fraction_b(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/special_functions/expint.hpp:394:42:   required from ‘T boost::math::detail::expint_as_fraction(unsigned int, T, const Policy&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:499:34:   required from ‘T boost::math::detail::expint_imp(unsigned int, T, const Policy&, const Tag&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; Tag = std::integral_constant<int, 113>]’
./boost/math/special_functions/expint.hpp:1434:25:   required from ‘T boost::math::detail::expint_i_imp(T, const Policy&, const std::integral_constant<int, 113>&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:1552:96:   required from ‘typename boost::math::tools::promote_args<T>::type boost::math::detail::expint_forwarder(T, const Policy&, const true_type&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::tools::promote_args<T>::type = long double; std::true_type = std::integral_constant<bool, true>]’
./boost/math/special_functions/expint.hpp:1596:35:   required from ‘typename boost::math::detail::expint_result<T, U>::type boost::math::expint(T, U) [with T = long double; U = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::detail::expint_result<T, U>::type = long double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/c_policy.hpp:129:1:   required from ‘boost::math::tools::promote_args_t<RT> c_policies::expint(T) [with T = long double; boost::math::tools::promote_args_t<RT> = long double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/expintl.cpp:16:67:   required from here
./boost/math/special_functions/expint.hpp:374:50: note: parameter passing for argument of type ‘std::pair<long double, long double>’ when C++17 is enabled changed to match C++14 in GCC 10.1
  374 |    BOOST_MATH_GPU_ENABLED boost::math::pair<T,T> operator()()
      |                                                  ^~~~~~~~
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/once_block.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/ellint_3l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_bessel_jl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/cyl_neumannl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_legendrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/riemann_zetal.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/threadsafe_queue.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/timestamp.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/event.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/permissions.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_bessell.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/sph_neumannl.o
gcc.link.dll bin.v2/libs/math/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_math_tr1l.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1l.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1l.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1l-1.90.0/boost_math_tr1l-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1l-1.90.0/boost_math_tr1l-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1l-1.90.0/libboost_math_tr1l-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/dump.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/trivial.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/spirit_encoding.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/parser_utils.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/init_from_stream.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/object_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/ipc_reliable_message_queue.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/date_time_format_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/format_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/named_scope_format_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/syslog_backend.o
gcc.link.dll bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_log.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_log.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_log.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log-1.90.0/boost_log-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log-1.90.0/boost_log-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log-1.90.0/libboost_log-variant-shared.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_nowide.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_nowide.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_nowide-1.90.0/boost_nowide-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_nowide-1.90.0/boost_nowide-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_nowide-1.90.0/libboost_nowide-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/filter_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/formatter_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/settings_parser.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/formatting.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/format.o
gcc.compile.c++ bin.v2/libs/charconv/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/from_chars.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/iconv_codecvt.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/default_formatter_factory.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/ids.o
gcc.compile.c++ bin.v2/libs/charconv/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/to_chars.o
gcc.link.dll bin.v2/libs/charconv/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_charconv.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_charconv.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_charconv.so
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/mo_lambda.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/generator.o
...on 1100th target...
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/localization_backend.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/util/default_locale.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/util/encoding.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/util/codecvt_converter.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/util/info.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/shared/message.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/codecvt.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/util/locale_data.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/collate.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/std/codecvt.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/converter.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/posix_backend.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/std/collate.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/default_filter_factory.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_charconv-1.90.0/boost_charconv-config.cmake
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/std/converter.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_charconv-1.90.0/boost_charconv-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_charconv-1.90.0/libboost_charconv-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/std/std_backend.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/init_from_settings.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/util/gregorian.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/file_descriptor.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/gzip.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/zlib.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/numeric.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/mapped_file.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/algo/algorithm.o
gcc.link.dll bin.v2/libs/iostreams/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_iostreams.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_iostreams.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_iostreams.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_iostreams-1.90.0/boost_iostreams-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_iostreams-1.90.0/boost_iostreams-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_iostreams-1.90.0/libboost_iostreams-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/std/numeric.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/algo/round_robin.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/algo/shared_work.o
gcc.link.dll bin.v2/libs/locale/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_locale.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_locale.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_locale.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_locale-1.90.0/boost_locale-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_locale-1.90.0/boost_locale-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_locale-1.90.0/libboost_locale-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/barrier.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/algo/work_stealing.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/condition_variable.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/future.o
...on 1200th target...
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/setup/matches_relation_factory.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/fiber.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/waker.o
gcc.link.dll bin.v2/libs/log/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_log_setup.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_log_setup.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_log_setup.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log_setup-1.90.0/boost_log_setup-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log_setup-1.90.0/boost_log_setup-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log_setup-1.90.0/libboost_log_setup-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/context.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/properties.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/mutex.o
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/detail/coroutine_context.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/recursive_mutex.o
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/posix/stack_traits.o
gcc.compile.c++ bin.v2/libs/date_time/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/gregorian/greg_month.o
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/exceptions.o
gcc.archive bin.v2/libs/date_time/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_date_time.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_date_time.a
gcc.link.dll bin.v2/libs/coroutine/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_coroutine.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_coroutine.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_date_time-1.90.0/libboost_date_time-variant-static.cmake
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_coroutine.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_coroutine-1.90.0/boost_coroutine-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_coroutine-1.90.0/boost_coroutine-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_coroutine-1.90.0/libboost_coroutine-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/recursive_timed_mutex.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/timed_mutex.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_archive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_iserializer.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/archive_exception.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/scheduler.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_oserializer.o
gcc.link.dll bin.v2/libs/fiber/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_fiber.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_fiber.so.1.90.0
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_pointer_iserializer.o
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_fiber.so
...on 1300th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_fiber-1.90.0/boost_fiber-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_fiber-1.90.0/boost_fiber-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_fiber-1.90.0/libboost_fiber-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_pointer_oserializer.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_serializer_map.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_xml_archive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_text_iprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_text_oprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/extended_type_info.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/extended_type_info_no_rtti.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/extended_type_info_typeid.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/binary_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/binary_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/stl_port.o
gcc.compile.c++ bin.v2/libs/contract/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/contract.o
gcc.link.dll bin.v2/libs/contract/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_contract.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_contract.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_contract.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_contract-1.90.0/boost_contract-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_contract-1.90.0/boost_contract-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_contract-1.90.0/libboost_contract-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_text_iarchive.o
gcc.compile.c++ bin.v2/libs/json/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/src.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_text_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_binary_iarchive.o
gcc.link.dll bin.v2/libs/json/build/gcc-11/release/arm_64/threading-multi/visibility-hidden/libboost_json.so.1.90.0
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_json.so.1.90.0
ln-UNIX /home/ubuntu/boost_1_90_0/stage/lib/libboost_json.so
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_json-1.90.0/boost_json-config.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_json-1.90.0/boost_json-config-version.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_json-1.90.0/libboost_json-variant-shared.cmake
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_binary_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_xml_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_xml_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_archive_exception.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/void_cast.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/codecvt_null.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_text_wiprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_iarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic_text_woprimitive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_oarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_wiarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_text_wiarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_woarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_text_woarchive.o
gcc.compile.c++ bin.v2/libs/graph/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/graphml.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_xml_woarchive.o
gcc.compile.c++ bin.v2/libs/atomic/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lock_pool.o
gcc.archive bin.v2/libs/atomic/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_atomic.a
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/polymorphic_xml_wiarchive.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_atomic.a
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_woarchive.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_grammar.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_wiarchive.o
gcc.archive bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_serialization.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_serialization.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_serialization-1.90.0/libboost_serialization-variant-static.cmake
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/codecvt_error_category.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/exception.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/path_traits.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/portability.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/directory.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/dlmalloc.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/path.o
gcc.compile.c++ bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/xml_wgrammar.o
gcc.archive bin.v2/libs/serialization/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_wserialization.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_wserialization.a
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/global_resource.o
...on 1400th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wserialization-1.90.0/libboost_wserialization-variant-static.cmake
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/monotonic_buffer_resource.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_regex.a
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/synchronized_pool_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/unsynchronized_pool_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/pool_resource.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/unique_path.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/operations.o
gcc.archive bin.v2/libs/filesystem/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_filesystem.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_filesystem.a
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/pthread/once.o
gcc.compile.c++ bin.v2/libs/chrono/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/chrono.o
gcc.compile.c++ bin.v2/libs/chrono/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/thread_clock.o
gcc.compile.c++ bin.v2/libs/chrono/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/process_cpu_clocks.o
gcc.archive bin.v2/libs/chrono/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_chrono.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_chrono.a
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/future.o
gcc.compile.c bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/alloc_lib.o
gcc.archive bin.v2/libs/container/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_container.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_container.a
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/pthread/thread.o
gcc.archive bin.v2/libs/thread/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_thread.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_thread.a
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_cpp_literalgrs.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_defined_grammar.o
gcc.compile.c++ bin.v2/libs/graph/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/read_graphviz_new.o
gcc.archive bin.v2/libs/graph/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_graph.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_graph.a
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_has_include_grammar.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_graph-1.90.0/libboost_graph-variant-static.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_predef_macros.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/token_ids.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_filesystem-1.90.0/libboost_filesystem-variant-static.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_cpp_grammar.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_atomic-1.90.0/libboost_atomic-variant-static.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/wave_config_constant.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_container-1.90.0/libboost_container-variant-static.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_regex-1.90.0/libboost_regex-variant-static.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cpplexer/re2clex/aq.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_thread-1.90.0/libboost_thread-variant-static.cmake
...on 1500th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_chrono-1.90.0/libboost_chrono-variant-static.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cpplexer/re2clex/cpp_re.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_cpp_exprgrammar.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/url_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/url.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/static_url.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/url_view_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/segments_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/segments_encoded_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/segments_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/segments_encoded_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/segments_encoded_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/segments_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/scheme.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/url_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/parse_query.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/pct_string_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/parse_path.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/parse.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/params_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/params_encoded_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/params_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/params_encoded_ref.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/params_encoded_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/params_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ipv6_address.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/error.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ipv4_address.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/decode_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/authority_view.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/uri_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/uri_reference_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/relative_ref_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/query_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/ipv6_address_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/origin_form_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/string_view_base.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/ipv4_address_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/authority_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/absolute_uri_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/error.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/literal_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/delim_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/ci_string.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/dec_octet_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/vformat.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/url_impl.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/segments_iter_impl.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/pct_format.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/replacement_field_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/params_iter_impl.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/except.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/decode.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/normalize.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/pattern.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/format_args.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/any_segments_iter.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/scheme_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/userinfo_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/any_params_iter.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/port_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/relative_part_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/ipvfuture_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/grammar/detail/recycled.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/ipv6_addrz_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/host_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/ip_literal_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/h16_rule.o
gcc.compile.c++ bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/rfc/detail/hier_part_rule.o
...on 1600th target...
gcc.archive bin.v2/libs/url/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_url.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_url.a
gcc.archive bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_unit_test_framework.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_unit_test_framework.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_url-1.90.0/libboost_url-variant-static.cmake
gcc.compile.c++ bin.v2/libs/timer/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/auto_timers_construction.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_test_exec_monitor-1.90.0/libboost_test_exec_monitor-variant-static.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_unit_test_framework-1.90.0/libboost_unit_test_framework-variant-static.cmake
gcc.compile.c++ bin.v2/libs/timer/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cpu_timer.o
gcc.archive bin.v2/libs/timer/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_timer.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_timer.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_timer-1.90.0/libboost_timer-variant-static.cmake
gcc.compile.c++ bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cpp_main.o
gcc.archive bin.v2/libs/test/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_prg_exec_monitor.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_prg_exec_monitor.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_prg_exec_monitor-1.90.0/libboost_prg_exec_monitor-variant-static.cmake
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/noop.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_random.a
gcc.archive bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_stacktrace_noop.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_noop.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_noop-1.90.0/libboost_stacktrace_noop-variant-static.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_random-1.90.0/libboost_random-variant-static.cmake
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/basic.o
gcc.archive bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_stacktrace_basic.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_basic.a
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/backtrace.o
gcc.archive bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_stacktrace_backtrace.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_basic-1.90.0/libboost_stacktrace_basic-variant-static.cmake
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_backtrace.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_backtrace-1.90.0/libboost_stacktrace_backtrace-variant-static.cmake
gcc.compile.c++ bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/addr2line.o
gcc.archive bin.v2/libs/stacktrace/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_stacktrace_addr2line.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_stacktrace_addr2line.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_stacktrace_addr2line-1.90.0/libboost_stacktrace_addr2line-variant-static.cmake
gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/dynamic_binding.o
gcc.archive bin.v2/libs/type_erasure/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_type_erasure.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_type_erasure.a
...on 1700th target...
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_type_erasure-1.90.0/libboost_type_erasure-variant-static.cmake
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/config_file.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/variables_map.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/positional_options.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/options_description.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/convert.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cmdline.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/parsers.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/asm/jump_arm64_aapcs_elf_gas.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/asm/make_arm64_aapcs_elf_gas.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/asm/ontop_arm64_aapcs_elf_gas.o
gcc.compile.c++ bin.v2/libs/context/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fcontext.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/winmain.o
gcc.compile.c++ bin.v2/libs/context/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/stack_traits.o
gcc.archive bin.v2/libs/context/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_context.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_context.a
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/detail/environment_win.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/value_semantic.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/detail/last_error.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/detail/environment_posix.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/detail/process_handle_windows.o
gcc.compile.c++ bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/split.o
gcc.archive bin.v2/libs/program_options/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_program_options.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_program_options.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_program_options-1.90.0/libboost_program_options-variant-static.cmake
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_re2c_lexer.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/detail/utf8.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/detail/throw_error.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/instantiate_re2c_lexer_str.o
gcc.archive bin.v2/libs/wave/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_wave.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_wave.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_wave-1.90.0/libboost_wave-variant-static.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/ext/proc_info.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/posix/close_handles.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/windows/default_launcher.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/ext/cwd.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/ext/exe.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_context-1.90.0/libboost_context-variant-static.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/ext/env.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cstdlib.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/ext/cmd.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cstdio.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/stat.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/console_buffer.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/error.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/environment.o
...on 1800th target...
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/filebuf.o
gcc.compile.c++ bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/iostream.o
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/pid.o
gcc.archive bin.v2/libs/nowide/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_nowide.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_nowide.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_nowide-1.90.0/libboost_nowide-variant-static.cmake
gcc.compile.c++ bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/shell.o
gcc.archive bin.v2/libs/process/build/gcc-11/release/arm_64/boost.process.fs-boost/link-static/threading-multi/visibility-hidden/libboost_process.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_process.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_process-1.90.0/libboost_process-variant-static.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/attribute_set.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/attribute_value_set.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/code_conversion.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/attribute_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/global_logger_storage.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/named_scope.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/process_id.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/process_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/severity_level.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/thread_id.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/default_attribute_names.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/timer.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/record_ostream.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/core.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/once_block.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_ostream_backend.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/thread_specific.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/timestamp.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/threadsafe_queue.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_multifile_backend.o
gcc.compile.c++.pch bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/pch.gch
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/acosh.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/default_sink.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/event.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/asinh.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/atanh.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cbrt.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/copysign.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/expm1.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/erfc.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/exceptions.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/erf.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/trivial.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fmax.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fmin.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/hypot.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fpclassify.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/llround.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/log1p.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lround.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/nextafter.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lgamma.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/spirit_encoding.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/round.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/nexttoward.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/trunc.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/tgamma.o
gcc.archive bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_math_c99.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99.a
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/acoshf.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99-1.90.0/libboost_math_c99-variant-static.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/asinhf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/atanhf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/copysignf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cbrtf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/erfcf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/expm1f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fmaxf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/erff.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fminf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fpclassifyf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/log1pf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/hypotf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/llroundf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lroundf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lgammaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/nextafterf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/roundf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/tgammaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/truncf.o
...on 1900th target...
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/nexttowardf.o
gcc.archive bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_math_c99f.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99f.a
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/acoshl.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99f-1.90.0/libboost_math_c99f-variant-static.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/atanhl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/asinhl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/copysignl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cbrtl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/expm1l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fmaxl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fminl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/erfcl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fpclassifyl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/erfl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/hypotl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/llroundl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/log1pl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lroundl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/lgammal.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/nextafterl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/roundl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/nexttowardl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/truncl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/tgammal.o
gcc.archive bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_math_c99l.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_c99l.a
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/assoc_laguerre.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_c99l-1.90.0/libboost_math_c99l-variant-static.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/beta.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_1.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_2.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_3.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/assoc_legendre.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/format_parser.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_i.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_1.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_2.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_k.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/hermite.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/expint.o
In file included from ./boost/math/special_functions.hpp:41,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/expint.hpp: In instantiation of ‘std::pair<_FIter, _FIter> boost::math::detail::expint_fraction<T>::operator()() [with T = long double]’:
./boost/math/tools/fraction.hpp:134:20:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::detail::continued_fraction_b_impl(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/tools/fraction.hpp:172:44:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::continued_fraction_b(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/special_functions/expint.hpp:394:42:   required from ‘T boost::math::detail::expint_as_fraction(unsigned int, T, const Policy&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:499:34:   required from ‘T boost::math::detail::expint_imp(unsigned int, T, const Policy&, const Tag&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; Tag = std::integral_constant<int, 53>]’
./boost/math/special_functions/expint.hpp:554:25:   required from ‘T boost::math::detail::expint_i_imp(T, const Policy&, const std::integral_constant<int, 53>&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:1552:96:   required from ‘typename boost::math::tools::promote_args<T>::type boost::math::detail::expint_forwarder(T, const Policy&, const true_type&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::tools::promote_args<T>::type = double; std::true_type = std::integral_constant<bool, true>]’
./boost/math/special_functions/expint.hpp:1596:35:   required from ‘typename boost::math::detail::expint_result<T, U>::type boost::math::expint(T, U) [with T = double; U = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::detail::expint_result<T, U>::type = double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/c_policy.hpp:129:1:   required from ‘boost::math::tools::promote_args_t<RT> c_policies::expint(T) [with T = double; boost::math::tools::promote_args_t<RT> = double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/expint.cpp:16:67:   required from here
./boost/math/special_functions/expint.hpp:374:50: note: parameter passing for argument of type ‘std::pair<long double, long double>’ when C++17 is enabled changed to match C++14 in GCC 10.1
  374 |    BOOST_MATH_GPU_ENABLED boost::math::pair<T,T> operator()()
      |                                                  ^~~~~~~~
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/laguerre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/legendre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_3.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_j.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/assoc_laguerref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_legendre.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_neumann.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/riemann_zeta.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/betaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_1f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_2f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/assoc_legendref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_3f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_bessel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_if.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_neumann.o
gcc.archive bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_math_tr1.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1-1.90.0/libboost_math_tr1-variant-static.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/text_file_backend.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_1f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/hermitef.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_kf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/expintf.o
In file included from ./boost/math/special_functions.hpp:41,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/expint.hpp: In instantiation of ‘std::pair<_FIter, _FIter> boost::math::detail::expint_fraction<T>::operator()() [with T = double]’:
./boost/math/tools/fraction.hpp:134:20:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::detail::continued_fraction_b_impl(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<double>; U = double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = double; uintmax_t = long unsigned int]’
./boost/math/tools/fraction.hpp:172:44:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::continued_fraction_b(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<double>; U = double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = double; uintmax_t = long unsigned int]’
./boost/math/special_functions/expint.hpp:394:42:   required from ‘T boost::math::detail::expint_as_fraction(unsigned int, T, const Policy&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:499:34:   required from ‘T boost::math::detail::expint_imp(unsigned int, T, const Policy&, const Tag&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; Tag = std::integral_constant<int, 53>]’
./boost/math/special_functions/expint.hpp:554:25:   required from ‘T boost::math::detail::expint_i_imp(T, const Policy&, const std::integral_constant<int, 53>&) [with T = double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:1552:96:   required from ‘typename boost::math::tools::promote_args<T>::type boost::math::detail::expint_forwarder(T, const Policy&, const true_type&) [with T = float; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::tools::promote_args<T>::type = float; std::true_type = std::integral_constant<bool, true>]’
./boost/math/special_functions/expint.hpp:1596:35:   required from ‘typename boost::math::detail::expint_result<T, U>::type boost::math::expint(T, U) [with T = float; U = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::detail::expint_result<T, U>::type = float]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/c_policy.hpp:129:1:   required from ‘boost::math::tools::promote_args_t<RT> c_policies::expint(T) [with T = float; boost::math::tools::promote_args_t<RT> = float]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/expintf.cpp:16:67:   required from here
./boost/math/special_functions/expint.hpp:374:50: note: parameter passing for argument of type ‘std::pair<double, double>’ when C++17 is enabled changed to match C++14 in GCC 10.1
  374 |    BOOST_MATH_GPU_ENABLED boost::math::pair<T,T> operator()()
      |                                                  ^~~~~~~~
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/laguerref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/legendref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_jf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_2f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_neumannf.o
In file included from ./boost/math/tools/roots.hpp:22,
                 from ./boost/math/special_functions/bessel.hpp:22,
                 from ./boost/math/special_functions/airy.hpp:16,
                 from ./boost/math/special_functions.hpp:15,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/policies/error_handling.hpp: In function ‘float boost_cyl_neumannf(float, float)’:
./boost/math/policies/error_handling.hpp:792:22: warning: ‘y’ may be used uninitialized in this function [-Wmaybe-uninitialized]
  792 |    if((val != 0) && (static_cast<R>(val) == 0))
      |                      ^~~~~~~~~~~~~~~~~~~
In file included from ./boost/math/special_functions/airy.hpp:16,
                 from ./boost/math/special_functions.hpp:15,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/bessel.hpp:316:16: note: ‘y’ was declared here
  316 |    T result_J, y; // LCOV_EXCL_LINE
      |                ^
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_3f.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/assoc_laguerrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/betal.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_1l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/riemann_zetaf.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_2l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_legendref.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_besself.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_neumannf.o
In file included from ./boost/math/special_functions/airy.hpp:16,
                 from ./boost/math/special_functions.hpp:15,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/bessel.hpp: In function ‘float boost_sph_neumannf(unsigned int, float)’:
./boost/math/special_functions/bessel.hpp:371:53: warning: ‘y’ may be used uninitialized in this function [-Wmaybe-uninitialized]
  371 |    if((tx > 1) && (tools::max_value<T>() / tx < fabs(result)))
      |                                                 ~~~~^~~~~~~~
./boost/math/special_functions/bessel.hpp:316:16: note: ‘y’ was declared here
  316 |    T result_J, y; // LCOV_EXCL_LINE
      |                ^
gcc.archive bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_math_tr1f.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1f.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1f-1.90.0/libboost_math_tr1f-variant-static.cmake
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/assoc_legendrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/comp_ellint_3l.o
...on 2000th target...
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_1l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_2l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/hermitel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_il.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/expintl.o
In file included from ./boost/math/special_functions.hpp:41,
                 from /home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/special_functions/expint.hpp: In instantiation of ‘std::pair<_FIter, _FIter> boost::math::detail::expint_fraction<T>::operator()() [with T = long double]’:
./boost/math/tools/fraction.hpp:134:20:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::detail::continued_fraction_b_impl(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/tools/fraction.hpp:172:44:   required from ‘typename boost::math::tools::detail::fraction_traits<Gen>::result_type boost::math::tools::continued_fraction_b(Gen&, const U&, uintmax_t&) [with Gen = boost::math::detail::expint_fraction<long double>; U = long double; typename boost::math::tools::detail::fraction_traits<Gen>::result_type = long double; uintmax_t = long unsigned int]’
./boost/math/special_functions/expint.hpp:394:42:   required from ‘T boost::math::detail::expint_as_fraction(unsigned int, T, const Policy&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:499:34:   required from ‘T boost::math::detail::expint_imp(unsigned int, T, const Policy&, const Tag&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; Tag = std::integral_constant<int, 113>]’
./boost/math/special_functions/expint.hpp:1434:25:   required from ‘T boost::math::detail::expint_i_imp(T, const Policy&, const std::integral_constant<int, 113>&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::promote_float<false>, boost::math::policies::promote_double<false>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>]’
./boost/math/special_functions/expint.hpp:1552:96:   required from ‘typename boost::math::tools::promote_args<T>::type boost::math::detail::expint_forwarder(T, const Policy&, const true_type&) [with T = long double; Policy = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::tools::promote_args<T>::type = long double; std::true_type = std::integral_constant<bool, true>]’
./boost/math/special_functions/expint.hpp:1596:35:   required from ‘typename boost::math::detail::expint_result<T, U>::type boost::math::expint(T, U) [with T = long double; U = boost::math::policies::policy<boost::math::policies::domain_error<boost::math::policies::errno_on_error>, boost::math::policies::pole_error<boost::math::policies::errno_on_error>, boost::math::policies::overflow_error<boost::math::policies::errno_on_error>, boost::math::policies::evaluation_error<boost::math::policies::errno_on_error>, boost::math::policies::rounding_error<boost::math::policies::errno_on_error>, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy, boost::math::policies::default_policy>; typename boost::math::detail::expint_result<T, U>::type = long double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/c_policy.hpp:129:1:   required from ‘boost::math::tools::promote_args_t<RT> c_policies::expint(T) [with T = long double; boost::math::tools::promote_args_t<RT> = long double]’
/home/ubuntu/boost_1_90_0/libs/math/build/../src/tr1/expintl.cpp:16:67:   required from here
./boost/math/special_functions/expint.hpp:374:50: note: parameter passing for argument of type ‘std::pair<long double, long double>’ when C++17 is enabled changed to match C++14 in GCC 10.1
  374 |    BOOST_MATH_GPU_ENABLED boost::math::pair<T,T> operator()()
      |                                                  ^~~~~~~~
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/laguerrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/legendrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_kl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/ellint_3l.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_bessel_jl.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/permissions.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/cyl_neumannl.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_legendrel.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/riemann_zetal.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/dump.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_bessell.o
gcc.compile.c++ bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/sph_neumannl.o
gcc.archive bin.v2/libs/math/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_math_tr1l.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_math_tr1l.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_math_tr1l-1.90.0/libboost_math_tr1l-variant-static.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/parser_utils.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/init_from_stream.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/ipc_reliable_message_queue.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/object_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/date_time_format_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/named_scope_format_parser.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/syslog_backend.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/settings_parser.o
gcc.archive bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_log.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_log.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log-1.90.0/libboost_log-variant-static.cmake
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/filter_parser.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/encoding/codepage.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/formatter_parser.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/format.o
gcc.compile.c++ bin.v2/libs/charconv/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/from_chars.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/formatting.o
gcc.compile.c++ bin.v2/libs/charconv/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/to_chars.o
gcc.archive bin.v2/libs/charconv/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_charconv.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_charconv.a
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/default_formatter_factory.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/date_time.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/iconv_codecvt.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/ids.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/generator.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/mo_lambda.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/util/default_locale.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/util/codecvt_converter.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/init_from_settings.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/localization_backend.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/util/encoding.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/util/info.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/codecvt.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/util/locale_data.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/collate.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/converter.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/shared/message.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/std/codecvt.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/default_filter_factory.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/std/collate.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/posix_backend.o
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_charconv-1.90.0/libboost_charconv-variant-static.cmake
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/std/converter.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/std/std_backend.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/util/gregorian.o
...on 2100th target...
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/file_descriptor.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/mapped_file.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/gzip.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/zlib.o
gcc.archive bin.v2/libs/iostreams/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_iostreams.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_iostreams.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_iostreams-1.90.0/libboost_iostreams-variant-static.cmake
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/numeric.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/algo/algorithm.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/algo/round_robin.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/algo/shared_work.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/std/numeric.o
gcc.archive bin.v2/libs/locale/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_locale.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_locale.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_locale-1.90.0/libboost_locale-variant-static.cmake
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/algo/work_stealing.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/condition_variable.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/barrier.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/future.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/fiber.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/context.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/waker.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/properties.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/mutex.o
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/detail/coroutine_context.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/setup/matches_relation_factory.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/recursive_mutex.o
gcc.archive bin.v2/libs/log/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_log_setup.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_log_setup.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_log_setup-1.90.0/libboost_log_setup-variant-static.cmake
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/recursive_timed_mutex.o
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/posix/stack_traits.o
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/exceptions.o
gcc.archive bin.v2/libs/coroutine/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_coroutine.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_coroutine.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_coroutine-1.90.0/libboost_coroutine-variant-static.cmake
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/timed_mutex.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/scheduler.o
gcc.archive bin.v2/libs/fiber/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_fiber.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_fiber.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_fiber-1.90.0/libboost_fiber-variant-static.cmake
gcc.compile.c++ bin.v2/libs/contract/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/contract.o
gcc.archive bin.v2/libs/contract/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_contract.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_contract.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_contract-1.90.0/libboost_contract-variant-static.cmake
gcc.compile.c++ bin.v2/libs/json/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/src.o
gcc.archive bin.v2/libs/json/build/gcc-11/release/arm_64/link-static/threading-multi/visibility-hidden/libboost_json.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/libboost_json.a
common.copy /home/ubuntu/boost_1_90_0/stage/lib/cmake/boost_json-1.90.0/libboost_json-variant-static.cmake

...updated 2197 targets...


The Boost C++ Libraries were successfully built!

The following directory should be added to compiler include paths:

    /home/ubuntu/boost_1_90_0

The following directory should be added to linker library paths:

    /home/ubuntu/boost_1_90_0/stage/lib
````
