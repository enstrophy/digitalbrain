Set(io_src
    input/ReadInputFile.cpp
    output/WriteVTU.cpp
    output/FreeArrays.cpp
    PartitionMesh.cpp
    SendRecvPartOut.cpp
    Partitions.cpp
    )

add_library(io OBJECT ${io_src})
