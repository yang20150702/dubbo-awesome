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
# Warmup Iteration   1: 1.505 ops/ms
Iteration   1: 5.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.486 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ops/ms
Iteration   1: 12.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.149 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.013 ops/ms
Iteration   1: 11.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.260 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ops/ms
Iteration   1: 7.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.972 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.068 ms/op
Iteration   1: 2.390 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.390 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ±(99.9%) 0.063 ms/op
Iteration   1: 1.863 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.863 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.397 ±(99.9%) 0.065 ms/op
Iteration   1: 1.985 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.986 ±(99.9%) 0.114 ms/op
Iteration   1: 3.798 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.798 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.124 ms/op
Iteration   1: 2.289 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   8.849 ms/op
                 createUser·p0.999:  17.335 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13988
  mean =      2.289 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 11819 
    [ 2.500,  3.750) = 1844 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      8.849 ms/op
     p(99.9000) =     17.335 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.081 ms/op
Iteration   1: 2.052 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.525 ms/op
                 existUser·p0.50:   2.050 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.019 ms/op
                 existUser·p0.999:  11.000 ms/op
                 existUser·p0.9999: 11.263 ms/op
                 existUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15797
  mean =      2.052 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 524 
    [ 1.250,  2.500) = 13569 
    [ 2.500,  3.750) = 1658 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.019 ms/op
     p(99.9000) =     11.000 ms/op
     p(99.9900) =     11.263 ms/op
     p(99.9990) =     11.272 ms/op
     p(99.9999) =     11.272 ms/op
    p(100.0000) =     11.272 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.137 ms/op
Iteration   1: 2.370 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.216 ms/op
                 getUser·p0.90:   2.798 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   5.402 ms/op
                 getUser·p0.999:  20.382 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13478
  mean =      2.370 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10316 
    [ 2.500,  5.000) = 3014 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.402 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.131 ms/op
Iteration   1: 4.011 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   6.116 ms/op
                 listUser·p0.999:  14.568 ms/op
                 listUser·p0.9999: 15.090 ms/op
                 listUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8069
  mean =      4.011 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 132 
    [ 2.500,  3.750) = 2616 
    [ 3.750,  5.000) = 4838 
    [ 5.000,  6.250) = 398 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.116 ms/op
     p(99.9000) =     14.568 ms/op
     p(99.9900) =     15.090 ms/op
     p(99.9990) =     15.090 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.486          ops/ms
ClientSimple.existUser                       thrpt         12.149          ops/ms
ClientSimple.getUser                         thrpt         11.260          ops/ms
ClientSimple.listUser                        thrpt          7.972          ops/ms
ClientSimple.createUser                       avgt          2.390           ms/op
ClientSimple.existUser                        avgt          1.863           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.798           ms/op
ClientSimple.createUser                     sample  13988   2.289 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.995           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.849           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.335           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.547           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.547           ms/op
ClientSimple.existUser                      sample  15797   2.052 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.525           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.019           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.000           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.263           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.272           ms/op
ClientSimple.getUser                        sample  13478   2.370 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.797           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.402           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.382           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.413           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.462           ms/op
ClientSimple.listUser                       sample   8069   4.011 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.012           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.046           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.116           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.568           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.090           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.090           ms/op

Benchmark result is saved to 1711327101166.json
