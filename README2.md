```
Building Boost.Build engine with toolset gcc... tools/build/src/engine/bin.linuxarm/b2
Unicode/ICU support for Boost.Regex?... not found.
Generating Boost.Build configuration in project-config.jam...

Bootstrapping is done. To build, run:

    ./b2
    
To adjust configuration, edit 'project-config.jam'.
Further information:

   - Command line help:
     ./b2 --help
     
   - Getting started guide: 
     http://www.boost.org/more/getting_started/unix-variants.html
     
   - Boost.Build documentation:
     http://www.boost.org/build/doc/html/index.html
     
Performing configuration checks

    - default address-model    : 64-bit
    - default architecture     : arm

Building the Boost C++ Libraries.


    - C++11 mutex              : yes
    - lockfree boost::atomic_flag : yes
    - Boost.Config Feature Check: cxx11_auto_declarations : yes
    - Boost.Config Feature Check: cxx11_constexpr : yes
    - Boost.Config Feature Check: cxx11_defaulted_functions : yes
    - Boost.Config Feature Check: cxx11_final : yes
    - Boost.Config Feature Check: cxx11_hdr_mutex : yes
    - Boost.Config Feature Check: cxx11_hdr_tuple : yes
    - Boost.Config Feature Check: cxx11_lambdas : yes
    - Boost.Config Feature Check: cxx11_noexcept : yes
    - Boost.Config Feature Check: cxx11_nullptr : yes
    - Boost.Config Feature Check: cxx11_rvalue_references : yes
    - Boost.Config Feature Check: cxx11_template_aliases : yes
    - Boost.Config Feature Check: cxx11_thread_local : yes
    - Boost.Config Feature Check: cxx11_variadic_templates : yes
    - has_icu builds           : no
warning: Graph library does not contain MPI-based parallel components.
note: to enable them, add "using mpi ;" to your user-config.jam
    - zlib                     : no
    - bzip2                    : no
    - lzma                     : no
    - zstd                     : no
    - iconv (libc)             : yes
    - icu                      : no
    - icu (lib64)              : no
    - native-atomic-int32-supported : yes
    - native-syslog-supported  : yes
    - pthread-supports-robust-mutexes : yes
    - gcc visibility           : yes
    - long double support      : yes
warning: skipping optional Message Passing Interface (MPI) library.
note: to enable MPI support, add "using mpi ;" to user-config.jam.
note: to suppress this message, pass "--without-mpi" to bjam.
note: otherwise, you can safely ignore this message.
warning: No python installation configured and autoconfiguration
note: failed.  See http://www.boost.org/libs/python/doc/building.html
note: for configuration instructions or pass --without-python to
note: suppress this message and silently skip all Boost.Python targets
    - libbacktrace builds      : yes
    - addr2line builds         : yes
    - WinDbg builds            : no
    - WinDbgCached builds      : no
    - BOOST_COMP_GNUC >= 4.3.0 : no
    - zlib                     : no
    - bzip2                    : no
    - lzma                     : no
    - zstd                     : no

Component configuration:

    - atomic                   : building
    - chrono                   : building
    - container                : building
    - context                  : building
    - contract                 : building
    - coroutine                : building
    - date_time                : building
    - exception                : building
    - fiber                    : building
    - filesystem               : building
    - graph                    : building
    - graph_parallel           : building
    - iostreams                : building
    - locale                   : building
    - log                      : building
    - math                     : building
    - mpi                      : building
    - program_options          : building
    - python                   : building
    - random                   : building
    - regex                    : building
    - serialization            : building
    - stacktrace               : building
    - system                   : building
    - test                     : building
    - thread                   : building
    - timer                    : building
    - type_erasure             : building
    - wave                     : building

...patience...
...patience...
...patience...
...patience...
...patience...
...found 11894 targets...
...updating 1225 targets...
gcc.compile.c++ bin.v2/libs/atomic/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/lockpool.o
gcc.archive bin.v2/libs/atomic/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_atomic.a
common.copy stage/lib/libboost_atomic.a
gcc.compile.c bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/alloc_lib.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/dlmalloc.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/global_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/monotonic_buffer_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/pool_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/synchronized_pool_resource.o
gcc.compile.c++ bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/unsynchronized_pool_resource.o
gcc.archive bin.v2/libs/container/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_container.a
common.copy stage/lib/libboost_container.a
gcc.compile.asm bin.v2/libs/context/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/asm/make_arm64_aapcs_elf_gas.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/asm/jump_arm64_aapcs_elf_gas.o
gcc.compile.asm bin.v2/libs/context/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/asm/ontop_arm64_aapcs_elf_gas.o
gcc.compile.c++ bin.v2/libs/context/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/execution_context.o
gcc.compile.c++ bin.v2/libs/context/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix/stack_traits.o
gcc.archive bin.v2/libs/context/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_context.a
common.copy stage/lib/libboost_context.a
gcc.compile.c++ bin.v2/libs/contract/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/contract.o
gcc.archive bin.v2/libs/contract/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_contract.a
common.copy stage/lib/libboost_contract.a
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o
In file included from /usr/include/pthread.h:33,
                 from /usr/include/aarch64-linux-gnu/c++/11/bits/gthr-default.h:35,
                 from /usr/include/aarch64-linux-gnu/c++/11/bits/gthr.h:148,
                 from /usr/include/c++/11/ext/atomicity.h:35,
                 from /usr/include/c++/11/bits/basic_string.h:39,
                 from /usr/include/c++/11/string:55,
                 from ./boost/thread/exceptions.hpp:20,
                 from ./boost/thread/pthread/thread_data.hpp:10,
                 from ./boost/thread/thread_only.hpp:17,
                 from libs/thread/src/pthread/thread.cpp:11:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token "("
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FinderConcept<boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/iter_find.hpp:77:13:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/iter_find.hpp:26,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/algorithm/string/concept.hpp:40:18: note: in a call to non-static member function ‘void boost::algorithm::FinderConcept<FinderT, IteratorT>::constraints() [with FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >; IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   40 |             void constraints()
      |                  ^~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept_check.hpp:167:5:   required from ‘struct boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:125:16:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >]’:
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >’
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>)>’
./boost/iterator/iterator_concepts.hpp:114:7:   [ skipping 18 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’:
./boost/iterator/iterator_concepts.hpp:114:7:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::incrementable_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/concepts.hpp:136:13:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept_check.hpp:233:5:   required from ‘struct boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >]’:
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >’
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>)>’
./boost/range/concepts.hpp:152:13:   [ skipping 17 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’:
./boost/range/concepts.hpp:152:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >)>’
./boost/range/concepts.hpp:278:9:   [ skipping 12 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::single_pass_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/concepts.hpp:158:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >)>’
./boost/range/concepts.hpp:278:9:   [ skipping 12 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/range/concepts.hpp:278:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >)>’
./boost/range/algorithm/equal.hpp:174:13:   [ skipping 7 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::SinglePassIteratorConcept<Iterator>::~SinglePassIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:158:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  158 |             BOOST_CONCEPT_USAGE(SinglePassIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >]’:
./boost/range/concepts.hpp:284:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >)>’
./boost/range/algorithm/equal.hpp:174:13:   [ skipping 7 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/algorithm/equal.hpp:174:13:   required from ‘bool boost::range::equal(const SinglePassRange1&, const SinglePassRange2&) [with SinglePassRange1 = boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; SinglePassRange2 = boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/range/iterator_range_core.hpp:646:32:   required from ‘bool boost::operator==(const boost::iterator_range<IteratorT>&, const boost::iterator_range<Iterator2T>&) [with Iterator1T = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >; Iterator2T = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/find_iterator.hpp:333:32:   required from ‘bool boost::algorithm::split_iterator<IteratorT>::equal(const boost::algorithm::split_iterator<IteratorT>&) const [with IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
./boost/iterator/iterator_facade.hpp:568:26:   required from ‘static bool boost::iterators::iterator_core_access::equal(const Facade1&, const Facade2&, mpl_::true_) [with Facade1 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; Facade2 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; mpl_::true_ = mpl_::bool_<true>]’
./boost/iterator/iterator_facade.hpp:900:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator==(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; V1 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; TC1 = boost::iterators::forward_traversal_tag; Reference1 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >&; Difference1 = long int; Derived2 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; V2 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; TC2 = boost::iterators::forward_traversal_tag; Reference2 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >&; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
./boost/iterator/iterator_adaptor.hpp:305:29:   [ skipping 2 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::SinglePassRangeConcept<T>::~SinglePassRangeConcept() [with T = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:284:9: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  284 |         BOOST_CONCEPT_USAGE(SinglePassRangeConcept)
      |         ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/concept_check.hpp:167:5:   required from ‘struct boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:125:16:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   [ skipping 15 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::CopyConstructible<TT>::~CopyConstructible() [with TT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:167:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  167 |     BOOST_CONCEPT_USAGE(CopyConstructible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >]’
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 19 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::incrementable_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/range/concepts.hpp:136:13:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::IncrementableIteratorConcept<Iterator>::~IncrementableIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:136:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  136 |             BOOST_CONCEPT_USAGE(IncrementableIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/concept_check.hpp:233:5:   required from ‘struct boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::EqualityComparable<TT>::~EqualityComparable() [with TT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:233:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  233 |     BOOST_CONCEPT_USAGE(EqualityComparable) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >]’
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 18 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::single_pass_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/range/concepts.hpp:158:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::SinglePassIteratorConcept<Iterator>::~SinglePassIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:158:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  158 |             BOOST_CONCEPT_USAGE(SinglePassIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >]’
./boost/range/concepts.hpp:284:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, boost::concepts::detail::wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
./boost/concept/detail/general.hpp:51:8:   [ skipping 8 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const boost::iterators::iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const boost::iterators::iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = boost::iterators::forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = boost::iterators::forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type = bool]’
/usr/include/c++/11/bits/stl_vector.h:1562:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
/usr/include/c++/11/bits/stl_vector.h:657:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; std::vector<_Tp, _Alloc>::allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >]’
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, boost::algorithm::token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = boost::algorithm::detail::is_any_ofF<char>]’
libs/thread/src/pthread/thread.cpp:537:29:   required from here
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::SinglePassRangeConcept<T>::~SinglePassRangeConcept() [with T = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:284:9: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  284 |         BOOST_CONCEPT_USAGE(SinglePassRangeConcept)
      |         ^~~~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -pthread -O3 -finline-functions -Wno-inline -Wall -pedantic -fvisibility=hidden -Wextra -Wno-long-long -Wno-unused-parameter -Wunused-function -pedantic -DBOOST_ALL_NO_LIB=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO -DBOOST_THREAD_POSIX -DNDEBUG  -I"." -c -o "bin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o" "libs/thread/src/pthread/thread.cpp"

...failed gcc.compile.c++ bin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o...
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/once.o
gcc.compile.c++ bin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/future.o
...skipped <pbin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.a(clean) for lack of <pbin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>pthread/thread.o...
...skipped <pbin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.a for lack of <pbin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>pthread/thread.o...
...skipped <pstage/lib>libboost_thread.a for lack of <pbin.v2/libs/thread/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.a...
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/detail/coroutine_context.o
In file included from ./boost/coroutine/detail/coroutine_context.hpp:16,
                 from libs/coroutine/src/detail/coroutine_context.cpp:7:
./boost/coroutine/detail/config.hpp:17:4: warning: #warning "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING." [-Wcpp]
   17 | #  warning                  "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING."
      |    ^~~~~~~
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/exceptions.o
In file included from ./boost/coroutine/exceptions.hpp:19,
                 from libs/coroutine/src/exceptions.cpp:7:
./boost/coroutine/detail/config.hpp:17:4: warning: #warning "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING." [-Wcpp]
   17 | #  warning                  "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING."
      |    ^~~~~~~
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o
In file included from ./boost/coroutine/stack_traits.hpp:14,
                 from libs/coroutine/src/posix/stack_traits.cpp:7:
./boost/coroutine/detail/config.hpp:17:4: warning: #warning "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING." [-Wcpp]
   17 | #  warning                  "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING."
      |    ^~~~~~~
In file included from /usr/include/pthread.h:33,
                 from /usr/include/aarch64-linux-gnu/c++/11/bits/gthr-default.h:35,
                 from /usr/include/aarch64-linux-gnu/c++/11/bits/gthr.h:148,
                 from /usr/include/c++/11/ext/atomicity.h:35,
                 from /usr/include/c++/11/bits/basic_string.h:39,
                 from /usr/include/c++/11/string:55,
                 from ./boost/thread/exceptions.hpp:20,
                 from ./boost/thread/pthread/thread_data.hpp:10,
                 from ./boost/thread/thread_only.hpp:17,
                 from ./boost/thread/thread.hpp:12,
                 from ./boost/thread.hpp:13,
                 from libs/coroutine/src/posix/stack_traits.cpp:22:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token "("
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_COROUTINES_SOURCE -DBOOST_DISABLE_ASSERTS -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DNDEBUG  -I"." -c -o "bin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o" "libs/coroutine/src/posix/stack_traits.cpp"

...failed gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o...
...skipped <pbin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.a(clean) for lack of <pbin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>posix/stack_traits.o...
...skipped <pbin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.a for lack of <pbin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>posix/stack_traits.o...
...skipped <pstage/lib>libboost_coroutine.a for lack of <pbin.v2/libs/coroutine/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.a...
gcc.compile.c++ bin.v2/libs/date_time/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/gregorian/greg_month.o
gcc.compile.c++ bin.v2/libs/date_time/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/gregorian/greg_weekday.o
gcc.compile.c++ bin.v2/libs/date_time/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/gregorian/date_generators.o
gcc.archive bin.v2/libs/date_time/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_date_time.a
common.copy stage/lib/libboost_date_time.a
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/codecvt_error_category.o
...on 100th target...
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/operations.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/path.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/path_traits.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/portability.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/unique_path.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/utf8_codecvt_facet.o
gcc.compile.c++ bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/windows_file_codecvt.o
gcc.archive bin.v2/libs/filesystem/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_filesystem.a
common.copy stage/lib/libboost_filesystem.a
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/algo/algorithm.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/algo/round_robin.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/algo/shared_work.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/algo/work_stealing.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/barrier.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/condition_variable.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/context.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/fiber.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/future.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/mutex.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/properties.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/recursive_mutex.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/recursive_timed_mutex.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/timed_mutex.o
gcc.compile.c++ bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/scheduler.o
gcc.archive bin.v2/libs/fiber/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_fiber.a
common.copy stage/lib/libboost_fiber.a
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/c_regex_traits.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/cpp_regex_traits.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/cregex.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/fileiter.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/icu.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/instances.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix_api.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/regex.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/regex_debug.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/regex_raw_buffer.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/regex_traits_defaults.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/static_mutex.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/w32_regex_traits.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/wc_regex_traits.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/wide_posix_api.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/winstances.o
gcc.compile.c++ bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/usinstances.o
gcc.archive bin.v2/libs/regex/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_regex.a
common.copy stage/lib/libboost_regex.a
gcc.compile.c++ bin.v2/libs/graph/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/read_graphviz_new.o
gcc.compile.c++ bin.v2/libs/graph/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/graphml.o
gcc.archive bin.v2/libs/graph/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_graph.a
common.copy stage/lib/libboost_graph.a
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/file_descriptor.o
gcc.compile.c++ bin.v2/libs/iostreams/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/mapped_file.o
gcc.archive bin.v2/libs/iostreams/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_iostreams.a
common.copy stage/lib/libboost_iostreams.a
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/encoding/codepage.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/date_time.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/format.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/formatting.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/generator.o
In file included from libs/locale/src/shared/generator.cpp:11:
./boost/locale/localization_backend.hpp:109:18: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  109 |             std::auto_ptr<localization_backend> get() const;
      |                  ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/shared/generator.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/shared/generator.cpp:11:
./boost/locale/localization_backend.hpp:116:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  116 |             void add_backend(std::string const &name,std::auto_ptr<localization_backend> backend);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/shared/generator.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/ids.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/localization_backend.o
In file included from libs/locale/src/shared/localization_backend.cpp:9:
./boost/locale/localization_backend.hpp:109:18: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  109 |             std::auto_ptr<localization_backend> get() const;
      |                  ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/shared/localization_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/shared/localization_backend.cpp:9:
./boost/locale/localization_backend.hpp:116:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  116 |             void add_backend(std::string const &name,std::auto_ptr<localization_backend> backend);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/shared/localization_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/shared/localization_backend.cpp:185:14: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  185 |         std::auto_ptr<localization_backend> localization_backend_manager::get() const
      |              ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/shared/localization_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/shared/localization_backend.cpp: In member function ‘std::auto_ptr<boost::locale::localization_backend> boost::locale::localization_backend_manager::get() const’:
libs/locale/src/shared/localization_backend.cpp:187:18: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  187 |             std::auto_ptr<localization_backend> r(pimpl_->create());
      |                  ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/shared/localization_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/shared/localization_backend.cpp: At global scope:
libs/locale/src/shared/localization_backend.cpp:190:85: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  190 |         void localization_backend_manager::add_backend(std::string const &name,std::auto_ptr<localization_backend> backend)
      |                                                                                     ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/shared/localization_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/message.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/shared/mo_lambda.o
...on 200th target...
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/util/codecvt_converter.o
In file included from libs/locale/src/util/codecvt_converter.cpp:15:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/util/codecvt_converter.cpp:15:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/util/codecvt_converter.cpp:15:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/util/codecvt_converter.cpp:273:10: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  273 |     std::auto_ptr<base_converter> create_utf8_converter()
      |          ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/util/codecvt_converter.cpp: In function ‘std::auto_ptr<boost::locale::util::base_converter> boost::locale::util::create_utf8_converter()’:
libs/locale/src/util/codecvt_converter.cpp:275:14: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  275 |         std::auto_ptr<base_converter> res(create_utf8_converter_new_ptr());
      |              ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/util/codecvt_converter.cpp: At global scope:
libs/locale/src/util/codecvt_converter.cpp:278:10: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  278 |     std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding)
      |          ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/util/codecvt_converter.cpp: In function ‘std::auto_ptr<boost::locale::util::base_converter> boost::locale::util::create_simple_converter(const string&)’:
libs/locale/src/util/codecvt_converter.cpp:280:14: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  280 |         std::auto_ptr<base_converter> res(create_simple_converter_new_ptr(encoding));
      |              ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
libs/locale/src/util/codecvt_converter.cpp: At global scope:
libs/locale/src/util/codecvt_converter.cpp:283:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  283 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type)
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from libs/locale/src/util/codecvt_converter.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/util/default_locale.o
In file included from libs/locale/src/util/default_locale.cpp:10:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/util.hpp:10,
                 from libs/locale/src/util/default_locale.cpp:10:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/util/default_locale.cpp:10:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/util.hpp:10,
                 from libs/locale/src/util/default_locale.cpp:10:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/util/default_locale.cpp:10:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/util.hpp:10,
                 from libs/locale/src/util/default_locale.cpp:10:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/util/info.o
In file included from libs/locale/src/util/info.cpp:14:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from libs/locale/src/util/info.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/util/info.cpp:14:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from libs/locale/src/util/info.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/util/info.cpp:14:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from libs/locale/src/util/info.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/util/locale_data.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix/codecvt.o
In file included from libs/locale/src/posix/codecvt.cpp:13:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/info.hpp:15,
                 from ./boost/locale/encoding.hpp:16,
                 from libs/locale/src/posix/codecvt.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/posix/codecvt.cpp:13:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/info.hpp:15,
                 from ./boost/locale/encoding.hpp:16,
                 from libs/locale/src/posix/codecvt.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/posix/codecvt.cpp:13:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/info.hpp:15,
                 from ./boost/locale/encoding.hpp:16,
                 from libs/locale/src/posix/codecvt.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix/collate.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix/converter.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix/numeric.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/posix/posix_backend.o
In file included from libs/locale/src/posix/posix_backend.cpp:12:
./boost/locale/localization_backend.hpp:109:18: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  109 |             std::auto_ptr<localization_backend> get() const;
      |                  ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/posix/posix_backend.cpp:12:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/posix/posix_backend.cpp:12:
./boost/locale/localization_backend.hpp:116:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  116 |             void add_backend(std::string const &name,std::auto_ptr<localization_backend> backend);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/posix/posix_backend.cpp:12:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/posix/posix_backend.cpp:20:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/posix/posix_backend.cpp:12:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/posix/posix_backend.cpp:20:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/posix/posix_backend.cpp:12:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/posix/posix_backend.cpp:20:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/posix/posix_backend.cpp:12:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/std/codecvt.o
In file included from libs/locale/src/std/codecvt.cpp:11:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from libs/locale/src/std/codecvt.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/std/codecvt.cpp:11:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from libs/locale/src/std/codecvt.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/std/codecvt.cpp:11:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from libs/locale/src/std/codecvt.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/std/collate.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/std/converter.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/std/numeric.o
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/std/std_backend.o
In file included from libs/locale/src/std/std_backend.cpp:9:
./boost/locale/localization_backend.hpp:109:18: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  109 |             std::auto_ptr<localization_backend> get() const;
      |                  ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/std/std_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/std/std_backend.cpp:9:
./boost/locale/localization_backend.hpp:116:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  116 |             void add_backend(std::string const &name,std::auto_ptr<localization_backend> backend);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/std/std_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/std/std_backend.cpp:14:
./boost/locale/util.hpp:180:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  180 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_utf8_converter();
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/std/std_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/std/std_backend.cpp:14:
./boost/locale/util.hpp:188:28: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  188 |     BOOST_LOCALE_DECL std::auto_ptr<base_converter> create_simple_converter(std::string const &encoding);
      |                            ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/std/std_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
In file included from libs/locale/src/std/std_backend.cpp:14:
./boost/locale/util.hpp:203:59: warning: ‘template<class> class std::auto_ptr’ is deprecated: use 'std::unique_ptr' instead [-Wdeprecated-declarations]
  203 |     std::locale create_codecvt(std::locale const &in,std::auto_ptr<base_converter> cvt,character_facet_type type);
      |                                                           ^~~~~~~~
In file included from /usr/include/c++/11/bits/locale_conv.h:41,
                 from /usr/include/c++/11/locale:43,
                 from ./boost/locale/generator.hpp:17,
                 from ./boost/locale/localization_backend.hpp:11,
                 from libs/locale/src/std/std_backend.cpp:9:
/usr/include/c++/11/bits/unique_ptr.h:57:28: note: declared here
   57 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
gcc.compile.c++ bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/util/gregorian.o
gcc.archive bin.v2/libs/locale/build/gcc-11.4.0/release/link-static/threading-multi/visibility-hidden/libboost_locale.a
common.copy stage/lib/libboost_locale.a
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/attribute_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/attribute_set.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/attribute_value_set.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/code_conversion.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/core.o
In file included from ./boost/config/header_deprecated.hpp:18,
                 from ./boost/pending/integer_log2.hpp:5,
                 from ./boost/random/detail/integer_log2.hpp:19,
                 from ./boost/random/detail/large_arithmetic.hpp:19,
                 from ./boost/random/detail/const_mod.hpp:23,
                 from ./boost/random/detail/seed_impl.hpp:26,
                 from ./boost/random/linear_feedback_shift.hpp:27,
                 from ./boost/random/taus88.hpp:18,
                 from libs/log/src/core.cpp:30:
./boost/config/pragma_message.hpp:24:34: note: ‘#pragma message: This header is deprecated. Use <boost/integer/integer_log2.hpp> instead.’
   24 | # define BOOST_PRAGMA_MESSAGE(x) _Pragma(BOOST_STRINGIZE(message(x)))
      |                                  ^~~~~~~
./boost/config/header_deprecated.hpp:23:37: note: in expansion of macro ‘BOOST_PRAGMA_MESSAGE’
   23 | # define BOOST_HEADER_DEPRECATED(a) BOOST_PRAGMA_MESSAGE("This header is deprecated. Use " a " instead.")
      |                                     ^~~~~~~~~~~~~~~~~~~~
./boost/pending/integer_log2.hpp:7:1: note: in expansion of macro ‘BOOST_HEADER_DEPRECATED’
    7 | BOOST_HEADER_DEPRECATED("<boost/integer/integer_log2.hpp>");
      | ^~~~~~~~~~~~~~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/record_ostream.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o
In file included from /usr/include/aarch64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/aarch64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/aarch64-linux-gnu/11/include/limits.h:203,
                 from /usr/lib/gcc/aarch64-linux-gnu/11/include/syslimits.h:7,
                 from /usr/lib/gcc/aarch64-linux-gnu/11/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from libs/log/src/severity_level.cpp:16:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token "("
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_STATIC_LINK=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_FILESYSTEM_STATIC_LINK=1 -DBOOST_LOG_BUILDING_THE_LIB=1 -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_WITHOUT_DEBUG_OUTPUT -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o" "libs/log/src/severity_level.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o...
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/global_logger_storage.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/named_scope.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/process_name.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/process_id.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/thread_id.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/timer.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/exceptions.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/default_attribute_names.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/default_sink.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/text_ostream_backend.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/text_file_backend.o
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/replace.hpp:16,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FinderConcept<boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>, __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/find_format.hpp:99:13:   required from ‘void boost::algorithm::find_format_all(SequenceT&, FinderT, FormatterT) [with SequenceT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; FormatterT = boost::algorithm::detail::const_formatF<boost::iterator_range<const char*> >]’
./boost/algorithm/string/replace.hpp:652:48:   required from ‘void boost::algorithm::replace_all(SequenceT&, const Range1T&, const Range2T&) [with SequenceT = std::__cxx11::basic_string<char>; Range1T = boost::iterator_range<const char*>; Range2T = boost::iterator_range<const char*>]’
./boost/date_time/time_facet.hpp:293:36:   required from ‘OutItrT boost::date_time::time_facet<time_type, CharT, OutItrT>::put(OutItrT, std::ios_base&, boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type, const time_type&) const [with time_type = boost::posix_time::ptime; CharT = char; OutItrT = std::ostreambuf_iterator<char, std::char_traits<char> >; boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type = char]’
libs/log/src/text_file_backend.cpp:242:24:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/find_format.hpp:22,
                 from ./boost/algorithm/string/replace.hpp:22,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/algorithm/string/concept.hpp:40:18: note: in a call to non-static member function ‘void boost::algorithm::FinderConcept<FinderT, IteratorT>::constraints() [with FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’
   40 |             void constraints()
      |                  ^~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/replace.hpp:16,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FormatterConcept<boost::algorithm::detail::const_formatF<boost::iterator_range<const char*> >, boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>, __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/find_format.hpp:104:13:   required from ‘void boost::algorithm::find_format_all(SequenceT&, FinderT, FormatterT) [with SequenceT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; FormatterT = boost::algorithm::detail::const_formatF<boost::iterator_range<const char*> >]’
./boost/algorithm/string/replace.hpp:652:48:   required from ‘void boost::algorithm::replace_all(SequenceT&, const Range1T&, const Range2T&) [with SequenceT = std::__cxx11::basic_string<char>; Range1T = boost::iterator_range<const char*>; Range2T = boost::iterator_range<const char*>]’
./boost/date_time/time_facet.hpp:293:36:   required from ‘OutItrT boost::date_time::time_facet<time_type, CharT, OutItrT>::put(OutItrT, std::ios_base&, boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type, const time_type&) const [with time_type = boost::posix_time::ptime; CharT = char; OutItrT = std::ostreambuf_iterator<char, std::char_traits<char> >; boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type = char]’
libs/log/src/text_file_backend.cpp:242:24:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/find_format.hpp:22,
                 from ./boost/algorithm/string/replace.hpp:22,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/algorithm/string/concept.hpp:65:18: note: in a call to non-static member function ‘void boost::algorithm::FormatterConcept<FormatterT, FinderT, IteratorT>::constraints() [with FormatterT = boost::algorithm::detail::const_formatF<boost::iterator_range<const char*> >; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’
   65 |             void constraints()
      |                  ^~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/replace.hpp:16,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FormatterConcept<boost::algorithm::detail::const_formatF<boost::iterator_range<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > > >, boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>, __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/find_format.hpp:104:13:   required from ‘void boost::algorithm::find_format_all(SequenceT&, FinderT, FormatterT) [with SequenceT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; FormatterT = boost::algorithm::detail::const_formatF<boost::iterator_range<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > > >]’
./boost/algorithm/string/replace.hpp:652:48:   required from ‘void boost::algorithm::replace_all(SequenceT&, const Range1T&, const Range2T&) [with SequenceT = std::__cxx11::basic_string<char>; Range1T = const char*; Range2T = std::__cxx11::basic_string<char>]’
./boost/date_time/time_facet.hpp:310:38:   required from ‘OutItrT boost::date_time::time_facet<time_type, CharT, OutItrT>::put(OutItrT, std::ios_base&, boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type, const time_type&) const [with time_type = boost::posix_time::ptime; CharT = char; OutItrT = std::ostreambuf_iterator<char, std::char_traits<char> >; boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type = char]’
libs/log/src/text_file_backend.cpp:242:24:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/find_format.hpp:22,
                 from ./boost/algorithm/string/replace.hpp:22,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/algorithm/string/concept.hpp:65:18: note: in a call to non-static member function ‘void boost::algorithm::FormatterConcept<FormatterT, FinderT, IteratorT>::constraints() [with FormatterT = boost::algorithm::detail::const_formatF<boost::iterator_range<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > > >; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’
   65 |             void constraints()
      |                  ^~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/replace.hpp:16,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FormatterConcept<boost::algorithm::detail::empty_formatF<char>, boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>, __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/find_format.hpp:104:13:   required from ‘void boost::algorithm::find_format_all(SequenceT&, FinderT, FormatterT) [with SequenceT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; FormatterT = boost::algorithm::detail::empty_formatF<char>]’
./boost/algorithm/string/erase.hpp:593:48:   required from ‘void boost::algorithm::erase_all(SequenceT&, const RangeT&) [with SequenceT = std::__cxx11::basic_string<char>; RangeT = const char*]’
./boost/date_time/time_facet.hpp:321:38:   required from ‘OutItrT boost::date_time::time_facet<time_type, CharT, OutItrT>::put(OutItrT, std::ios_base&, boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type, const time_type&) const [with time_type = boost::posix_time::ptime; CharT = char; OutItrT = std::ostreambuf_iterator<char, std::char_traits<char> >; boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type = char]’
libs/log/src/text_file_backend.cpp:242:24:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/find_format.hpp:22,
                 from ./boost/algorithm/string/replace.hpp:22,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/algorithm/string/concept.hpp:65:18: note: in a call to non-static member function ‘void boost::algorithm::FormatterConcept<FormatterT, FinderT, IteratorT>::constraints() [with FormatterT = boost::algorithm::detail::empty_formatF<char>; FinderT = boost::algorithm::detail::first_finderF<const char*, boost::algorithm::is_equal>; IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’
   65 |             void constraints()
      |                  ^~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/replace.hpp:16,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FinderConcept<boost::algorithm::detail::first_finderF<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >, boost::algorithm::is_equal>, __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/find_format.hpp:99:13:   required from ‘void boost::algorithm::find_format_all(SequenceT&, FinderT, FormatterT) [with SequenceT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::first_finderF<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >, boost::algorithm::is_equal>; FormatterT = boost::algorithm::detail::empty_formatF<char>]’
./boost/algorithm/string/erase.hpp:593:48:   required from ‘void boost::algorithm::erase_all(SequenceT&, const RangeT&) [with SequenceT = std::__cxx11::basic_string<char>; RangeT = std::__cxx11::basic_string<char>]’
./boost/date_time/time_facet.hpp:339:38:   required from ‘OutItrT boost::date_time::time_facet<time_type, CharT, OutItrT>::put(OutItrT, std::ios_base&, boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type, const time_type&) const [with time_type = boost::posix_time::ptime; CharT = char; OutItrT = std::ostreambuf_iterator<char, std::char_traits<char> >; boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type = char]’
libs/log/src/text_file_backend.cpp:242:24:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/find_format.hpp:22,
                 from ./boost/algorithm/string/replace.hpp:22,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/algorithm/string/concept.hpp:40:18: note: in a call to non-static member function ‘void boost::algorithm::FinderConcept<FinderT, IteratorT>::constraints() [with FinderT = boost::algorithm::detail::first_finderF<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >, boost::algorithm::is_equal>; IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’
   40 |             void constraints()
      |                  ^~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/replace.hpp:16,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FormatterConcept<boost::algorithm::detail::empty_formatF<char>, boost::algorithm::detail::first_finderF<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >, boost::algorithm::is_equal>, __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/find_format.hpp:104:13:   required from ‘void boost::algorithm::find_format_all(SequenceT&, FinderT, FormatterT) [with SequenceT = std::__cxx11::basic_string<char>; FinderT = boost::algorithm::detail::first_finderF<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >, boost::algorithm::is_equal>; FormatterT = boost::algorithm::detail::empty_formatF<char>]’
./boost/algorithm/string/erase.hpp:593:48:   required from ‘void boost::algorithm::erase_all(SequenceT&, const RangeT&) [with SequenceT = std::__cxx11::basic_string<char>; RangeT = std::__cxx11::basic_string<char>]’
./boost/date_time/time_facet.hpp:339:38:   required from ‘OutItrT boost::date_time::time_facet<time_type, CharT, OutItrT>::put(OutItrT, std::ios_base&, boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type, const time_type&) const [with time_type = boost::posix_time::ptime; CharT = char; OutItrT = std::ostreambuf_iterator<char, std::char_traits<char> >; boost::date_time::time_facet<time_type, CharT, OutItrT>::char_type = char]’
libs/log/src/text_file_backend.cpp:242:24:   required from here
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/find_format.hpp:22,
                 from ./boost/algorithm/string/replace.hpp:22,
                 from ./boost/date_time/date_facet.hpp:17,
                 from ./boost/date_time/gregorian/gregorian_io.hpp:16,
                 from ./boost/date_time/gregorian/gregorian.hpp:31,
                 from ./boost/date_time/posix_time/time_formatters.hpp:12,
                 from ./boost/date_time/posix_time/posix_time.hpp:24,
                 from libs/log/src/text_file_backend.cpp:49:
./boost/algorithm/string/concept.hpp:65:18: note: in a call to non-static member function ‘void boost::algorithm::FormatterConcept<FormatterT, FinderT, IteratorT>::constraints() [with FormatterT = boost::algorithm::detail::empty_formatF<char>; FinderT = boost::algorithm::detail::first_finderF<__gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >, boost::algorithm::is_equal>; IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’
   65 |             void constraints()
      |                  ^~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/text_multifile_backend.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/thread_specific.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/once_block.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/timestamp.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/threadsafe_queue.o
In file included from ./boost/align/aligned_alloc.hpp:38,
                 from libs/log/src/threadsafe_queue.cpp:32:
In function ‘void boost::alignment::aligned_free(void*)’,
    inlined from ‘static void boost::log::v2s_mt_posix::aux::threadsafe_queue_impl::operator delete(void*, std::size_t)’ at libs/log/src/threadsafe_queue.cpp:149:28,
    inlined from ‘static boost::log::v2s_mt_posix::aux::threadsafe_queue_impl* boost::log::v2s_mt_posix::aux::threadsafe_queue_impl::create(boost::log::v2s_mt_posix::aux::threadsafe_queue_impl::node_base*)’ at libs/log/src/threadsafe_queue.cpp:136:56:
./boost/align/detail/aligned_alloc_posix.hpp:35:11: warning: ‘void free(void*)’ called on pointer returned from a mismatched allocation function [-Wmismatched-new-delete]
   35 |     ::free(ptr);
      |     ~~~~~~^~~~~
libs/log/src/threadsafe_queue.cpp: In static member function ‘static boost::log::v2s_mt_posix::aux::threadsafe_queue_impl* boost::log::v2s_mt_posix::aux::threadsafe_queue_impl::create(boost::log::v2s_mt_posix::aux::threadsafe_queue_impl::node_base*)’:
libs/log/src/threadsafe_queue.cpp:136:56: note: returned from ‘static void* boost::log::v2s_mt_posix::aux::threadsafe_queue_impl::operator new(std::size_t)’
  136 |     return new threadsafe_queue_impl_generic(first_node);
      |                                                        ^
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/event.o
In file included from /usr/include/aarch64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/aarch64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/aarch64-linux-gnu/11/include/limits.h:203,
                 from /usr/lib/gcc/aarch64-linux-gnu/11/include/syslimits.h:7,
                 from /usr/lib/gcc/aarch64-linux-gnu/11/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from libs/log/src/event.cpp:16:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token "("
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_STATIC_LINK=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_FILESYSTEM_STATIC_LINK=1 -DBOOST_LOG_BUILDING_THE_LIB=1 -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_WITHOUT_DEBUG_OUTPUT -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/event.o" "libs/log/src/event.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/event.o...
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/trivial.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/spirit_encoding.o
gcc.compile.c++ bin.v2/libs/log/build/gcc-11.4.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/format_parser.o
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
   40 |                                   __va_arg_pack ());
      |                                   ~~~~~~~~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/test/build/gcc-11.4.0/release/threading-multi/visibility-hidden/junit_log_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11.4.0/release/threading-multi/visibility-hidden/xml_log_formatter.o
gcc.compile.c++ bin.v2/libs/test/build/gcc-11.4.0/release/threading-multi/visibility-hidden/xml_report_formatter.o
gcc.link.dll bin.v2/libs/test/build/gcc-11.4.0/release/threading-multi/visibility-hidden/libboost_unit_test_framework.so.1.69.0
common.copy stage/lib/libboost_unit_test_framework.so.1.69.0
ln-UNIX stage/lib/libboost_unit_test_framework.so
gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o
In file included from /usr/include/pthread.h:33,
                 from /usr/include/aarch64-linux-gnu/c++/11/bits/gthr-default.h:35,
                 from /usr/include/aarch64-linux-gnu/c++/11/bits/gthr.h:148,
                 from /usr/include/c++/11/ext/atomicity.h:35,
                 from /usr/include/c++/11/bits/basic_string.h:39,
                 from /usr/include/c++/11/string:55,
                 from /usr/include/c++/11/stdexcept:39,
                 from ./boost/type_erasure/exception.hpp:14,
                 from ./boost/type_erasure/require_match.hpp:30,
                 from ./boost/type_erasure/call.hpp:40,
                 from ./boost/type_erasure/constructible.hpp:22,
                 from ./boost/type_erasure/builtin.hpp:19,
                 from ./boost/type_erasure/detail/normalize.hpp:35,
                 from ./boost/type_erasure/detail/check_map.hpp:24,
                 from ./boost/type_erasure/register_binding.hpp:14,
                 from libs/type_erasure/src/dynamic_binding.cpp:13:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token "("
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_CHRONO_DYN_LINK=1 -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_DLL=1 -DBOOST_TYPE_ERASURE_DYN_LINK -DNDEBUG  -I"." -c -o "bin.v2/libs/type_erasure/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o" "libs/type_erasure/src/dynamic_binding.cpp"

...failed gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o...
...skipped <pbin.v2/libs/type_erasure/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.so.1.69.0 for lack of <pbin.v2/libs/type_erasure/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden>dynamic_binding.o...
...skipped <pstage/lib>libboost_type_erasure.so.1.69.0 for lack of <pbin.v2/libs/type_erasure/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.so.1.69.0...
...skipped <pstage/lib>libboost_type_erasure.so for lack of <pstage/lib>libboost_type_erasure.so.1.69.0...
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_cpp_exprgrammar.o
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_cpp_exprgrammar.cpp:14:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_cpp_exprgrammar.cpp:14:
./boost/wave/util/flex_string.hpp: In member function ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_cpp_exprgrammar.cpp:14:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::util::impl::as_string(IteratorT, const IteratorT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >; IteratorT = std::_List_const_iterator<boost::wave::cpplexer::lex_token<> >]’ at ./boost/wave/util/macro_helpers.hpp:215:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_cpp_exprgrammar.cpp:14:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::util::impl::as_string(IteratorT, const IteratorT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >; IteratorT = std::_List_const_iterator<boost::wave::cpplexer::lex_token<> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_cpp_grammar.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_cpp_literalgrs.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_defined_grammar.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_predef_macros.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_re2c_lexer.o
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1284:22:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:18:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:18:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:35:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:35:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2069:30,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = char*; T2 = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = char*; ItOrChar = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1955:15,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::iterator boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1969:14,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2079:18,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = char*; T2 = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = char*; ItOrChar = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
   
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2069:30,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = const char*; T2 = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = const char*; ItOrChar = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1879:31:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1955:15,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::iterator boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1969:14,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2079:18,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = const char*; T2 = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = const char*; ItOrChar = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1879:31:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1902:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1908:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1919:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1920:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1691:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = const char*]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = const char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1693:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = const char*]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = const char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1691:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = char*]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1693:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = char*]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::clear() [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1606:13,
    inlined from ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = const char*; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’ at ./boost/wave/cpplexer/re2clex/cpp_re2c_lexer.hpp:246:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In member function ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = const char*; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::clear() [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1606:13,
    inlined from ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = char*; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’ at ./boost/wave/cpplexer/re2clex/cpp_re2c_lexer.hpp:246:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer.cpp:16:
./boost/wave/util/flex_string.hpp: In member function ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = char*; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/instantiate_re2c_lexer_str.o
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1284:22:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1285:22:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1719:19,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1711:18,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1731:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1725:19,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1731:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1725:19,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1731:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(const value_type*) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/token_cache.hpp:49:19:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/token_cache.hpp:49:19:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1284:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/token_cache.hpp:49:19:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1285:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/token_cache.hpp:49:19:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::cpplexer::token_cache<StringT>::token_cache() [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:233:13:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:233:13:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1284:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:233:13:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1285:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:233:13:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_identifier_name(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:107:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:107:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:110:24:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:110:24:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1691:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:114:24:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1693:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:114:24:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:118:16:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1632:20,
    inlined from ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/convert_trigraphs.hpp:118:16:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘StringT boost::wave::cpplexer::impl::convert_trigraphs(const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:285:17:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:285:17:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1284:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:285:17:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1285:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1510:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage> boost::wave::util::flex_string<E, T, A, Storage>::substr(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) const [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2309:62,
    inlined from ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’ at ./boost/wave/cpplexer/validate_universal_char.hpp:285:17:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::cpplexer::impl::validate_literal(const StringT&, std::size_t, std::size_t, const StringT&) [with StringT = boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2376:19:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:18:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:18:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1663:29,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:35:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const value_type*, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1666:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&, boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1652:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::append(const boost::wave::util::flex_string<E, T, A, Storage>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1644:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2377:35:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<E, T, A, S> boost::wave::util::operator+(const typename boost::wave::util::flex_string<E, T, A, S>::value_type*, const boost::wave::util::flex_string<E, T, A, S>&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; S = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2069:30,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = char*; T2 = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = char*; ItOrChar = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1955:15,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::iterator boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1969:14,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2079:18,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = char*; T2 = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = char*; ItOrChar = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In constructor ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1902:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1908:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1919:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1920:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2069:30,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = const char*; T2 = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = const char*; ItOrChar = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1879:31:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1955:15,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::iterator boost::wave::util::flex_string<E, T, A, Storage>::erase(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1969:14,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2079:18,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::ReplaceImplDiscr(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, InputIterator, InputIterator, boost::wave::util::flex_string<E, T, A, Storage>::Selector<0>) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2046:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::replace(boost::wave::util::flex_string<E, T, A, Storage>::iterator, boost::wave::util::flex_string<E, T, A, Storage>::iterator, T1, T2) [with T1 = const char*; T2 = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:2107:32,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::assign(ItOrLength, ItOrChar) [with ItOrLength = const char*; ItOrChar = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1735:21,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(InputIterator, InputIterator, const A&) [with InputIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1521:15,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1879:31:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1902:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1908:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1919:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = const char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1920:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘void boost::wave::util::flex_string<E, T, A, Storage>::InsertImpl(boost::wave::util::flex_string<E, T, A, Storage>::iterator, FwdIterator, FwdIterator, std::forward_iterator_tag) [with FwdIterator = const char*; E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1691:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1693:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::reserve(boost::wave::util::CowString<Storage, Align>::size_type) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1381:23,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::reserve(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1602:25,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1691:20,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::append(FwdIterator, FwdIterator) [with FwdIterator = char*; Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1374:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::push_back(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1693:24,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>& boost::wave::util::flex_string<E, T, A, Storage>::operator+=(boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1639:18,
    inlined from ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’ at cpp.re:524:28:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::token_id boost::wave::cpplexer::re2clex::scan(boost::wave::cpplexer::re2clex::Scanner<Iterator>*) [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::clear() [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1606:13,
    inlined from ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’ at ./boost/wave/cpplexer/re2clex/cpp_re2c_lexer.hpp:246:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In member function ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = __gnu_cxx::__normal_iterator<const char*, std::__cxx11::basic_string<char> >; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from /usr/include/c++/11/bits/locale_classes.h:40,
                 from /usr/include/c++/11/bits/ios_base.h:41,
                 from /usr/include/c++/11/streambuf:41,
                 from /usr/include/c++/11/bits/streambuf_iterator.h:35,
                 from /usr/include/c++/11/iterator:66,
                 from ./boost/iterator/iterator_categories.hpp:23,
                 from ./boost/iterator/iterator_adaptor.hpp:12,
                 from ./boost/iterator/reverse_iterator.hpp:10,
                 from ./boost/wave/util/flex_string.hpp:90,
                 from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘void boost::wave::util::CowString<Storage, Align>::resize(boost::wave::util::CowString<Storage, Align>::size_type, boost::wave::util::CowString<Storage, Align>::E) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1367:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type, boost::wave::util::flex_string<E, T, A, Storage>::value_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1591:22,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::resize(boost::wave::util::flex_string<E, T, A, Storage>::size_type) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1594:13,
    inlined from ‘void boost::wave::util::flex_string<E, T, A, Storage>::clear() [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1606:13,
    inlined from ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’ at ./boost/wave/cpplexer/re2clex/cpp_re2c_lexer.hpp:246:20:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/instantiate_re2c_lexer_str.cpp:16:
./boost/wave/util/flex_string.hpp: In member function ‘TokenT& boost::wave::cpplexer::re2clex::lexer<IteratorT, PositionT, TokenT>::get(TokenT&) [with IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >; PositionT = boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > >; TokenT = boost::wave::cpplexer::lex_token<boost::wave::util::file_position<boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > > >]’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/token_ids.o
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from libs/wave/src/token_ids.cpp:18:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1283:23,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > boost::wave::get_token_name(boost::wave::token_id)’ at libs/wave/src/token_ids.cpp:233:64:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/token_ids.cpp:22:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > boost::wave::get_token_name(boost::wave::token_id)’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from libs/wave/src/token_ids.cpp:18:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::resize(boost::wave::util::AllocatorStringStorage<E, A>::size_type, E) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:676:16,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1284:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > boost::wave::get_token_name(boost::wave::token_id)’ at libs/wave/src/token_ids.cpp:233:64:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/token_ids.cpp:22:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > boost::wave::get_token_name(boost::wave::token_id)’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/aarch64-linux-gnu/c++/11/bits/c++allocator.h:33,
                 from /usr/include/c++/11/bits/allocator.h:46,
                 from /usr/include/c++/11/string:41,
                 from libs/wave/src/token_ids.cpp:18:
In member function ‘void __gnu_cxx::new_allocator<_Tp>::deallocate(_Tp*, __gnu_cxx::new_allocator<_Tp>::size_type) [with _Tp = char]’,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::Free(void*, boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:566:22,
    inlined from ‘boost::wave::util::AllocatorStringStorage<E, A>::~AllocatorStringStorage() [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:648:17,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::reserve(boost::wave::util::AllocatorStringStorage<E, A>::size_type) [with E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:702:5,
    inlined from ‘void boost::wave::util::AllocatorStringStorage<E, A>::append(ForwardIterator, ForwardIterator) [with ForwardIterator = const char*; E = char; A = std::allocator<char>]’ at ./boost/wave/util/flex_string.hpp:715:20,
    inlined from ‘boost::wave::util::CowString<Storage, Align>::CowString(const E*, boost::wave::util::CowString<Storage, Align>::size_type, const allocator_type&) [with Storage = boost::wave::util::AllocatorStringStorage<char>; Align = char*]’ at ./boost/wave/util/flex_string.hpp:1285:22,
    inlined from ‘boost::wave::util::flex_string<E, T, A, Storage>::flex_string(const value_type*, const A&) [with E = char; T = std::char_traits<char>; A = std::allocator<char>; Storage = boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> >]’ at ./boost/wave/util/flex_string.hpp:1506:43,
    inlined from ‘boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > boost::wave::get_token_name(boost::wave::token_id)’ at libs/wave/src/token_ids.cpp:233:64:
/usr/include/c++/11/ext/new_allocator.h:145:26: warning: ‘void operator delete(void*, std::size_t)’ called on unallocated object ‘boost::wave::util::SimpleStringStorage<char, std::allocator<char> >::emptyString_’ [-Wfree-nonheap-object]
  145 |         ::operator delete(__p
      |         ~~~~~~~~~~~~~~~~~^~~~
  146 | #if __cpp_sized_deallocation
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  147 |                           , __t * sizeof(_Tp)
      |                           ~~~~~~~~~~~~~~~~~~~
  148 | #endif
      | ~~~~~~                    
  149 |                          );
      |                          ~
In file included from ./boost/wave/wave_config.hpp:230,
                 from libs/wave/src/token_ids.cpp:22:
./boost/wave/util/flex_string.hpp: In function ‘boost::wave::util::flex_string<char, std::char_traits<char>, std::allocator<char>, boost::wave::util::CowString<boost::wave::util::AllocatorStringStorage<char> > > boost::wave::get_token_name(boost::wave::token_id)’:
./boost/wave/util/flex_string.hpp:535:1: note: declared here
  535 | SimpleStringStorage<E, A>::emptyString_ =
      | ^~~~~~~~~~~~~~~~~~~~~~~~~
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/wave_config_constant.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/cpplexer/re2clex/aq.o
gcc.compile.c++ bin.v2/libs/wave/build/gcc-11.4.0/release/threading-multi/visibility-hidden/cpplexer/re2clex/cpp_re.o
...skipped <pbin.v2/libs/wave/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_wave.so.1.69.0 for lack of <pbin.v2/libs/thread/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.so.1.69.0...
...skipped <pstage/lib>libboost_wave.so.1.69.0 for lack of <pbin.v2/libs/wave/build/gcc-11.4.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_wave.so.1.69.0...
...skipped <pstage/lib>libboost_wave.so for lack of <pstage/lib>libboost_wave.so.1.69.0...
...failed updating 12 targets...
...skipped 33 targets...
...updated 1180 targets...
```
