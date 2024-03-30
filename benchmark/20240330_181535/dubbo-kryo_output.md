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
# Warmup Iteration   1: 1.997 ops/ms
Iteration   1: 6.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.993 ops/ms


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
# Warmup Iteration   1: 5.786 ops/ms
Iteration   1: 13.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.870 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.115 ops/ms
Iteration   1: 14.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.705 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.280 ops/ms
Iteration   1: 9.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.442 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ±(99.9%) 0.060 ms/op
Iteration   1: 2.378 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.378 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ±(99.9%) 0.059 ms/op
Iteration   1: 2.192 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.192 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.057 ms/op
Iteration   1: 1.952 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.952 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.080 ms/op
Iteration   1: 2.960 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.960 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ±(99.9%) 0.088 ms/op
Iteration   1: 1.959 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   1.694 ms/op
                 createUser·p0.90:   2.359 ms/op
                 createUser·p0.95:   2.589 ms/op
                 createUser·p0.99:   7.946 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 22.746 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16322
  mean =      1.959 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15241 
    [ 2.500,  5.000) = 894 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     22.746 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ±(99.9%) 0.080 ms/op
Iteration   1: 1.894 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   2.802 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 11.217 ms/op
                 existUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16893
  mean =      1.894 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1036 
    [ 1.250,  2.500) = 15205 
    [ 2.500,  3.750) = 584 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      2.802 ms/op
     p(99.9000) =     10.781 ms/op
     p(99.9900) =     11.217 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.054 ±(99.9%) 0.074 ms/op
Iteration   1: 1.818 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   1.731 ms/op
                 getUser·p0.90:   2.159 ms/op
                 getUser·p0.95:   2.392 ms/op
                 getUser·p0.99:   2.974 ms/op
                 getUser·p0.999:  17.315 ms/op
                 getUser·p0.9999: 17.815 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17576
  mean =      1.818 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 16913 
    [ 2.500,  3.750) = 544 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      2.974 ms/op
     p(99.9000) =     17.315 ms/op
     p(99.9900) =     17.815 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.151 ms/op
Iteration   1: 3.547 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.618 ms/op
                 listUser·p0.50:   3.420 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9019
  mean =      3.547 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 369 
    [ 2.500,  5.000) = 8296 
    [ 5.000,  7.500) = 289 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.993          ops/ms
ClientSimple.existUser                       thrpt         13.870          ops/ms
ClientSimple.getUser                         thrpt         14.705          ops/ms
ClientSimple.listUser                        thrpt          9.442          ops/ms
ClientSimple.createUser                       avgt          2.378           ms/op
ClientSimple.existUser                        avgt          2.192           ms/op
ClientSimple.getUser                          avgt          1.952           ms/op
ClientSimple.listUser                         avgt          2.960           ms/op
ClientSimple.createUser                     sample  16322   1.959 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.876           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.694           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.359           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.946           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.381           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.746           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.036           ms/op
ClientSimple.existUser                      sample  16893   1.894 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.497           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.781           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.217           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.239           ms/op
ClientSimple.getUser                        sample  17576   1.818 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.731           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.731           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.315           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.815           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.088           ms/op
ClientSimple.listUser                       sample   9019   3.547 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.618           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.420           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.808           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.988           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.594           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.594           ms/op

Benchmark result is saved to 1711822272757.json
