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
# Warmup Iteration   1: 1.879 ops/ms
Iteration   1: 7.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.094 ops/ms


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
# Warmup Iteration   1: 4.681 ops/ms
Iteration   1: 11.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.688 ops/ms


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
# Warmup Iteration   1: 7.026 ops/ms
Iteration   1: 14.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.186 ops/ms


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
# Warmup Iteration   1: 5.071 ops/ms
Iteration   1: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.110 ops/ms


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.069 ms/op
Iteration   1: 2.440 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.440 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.047 ms/op
Iteration   1: 1.989 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.989 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.055 ms/op
Iteration   1: 2.222 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.222 ms/op


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.095 ms/op
Iteration   1: 3.611 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.611 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.098 ms/op
Iteration   1: 2.337 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.692 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  14.374 ms/op
                 createUser·p0.9999: 15.395 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13690
  mean =      2.337 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 10399 
    [ 2.500,  3.750) = 2599 
    [ 3.750,  5.000) = 372 
    [ 5.000,  6.250) = 165 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.692 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     14.374 ms/op
     p(99.9900) =     15.395 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.063 ms/op
Iteration   1: 2.220 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.207 ms/op
                 existUser·p0.50:   2.130 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   4.049 ms/op
                 existUser·p0.999:  17.662 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14405
  mean =      2.220 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 11768 
    [ 2.500,  3.750) = 2329 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.207 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      4.049 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.068 ms/op
Iteration   1: 1.896 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.432 ms/op
                 getUser·p0.50:   1.757 ms/op
                 getUser·p0.90:   2.269 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  18.322 ms/op
                 getUser·p0.9999: 18.850 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16847
  mean =      1.896 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 15652 
    [ 2.500,  3.750) = 905 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =     18.322 ms/op
     p(99.9900) =     18.850 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.301 ms/op
Iteration   1: 3.485 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.117 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.542 ms/op
                 listUser·p0.999:  27.148 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9171
  mean =      3.485 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 300 
    [ 2.500,  5.000) = 8540 
    [ 5.000,  7.500) = 257 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.542 ms/op
     p(99.9000) =     27.148 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.094          ops/ms
ClientSimple.existUser                       thrpt         11.688          ops/ms
ClientSimple.getUser                         thrpt         14.186          ops/ms
ClientSimple.listUser                        thrpt          8.110          ops/ms
ClientSimple.createUser                       avgt          2.440           ms/op
ClientSimple.existUser                        avgt          1.989           ms/op
ClientSimple.getUser                          avgt          2.222           ms/op
ClientSimple.listUser                         avgt          3.611           ms/op
ClientSimple.createUser                     sample  13690   2.337 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.836           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.692           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.890           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.374           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.395           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.401           ms/op
ClientSimple.existUser                      sample  14405   2.220 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.207           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.834           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.049           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.662           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.826           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.826           ms/op
ClientSimple.getUser                        sample  16847   1.896 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.432           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.757           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.592           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.322           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.850           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.940           ms/op
ClientSimple.listUser                       sample   9171   3.485 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.300           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.117           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.542           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.148           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.886           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.886           ms/op

Benchmark result is saved to 1711260634426.json
