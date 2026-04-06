# 1. Выполнение домашнего задания

## 1) Скачайте библиотеку boost с помощью утилиты wget. Адрес для скачивания https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz.

#### Команда:
```
ubuntu@ubuntu:~$ wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
```

#### Вывод:
```
--2026-03-06 06:57:15--  https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
Resolving sourceforge.net (sourceforge.net)... 104.18.12.149, 104.18.13.149, 2606:4700::6812:c95, ...
Connecting to sourceforge.net (sourceforge.net)|104.18.12.149|:443... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/ [following]
--2026-03-06 06:57:15--  https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/
Reusing existing connection to sourceforge.net:443.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/download [following]
--2026-03-06 06:57:16--  https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz/download
Reusing existing connection to sourceforge.net:443.
HTTP request sent, awaiting response... 302 Found
Location: https://downloads.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz?ts=gAAAAABpqnrMWiNXGxeCI0qQNJD5b_acHi6C7Ov7b4QNdJSfggcvotFEj_TArI6A4CWS8mVVE3YMLV9STMilwFraQb7EREFg6A%3D%3D&use_mirror=sf-eu-introserv-1&r= [following]
--2026-03-06 06:57:16--  https://downloads.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz?ts=gAAAAABpqnrMWiNXGxeCI0qQNJD5b_acHi6C7Ov7b4QNdJSfggcvotFEj_TArI6A4CWS8mVVE3YMLV9STMilwFraQb7EREFg6A%3D%3D&use_mirror=sf-eu-introserv-1&r=
Resolving downloads.sourceforge.net (downloads.sourceforge.net)... 104.18.13.149, 104.18.12.149, 2606:4700::6812:d95, ...
Connecting to downloads.sourceforge.net (downloads.sourceforge.net)|104.18.13.149|:443... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://sf-eu-introserv-1.dl.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz?viasf=1 [following]
--2026-03-06 06:57:16--  https://sf-eu-introserv-1.dl.sourceforge.net/project/boost/boost/1.69.0/boost_1_69_0.tar.gz?viasf=1
Resolving sf-eu-introserv-1.dl.sourceforge.net (sf-eu-introserv-1.dl.sourceforge.net)... 141.95.66.71
Connecting to sf-eu-introserv-1.dl.sourceforge.net (sf-eu-introserv-1.dl.sourceforge.net)|141.95.66.71|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 111710205 (107M) [application/x-gzip]
Saving to: ‘boost_1_69_0.tar.gz’

boost_1_69_0.tar.gz           100%[==============================================>] 106.53M  11.9MB/s    in 8.7s    
```

2026-03-06 06:57:26 (12.3 MB/s) - ‘boost_1_69_0.tar.gz’ saved [111710205/111710205]

## 2) Разархивируйте скаченный файл в директорию ~/boost_1_69_0

#### Команда:
```
ubuntu@ubuntu:~$ tar -xf boost_1_69_0.tar.gz 
ubuntu@ubuntu:~$ ls
```

#### Вывод:
```
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos  boost_1_69_0  boost_1_69_0.tar.gz  snap
```


## 3) Подсчитайте количество файлов в директории ~/boost_1_69_0 не включая вложенные директории.


#### Команда:
```
ubuntu@ubuntu:~/boost_1_69_0$ find -maxdepth 1 -type f | wc -l
```
#### Вывод:
```
12
```

## 4) Подсчитайте количество файлов в директории ~/boost_1_69_0 включая вложенные директории.


#### Команда:
```
ubuntu@ubuntu:~/boost_1_69_0$ find -type f | wc -l
```
#### Вывод:
```
61191
```

## 5) Подсчитайте количество заголовочных файлов, файлов с расширением .cpp, сколько остальных файлов (не заголовочных и не .cpp).

#### Заголовочные файлы:
```
ubuntu@ubuntu:~/boost_1_69_0$ find -type f \( -name "*.h" -o -name "*.hpp" \) | wc -l
```
#### Вывод:
```
15208
```
#### Файлы .cpp:
```
ubuntu@ubuntu:~/boost_1_69_0$ find -type f -name "*.cpp" | wc -l
```
#### Вывод:
```
13774
```
#### Остальные файлы:
```
ubuntu@ubuntu:~/boost_1_69_0$ find -type f \( ! -name "*.h" -o ! -name "*.hpp" -o ! -name "*.cpp" \) | wc -l
```
#### Вывод:
```
61191
```
## 6) Найдите полный путь до файла any.hpp внутри библиотеки boost.
 
#### Команда:
```
ubuntu@ubuntu:/$ find ~/boost_1_69_0/ -path "*/boost/any.hpp"
```
####Вывод:
```
/home/ubuntu/boost_1_69_0/boost/any.hpp
```

