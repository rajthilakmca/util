scala_library(name='scala',
  dependencies=[
    pants('3rdparty:jackson-mapper-asl'),
    pants('3rdparty:libthrift-0.5.0'),
    
    # TODO(John Sirois): review if this is needed - slf4j backends should generally be specified
    # at the dep leaves.
    pants('3rdparty:slf4j-nop'),
    
    pants('util/util-codec')
  ],
  sources=rglobs('*.scala')
)
