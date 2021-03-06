cmake_minimum_required(VERSION 2.8)

project(VTK-TUTORIALS CXX)

find_package(VTK REQUIRED)
include(${VTK_USE_FILE})


add_executable(First src/example_first.cpp)
target_link_libraries(First ${VTK_LIBRARIES})

add_executable(ImageData src/example_imagedata.cpp)
target_link_libraries(ImageData ${VTK_LIBRARIES})

add_executable(StructuredGrid src/example_structuredgrid.cpp)
target_link_libraries(StructuredGrid ${VTK_LIBRARIES})

add_executable(PolyData src/example_polydata.cpp)
target_link_libraries(PolyData ${VTK_LIBRARIES})

add_executable(ActorProperties src/example_actorproperties.cpp)
target_link_libraries(ActorProperties ${VTK_LIBRARIES})

add_executable(ConeLight src/example_conelight.cpp)
target_link_libraries(ConeLight ${VTK_LIBRARIES})

add_executable(TrackballCamera src/example_trackballcamera.cpp)
target_link_libraries(TrackballCamera ${VTK_LIBRARIES})

add_executable(Save3dArray src/example_save3darray.cpp)
target_link_libraries(Save3dArray ${VTK_LIBRARIES})

add_executable(ObjReader src/example_objreader.cpp)
target_link_libraries(ObjReader ${VTK_LIBRARIES})

add_executable(ContourFilter src/example_contourfilter.cpp)
target_link_libraries(ContourFilter ${VTK_LIBRARIES})

add_executable(SmoothPolyFilter src/example_smoothpolyfilter.cpp)
target_link_libraries(SmoothPolyFilter ${VTK_LIBRARIES})

add_executable(GaussFilter src/example_gaussfilter.cpp)
target_link_libraries(GaussFilter ${VTK_LIBRARIES})

add_executable(CutterFilter src/example_cutterfilter.cpp)
target_link_libraries(CutterFilter ${VTK_LIBRARIES})

add_executable(ClipData src/example_clipdata.cpp)
target_link_libraries(ClipData ${VTK_LIBRARIES})

add_executable(ScalarBar src/example_scalarbar.cpp)
target_link_libraries(ScalarBar ${VTK_LIBRARIES})

add_executable(Historgam src/example_histogram.cpp)
target_link_libraries(Historgam ${VTK_LIBRARIES})

add_executable(LookupTable src/example_lookuptable.cpp)
target_link_libraries(LookupTable ${VTK_LIBRARIES})

add_executable(VolumeRender src/example_volumerender.cpp)
target_link_libraries(VolumeRender ${VTK_LIBRARIES})

add_executable(PlainCutWidget src/example_planecutwidget.cpp)
target_link_libraries(PlainCutWidget ${VTK_LIBRARIES})

add_executable(VectorField src/example_vectorfield.cpp)
target_link_libraries(VectorField ${VTK_LIBRARIES})

add_executable(TetraMesh src/example_tetramesh.cpp)
target_link_libraries(TetraMesh ${VTK_LIBRARIES})