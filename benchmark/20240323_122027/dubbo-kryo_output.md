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
# Warmup Iteration   1: 1.353 ops/ms
Iteration   1: 6.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.494 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.781 ops/ms
Iteration   1: 11.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.681 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.466 ops/ms
Iteration   1: 10.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.989 ops/ms


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
# Warmup Iteration   1: 4.632 ops/ms
Iteration   1: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.140 ops/ms


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.068 ms/op
Iteration   1: 2.341 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.341 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.059 ms/op
Iteration   1: 1.790 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.790 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.067 ms/op
Iteration   1: 2.079 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.079 ms/op


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.098 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.203 ms/op


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.095 ms/op
Iteration   1: 2.396 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   2.847 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   9.873 ms/op
                 createUser·p0.999:  15.687 ms/op
                 createUser·p0.9999: 17.165 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13379
  mean =      2.396 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 274 
    [ 1.250,  2.500) = 8891 
    [ 2.500,  3.750) = 3854 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      9.873 ms/op
     p(99.9000) =     15.687 ms/op
     p(99.9900) =     17.165 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.103 ±(99.9%) 0.071 ms/op
Iteration   1: 1.988 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   1.866 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.855 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16074
  mean =      1.988 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 14539 
    [ 2.500,  3.750) = 1025 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.855 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.094 ms/op
Iteration   1: 1.910 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.445 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.281 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  14.893 ms/op
                 getUser·p0.9999: 15.111 ms/op
                 getUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16820
  mean =      1.910 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 15659 
    [ 2.500,  3.750) = 762 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 131 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     15.111 ms/op
     p(99.9990) =     15.122 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.122 ms/op
Iteration   1: 3.383 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.424 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.862 ms/op
                 listUser·p0.999:  11.061 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9446
  mean =      3.383 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1311 
    [ 2.500,  3.750) = 5763 
    [ 3.750,  5.000) = 2222 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.862 ms/op
     p(99.9000) =     11.061 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     11.256 ms/op
     p(99.9999) =     11.256 ms/op
    p(100.0000) =     11.256 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.494          ops/ms
ClientSimple.existUser                       thrpt         11.681          ops/ms
ClientSimple.getUser                         thrpt         10.989          ops/ms
ClientSimple.listUser                        thrpt          8.140          ops/ms
ClientSimple.createUser                       avgt          2.341           ms/op
ClientSimple.existUser                        avgt          1.790           ms/op
ClientSimple.getUser                          avgt          2.079           ms/op
ClientSimple.listUser                         avgt          3.203           ms/op
ClientSimple.createUser                     sample  13379   2.396 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.541           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.847           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.873           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.687           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.165           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.531           ms/op
ClientSimple.existUser                      sample  16074   1.988 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.651           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.866           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.855           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.219           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.907           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.907           ms/op
ClientSimple.getUser                        sample  16820   1.910 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.445           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.281           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.341           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.893           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.111           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.122           ms/op
ClientSimple.listUser                       sample   9446   3.383 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.048           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.424           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.862           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.061           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.256           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.256           ms/op

Benchmark result is saved to 1711196153271.json
