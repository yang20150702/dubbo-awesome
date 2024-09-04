# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.935 ops/ms
Iteration   1: 6.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.032 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.658 ops/ms
Iteration   1: 12.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.217 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.807 ops/ms
Iteration   1: 13.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.330 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.086 ops/ms
Iteration   1: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.007 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.157 ±(99.9%) 0.076 ms/op
Iteration   1: 2.223 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.223 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.036 ±(99.9%) 0.042 ms/op
Iteration   1: 1.950 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.253 ±(99.9%) 0.054 ms/op
Iteration   1: 2.044 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.044 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.098 ms/op
Iteration   1: 3.329 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.329 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.088 ±(99.9%) 0.073 ms/op
Iteration   1: 1.857 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   1.726 ms/op
                 createUser·p0.90:   2.494 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  4.907 ms/op
                 createUser·p0.9999: 6.384 ms/op
                 createUser·p1.00:   6.390 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17163
  mean =      1.857 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 172 
    [1.000, 1.500) = 3887 
    [1.500, 2.000) = 7391 
    [2.000, 2.500) = 4025 
    [2.500, 3.000) = 1177 
    [3.000, 3.500) = 326 
    [3.500, 4.000) = 87 
    [4.000, 4.500) = 56 
    [4.500, 5.000) = 34 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =      4.907 ms/op
     p(99.9900) =      6.384 ms/op
     p(99.9990) =      6.390 ms/op
     p(99.9999) =      6.390 ms/op
    p(100.0000) =      6.390 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ±(99.9%) 0.065 ms/op
Iteration   1: 1.905 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 13.063 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16787
  mean =      1.905 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1091 
    [ 1.250,  2.500) = 14593 
    [ 2.500,  3.750) = 914 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     13.063 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.089 ±(99.9%) 0.080 ms/op
Iteration   1: 1.918 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.613 ms/op
                 getUser·p0.99:   3.208 ms/op
                 getUser·p0.999:  22.217 ms/op
                 getUser·p0.9999: 23.047 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16667
  mean =      1.918 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15392 
    [ 2.500,  5.000) = 1201 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.208 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     23.047 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.317 ±(99.9%) 0.105 ms/op
Iteration   1: 3.455 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.192 ms/op
                 listUser·p0.999:  12.345 ms/op
                 listUser·p0.9999: 13.418 ms/op
                 listUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9257
  mean =      3.455 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 994 
    [ 2.500,  3.750) = 5491 
    [ 3.750,  5.000) = 2456 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.192 ms/op
     p(99.9000) =     12.345 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.032          ops/ms
ClientSimple.existUser                       thrpt         12.217          ops/ms
ClientSimple.getUser                         thrpt         13.330          ops/ms
ClientSimple.listUser                        thrpt          8.007          ops/ms
ClientSimple.createUser                       avgt          2.223           ms/op
ClientSimple.existUser                        avgt          1.950           ms/op
ClientSimple.getUser                          avgt          2.044           ms/op
ClientSimple.listUser                         avgt          3.329           ms/op
ClientSimple.createUser                     sample  17163   1.857 ± 0.013   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.635           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.726           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.518           ms/op
ClientSimple.createUser:createUser·p0.999   sample          4.907           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          6.384           ms/op
ClientSimple.createUser:createUser·p1.00    sample          6.390           ms/op
ClientSimple.existUser                      sample  16787   1.905 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.461           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.895           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.063           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.074           ms/op
ClientSimple.getUser                        sample  16667   1.918 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.710           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.208           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.217           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.047           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.069           ms/op
ClientSimple.listUser                       sample   9257   3.455 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.866           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.192           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.345           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.418           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.418           ms/op

Benchmark result is saved to 1725430476348.json