## 7) Выведите в консоль все файлы, где упоминается последовательность boost::asio.

#### Команда:
```
ubuntu@ubuntu:/$ grep -rl "boost::asio" ~/boost_1_69_0/
```
#### Вывод:
[Tap to check output](README3.md)

## 8) Скомпилирутйе boost. Можно воспользоваться инструкцией или ссылкой.

#### Команда:
```
ubuntu@ubuntu:~/boost_1_90_0$ ./bootstrap.sh 
```

#### Вывод:
```
Building B2 engine..

###
###
### Using 'gcc' toolset.
###
###

g++ (Ubuntu 11.4.0-1ubuntu1~22.04.3) 11.4.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.


###
###

> g++ -x c++ -std=c++11 -pthread -O2 -s -DNDEBUG bindjam.cpp builtins.cpp class.cpp command.cpp compile.cpp constants.cpp cwd.cpp debug.cpp debugger.cpp events.cpp execcmd.cpp execnt.cpp execunix.cpp filent.cpp filesys.cpp fileunix.cpp frames.cpp function.cpp glob.cpp hash.cpp hcache.cpp hdrmacro.cpp headers.cpp jam_strings.cpp jam.cpp jamgram.cpp lists.cpp make.cpp make1.cpp md5.cpp mem.cpp modules.cpp native.cpp output.cpp parse.cpp pathnt.cpp pathsys.cpp pathunix.cpp regexp.cpp rules.cpp scan.cpp search.cpp startup.cpp tasks.cpp timestamp.cpp value.cpp variable.cpp w32_getreg.cpp mod_args.cpp mod_command_db.cpp mod_db.cpp mod_jam_builtin.cpp mod_jam_class.cpp mod_jam_errors.cpp mod_jam_modules.cpp mod_order.cpp mod_path.cpp mod_property_set.cpp mod_regex.cpp mod_sequence.cpp mod_set.cpp mod_string.cpp mod_summary.cpp mod_sysinfo.cpp mod_version.cpp -o b2
tools/build/src/engine/b2
Unicode/ICU support for Boost.Regex?... not found.
Generating B2 configuration in project-config.jam for gcc...

Bootstrapping is done. To build, run:

    ./b2
    
To generate header files, run:

    ./b2 headers

The configuration generated uses gcc to build by default. If that is
unintended either use the --with-toolset option or adjust configuration, by
editing 'project-config.jam'.

Further information:

   - Command line help:
     ./b2 --help
     
   - Getting started guide: 
     http://www.boost.org/more/getting_started/unix-variants.html
     
   - B2 documentation:
     http://www.boost.org/build/
```

#### Команда:
```

```

#### Вывод:

[Tap to check output](README2.md)

## 9) Перенесите все скомпилированные на предыдущем шаге статические библиотеки в директорию ~/boost-libs.

#### Команда:
```
ubuntu@ubuntu:~$ mv ~/boost_1_69_0/stage/lib/*.a ~/boost-libs
ubuntu@ubuntu:~$ ls boost-libs/
```

#### Вывод:
```
libboost_atomic.a      libboost_graph.a      libboost_prg_exec_monitor.a      libboost_system.a
libboost_chrono.a      libboost_iostreams.a  libboost_program_options.a       libboost_test_exec_monitor.a
libboost_container.a   libboost_locale.a     libboost_random.a                libboost_timer.a
libboost_context.a     libboost_math_c99.a   libboost_regex.a                 libboost_unit_test_framework.a
libboost_contract.a    libboost_math_c99f.a  libboost_serialization.a         libboost_wave.a
libboost_date_time.a   libboost_math_c99l.a  libboost_stacktrace_addr2line.a  libboost_wserialization.a
libboost_exception.a   libboost_math_tr1.a   libboost_stacktrace_backtrace.a
libboost_fiber.a       libboost_math_tr1f.a  libboost_stacktrace_basic.a
libboost_filesystem.a  libboost_math_tr1l.a  libboost_stacktrace_noop.a
```

## 10) Подсчитайте сколько занимает дискового пространства каждый файл в этой директории.

#### Команда:
```
ubuntu@ubuntu:~$ ls -lhS boost-libs/
```

