/bin/clang++ -Xclang -ast-dump -E -fplugin=lib/PrintFunctionNames.so -fplugin-arg-set-ai main.cpp
