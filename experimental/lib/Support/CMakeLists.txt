add_dynamatic_library(DynamaticExperimentalSupport
  BlifReader.cpp
  CutlessMapping.cpp
  SubjectGraph.cpp
  CDGAnalysis.cpp
  StdProfiler.cpp
  HandshakeSimulator.cpp
  FtdImplementation.cpp
  FtdSupport.cpp
  FormalProperty.cpp

  LINK_LIBS PUBLIC
  MLIRIR
  MLIRLLVMDialect
  MLIRMemRefDialect
  MLIROptLib
  MLIRParser
  MLIRFuncDialect
  MLIRSupport
  MLIRTransforms
  MLIRSCFDialect
)

add_subdirectory(BooleanLogic)