#### Вывод:
```
total 35M
-rw-rw-r-- 1 ubuntu ubuntu 4.8M Mar  6 09:12 libboost_wave.a
-rw-rw-r-- 1 ubuntu ubuntu 3.9M Mar  6 09:10 libboost_math_tr1.a
-rw-rw-r-- 1 ubuntu ubuntu 3.7M Mar  6 09:11 libboost_math_tr1l.a
-rw-rw-r-- 1 ubuntu ubuntu 3.1M Mar  6 09:11 libboost_math_tr1f.a
-rw-rw-r-- 1 ubuntu ubuntu 2.8M Mar  6 09:09 libboost_regex.a
-rw-rw-r-- 1 ubuntu ubuntu 2.4M Mar  6 09:16 libboost_test_exec_monitor.a
-rw-rw-r-- 1 ubuntu ubuntu 2.4M Mar  6 09:12 libboost_unit_test_framework.a
-rw-rw-r-- 1 ubuntu ubuntu 2.2M Mar  6 09:09 libboost_locale.a
-rw-rw-r-- 1 ubuntu ubuntu 1.8M Mar  6 09:11 libboost_program_options.a
-rw-rw-r-- 1 ubuntu ubuntu 1.3M Mar  6 09:11 libboost_serialization.a
-rw-rw-r-- 1 ubuntu ubuntu 971K Mar  6 09:09 libboost_graph.a
-rw-rw-r-- 1 ubuntu ubuntu 890K Mar  6 09:11 libboost_math_c99.a
-rw-rw-r-- 1 ubuntu ubuntu 821K Mar  6 09:11 libboost_math_c99l.a
-rw-rw-r-- 1 ubuntu ubuntu 819K Mar  6 09:12 libboost_wserialization.a
-rw-rw-r-- 1 ubuntu ubuntu 625K Mar  6 09:11 libboost_math_c99f.a
-rw-rw-r-- 1 ubuntu ubuntu 445K Mar  6 09:08 libboost_filesystem.a
-rw-rw-r-- 1 ubuntu ubuntu 392K Mar  6 09:08 libboost_contract.a
-rw-rw-r-- 1 ubuntu ubuntu 271K Mar  6 09:16 libboost_chrono.a
-rw-rw-r-- 1 ubuntu ubuntu 258K Mar  6 09:08 libboost_fiber.a
-rw-rw-r-- 1 ubuntu ubuntu 234K Mar  6 09:12 libboost_prg_exec_monitor.a
-rw-rw-r-- 1 ubuntu ubuntu 179K Mar  6 09:09 libboost_iostreams.a
-rw-rw-r-- 1 ubuntu ubuntu 165K Mar  6 09:08 libboost_date_time.a
-rw-rw-r-- 1 ubuntu ubuntu 145K Mar  6 09:08 libboost_container.a
-rw-rw-r-- 1 ubuntu ubuntu  93K Mar  6 09:11 libboost_random.a
-rw-rw-r-- 1 ubuntu ubuntu  61K Mar  6 09:16 libboost_timer.a
-rw-rw-r-- 1 ubuntu ubuntu  22K Mar  6 09:08 libboost_context.a
-rw-rw-r-- 1 ubuntu ubuntu  21K Mar  6 09:12 libboost_stacktrace_addr2line.a
-rw-rw-r-- 1 ubuntu ubuntu  21K Mar  6 09:12 libboost_stacktrace_backtrace.a
-rw-rw-r-- 1 ubuntu ubuntu  13K Mar  6 09:12 libboost_stacktrace_basic.a
-rw-rw-r-- 1 ubuntu ubuntu 2.8K Mar  6 09:12 libboost_stacktrace_noop.a
-rw-rw-r-- 1 ubuntu ubuntu 2.8K Mar  6 09:08 libboost_atomic.a
-rw-rw-r-- 1 ubuntu ubuntu 1.7K Mar  6 09:13 libboost_exception.a
-rw-rw-r-- 1 ubuntu ubuntu 1.5K Mar  6 09:16 libboost_system.a
```


## 11) Найдите топ10 самых "тяжёлых".

#### Команда:
```
ubuntu@ubuntu:~$ ls -lhS boost-libs/ | head -10
```
#### Вывод:
```
total 35M
-rw-rw-r-- 1 ubuntu ubuntu 4.8M Mar  6 09:12 libboost_wave.a
-rw-rw-r-- 1 ubuntu ubuntu 3.9M Mar  6 09:10 libboost_math_tr1.a
-rw-rw-r-- 1 ubuntu ubuntu 3.7M Mar  6 09:11 libboost_math_tr1l.a
-rw-rw-r-- 1 ubuntu ubuntu 3.1M Mar  6 09:11 libboost_math_tr1f.a
-rw-rw-r-- 1 ubuntu ubuntu 2.8M Mar  6 09:09 libboost_regex.a
-rw-rw-r-- 1 ubuntu ubuntu 2.4M Mar  6 09:16 libboost_test_exec_monitor.a
-rw-rw-r-- 1 ubuntu ubuntu 2.4M Mar  6 09:12 libboost_unit_test_framework.a
-rw-rw-r-- 1 ubuntu ubuntu 2.2M Mar  6 09:09 libboost_locale.a
-rw-rw-r-- 1 ubuntu ubuntu 1.8M Mar  6 09:11 libboost_program_options.a
```

