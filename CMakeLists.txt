cmake_minimum_required(VERSION 3.19.3)
project(Cork)

set(SOURCES
src/accel/aabvh.h
src/cork.cpp
src/cork.h
src/file_formats/files.cpp
src/file_formats/files.h
src/file_formats/ifs.cpp
src/file_formats/off.cpp
src/isct/absext4.h
src/isct/CDTtriangle.c
src/isct/CDTtriangle.h
src/isct/empty3d.cpp
src/isct/empty3d.h
src/isct/ext4.h
src/isct/fixext4.h
src/isct/fixint.h
src/isct/gmpext4.h
src/isct/quantization.cpp
src/isct/quantization.h
src/isct/unsafeRayTriIsct.h
src/math/bbox.h
src/math/ray.h
src/math/vec.h
src/mesh/mesh.bool.tpp
src/mesh/mesh.decl.h
src/mesh/mesh.h
src/mesh/mesh.isct.tpp
src/mesh/mesh.remesh.tpp
src/mesh/mesh.topoCache.tpp
src/mesh/mesh.tpp
src/off2obj.cpp
src/rawmesh/rawMesh.h
src/rawmesh/rawMesh.tpp
src/util/iterPool.h
src/util/log.cpp
src/util/memPool.h
src/util/prelude.h
src/util/shortVec.h
src/util/timer.cpp
src/util/unionFind.h
# src/main.cpp
# win/DLLTest/DLLTest.cpp
)
add_library( ${PROJECT_NAME} ${SOURCES})
