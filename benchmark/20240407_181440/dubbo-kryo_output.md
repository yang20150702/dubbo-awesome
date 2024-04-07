# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.145 ops/ms
Iteration   1: 5.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.791 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.932 ops/ms
Iteration   1: 12.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.887 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.670 ops/ms
Iteration   1: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.031 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.516 ops/ms
Iteration   1: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.026 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.069 ms/op
Iteration   1: 2.205 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.205 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ±(99.9%) 0.048 ms/op
Iteration   1: 1.723 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.105 ms/op
Iteration   1: 2.184 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ±(99.9%) 0.094 ms/op
Iteration   1: 3.568 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.568 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.346 ±(99.9%) 0.093 ms/op
Iteration   1: 2.205 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.325 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  18.463 ms/op
                 createUser·p0.9999: 19.624 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14563
  mean =      2.205 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 298 
    [ 1.250,  2.500) = 12392 
    [ 2.500,  3.750) = 1338 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.325 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     18.463 ms/op
     p(99.9900) =     19.624 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ±(99.9%) 0.062 ms/op
Iteration   1: 1.639 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.520 ms/op
                 existUser·p0.90:   2.050 ms/op
                 existUser·p0.95:   2.304 ms/op
                 existUser·p0.99:   2.863 ms/op
                 existUser·p0.999:  15.286 ms/op
                 existUser·p0.9999: 16.729 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19511
  mean =      1.639 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1025 
    [ 1.250,  2.500) = 18028 
    [ 2.500,  3.750) = 326 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.520 ms/op
     p(90.0000) =      2.050 ms/op
     p(95.0000) =      2.304 ms/op
     p(99.0000) =      2.863 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     16.729 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ±(99.9%) 0.108 ms/op
Iteration   1: 2.005 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.367 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.433 ms/op
                 getUser·p0.99:   3.509 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15934
  mean =      2.005 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 15194 
    [ 2.500,  3.750) = 498 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.509 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.470 ±(99.9%) 0.118 ms/op
Iteration   1: 3.393 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  33.358 ms/op
                 listUser·p0.9999: 35.258 ms/op
                 listUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9431
  mean =      3.393 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 713 
    [ 2.500,  5.000) = 8482 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     33.358 ms/op
     p(99.9900) =     35.258 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.791          ops/ms
ClientSimple.existUser                       thrpt         12.887          ops/ms
ClientSimple.getUser                         thrpt         13.031          ops/ms
ClientSimple.listUser                        thrpt          8.026          ops/ms
ClientSimple.createUser                       avgt          2.205           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          2.184           ms/op
ClientSimple.listUser                         avgt          3.568           ms/op
ClientSimple.createUser                     sample  14563   2.205 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.325           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.338           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.463           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.624           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.923           ms/op
ClientSimple.existUser                      sample  19511   1.639 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.520           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.304           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.863           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.286           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.729           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.744           ms/op
ClientSimple.getUser                        sample  15934   2.005 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.367           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.509           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.859           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.990           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.990           ms/op
ClientSimple.listUser                       sample   9431   3.393 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.526           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.358           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         35.258           ms/op
ClientSimple.listUser:listUser·p1.00        sample         35.258           ms/op

Benchmark result is saved to 1712513413174.json
