# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.187 ops/ms
Iteration   1: 7.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.104 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.181 ops/ms
Iteration   1: 13.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.250 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.060 ops/ms
Iteration   1: 13.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.519 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ops/ms
Iteration   1: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.282 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ±(99.9%) 0.073 ms/op
Iteration   1: 2.191 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.191 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.297 ±(99.9%) 0.065 ms/op
Iteration   1: 2.111 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.111 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.171 ±(99.9%) 0.074 ms/op
Iteration   1: 2.229 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ±(99.9%) 0.096 ms/op
Iteration   1: 3.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.372 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.363 ±(99.9%) 0.080 ms/op
Iteration   1: 2.169 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.404 ms/op
                 createUser·p0.95:   2.785 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  51.315 ms/op
                 createUser·p0.9999: 51.873 ms/op
                 createUser·p1.00:   51.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14744
  mean =      2.169 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14511 
    [ 5.000, 10.000) = 136 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 24 
    [25.000, 30.000) = 8 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     51.315 ms/op
     p(99.9900) =     51.873 ms/op
     p(99.9990) =     51.905 ms/op
     p(99.9999) =     51.905 ms/op
    p(100.0000) =     51.905 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ±(99.9%) 0.061 ms/op
Iteration   1: 1.840 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  12.396 ms/op
                 existUser·p0.9999: 12.676 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17419
  mean =      1.840 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 15987 
    [ 2.500,  3.750) = 1184 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =     12.396 ms/op
     p(99.9900) =     12.676 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.379 ±(99.9%) 0.097 ms/op
Iteration   1: 2.320 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.212 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   4.535 ms/op
                 getUser·p0.999:  13.945 ms/op
                 getUser·p0.9999: 14.517 ms/op
                 getUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13936
  mean =      2.320 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 9530 
    [ 2.500,  3.750) = 4005 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      4.535 ms/op
     p(99.9000) =     13.945 ms/op
     p(99.9900) =     14.517 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.113 ms/op
Iteration   1: 3.163 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.964 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 17.857 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10149
  mean =      3.163 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2193 
    [ 2.500,  3.750) = 5752 
    [ 3.750,  5.000) = 2035 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     17.857 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.104          ops/ms
ClientSimple.existUser                       thrpt         13.250          ops/ms
ClientSimple.getUser                         thrpt         13.519          ops/ms
ClientSimple.listUser                        thrpt          8.282          ops/ms
ClientSimple.createUser                       avgt          2.191           ms/op
ClientSimple.existUser                        avgt          2.111           ms/op
ClientSimple.getUser                          avgt          2.229           ms/op
ClientSimple.listUser                         avgt          3.372           ms/op
ClientSimple.createUser                     sample  14744   2.169 ± 0.072   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.682           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.404           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.734           ms/op
ClientSimple.createUser:createUser·p0.999   sample         51.315           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         51.873           ms/op
ClientSimple.createUser:createUser·p1.00    sample         51.905           ms/op
ClientSimple.existUser                      sample  17419   1.840 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.616           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.555           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.396           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.676           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.943           ms/op
ClientSimple.getUser                        sample  13936   2.320 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.810           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.212           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.535           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.945           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.517           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.549           ms/op
ClientSimple.listUser                       sample  10149   3.163 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.957           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.875           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.964           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.072           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.857           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.859           ms/op

Benchmark result is saved to 1719727932883.json
