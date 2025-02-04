cmake_minimum_required(VERSION 3.10)
project(RoutingAPI)

# Definir a versão do C++ a ser usada
set(CMAKE_CXX_STANDARD 17)

# Incluir diretórios de cabeçalho
include_directories(include)
include_directories(lib/cpprest/include)

# Definir os arquivos fonte
set(SOURCES
    src/main.cpp
    # src/api/Controller.cpp
    # src/db/RealmManager.cpp
    # src/models/Graph.cpp
    # src/models/Node.cpp
    # src/models/Edge.cpp
    # src/services/GraphService.cpp
)

# Definir o executável
add_executable(RoutingAPI ${SOURCES})

# Linkar as bibliotecas necessárias (por exemplo, cpprest)
target_link_libraries(RoutingAPI cpprest)
