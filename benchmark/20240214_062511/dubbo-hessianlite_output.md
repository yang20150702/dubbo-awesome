# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.399 ops/ms
Iteration   1: 6.526 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.526 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ops/ms
Iteration   1: 13.357 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.357 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.254 ops/ms
Iteration   1: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.350 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.910 ops/ms
Iteration   1: 3.851 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.851 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ±(99.9%) 0.073 ms/op
Iteration   1: 3.048 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.048 ±(99.9%) 0.034 ms/op
Iteration   1: 1.817 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.339 ±(99.9%) 0.044 ms/op
Iteration   1: 3.024 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.352 ±(99.9%) 0.208 ms/op
Iteration   1: 9.340 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.340 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ±(99.9%) 0.097 ms/op
Iteration   1: 3.269 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   7.728 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 10.600 ms/op
                 createUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9829
  mean =      3.269 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 204 
    [ 2.000,  3.000) = 3633 
    [ 3.000,  4.000) = 5036 
    [ 4.000,  5.000) = 615 
    [ 5.000,  6.000) = 84 
    [ 6.000,  7.000) = 99 
    [ 7.000,  8.000) = 81 
    [ 8.000,  9.000) = 16 
    [ 9.000, 10.000) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.728 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     10.600 ms/op
     p(99.9990) =     10.600 ms/op
     p(99.9999) =     10.600 ms/op
    p(100.0000) =     10.600 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.814 ±(99.9%) 0.061 ms/op
Iteration   1: 1.991 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  14.778 ms/op
                 existUser·p0.9999: 14.998 ms/op
                 existUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16089
  mean =      1.991 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 305 
    [ 1.250,  2.500) = 14374 
    [ 2.500,  3.750) = 1201 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     14.998 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.276 ±(99.9%) 0.107 ms/op
Iteration   1: 2.943 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.971 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  6.948 ms/op
                 getUser·p0.9999: 8.941 ms/op
                 getUser·p1.00:   8.946 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10869
  mean =      2.943 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 32 
    [1.000, 1.500) = 90 
    [1.500, 2.000) = 300 
    [2.000, 2.500) = 1684 
    [2.500, 3.000) = 4043 
    [3.000, 3.500) = 3469 
    [3.500, 4.000) = 741 
    [4.000, 4.500) = 356 
    [4.500, 5.000) = 81 
    [5.000, 5.500) = 27 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 32 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.971 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      6.948 ms/op
     p(99.9900) =      8.941 ms/op
     p(99.9990) =      8.946 ms/op
     p(99.9999) =      8.946 ms/op
    p(100.0000) =      8.946 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.183 ±(99.9%) 0.531 ms/op
Iteration   1: 8.401 ±(99.9%) 0.152 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   7.856 ms/op
                 listUser·p0.90:   11.436 ms/op
                 listUser·p0.95:   13.156 ms/op
                 listUser·p0.99:   20.160 ms/op
                 listUser·p0.999:  28.994 ms/op
                 listUser·p0.9999: 31.097 ms/op
                 listUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3791
  mean =      8.401 ±(99.9%) 0.152 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 100 
    [ 5.000,  7.500) = 1560 
    [ 7.500, 10.000) = 1396 
    [10.000, 12.500) = 512 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      7.856 ms/op
     p(90.0000) =     11.436 ms/op
     p(95.0000) =     13.156 ms/op
     p(99.0000) =     20.160 ms/op
     p(99.9000) =     28.994 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.526          ops/ms
Client.existUser                       thrpt         13.357          ops/ms
Client.getUser                         thrpt          8.350          ops/ms
Client.listUser                        thrpt          3.851          ops/ms
Client.createUser                       avgt          3.048           ms/op
Client.existUser                        avgt          1.817           ms/op
Client.getUser                          avgt          3.024           ms/op
Client.listUser                         avgt          9.340           ms/op
Client.createUser                     sample   9829   3.269 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.055           ms/op
Client.createUser:createUser·p0.50    sample          3.162           ms/op
Client.createUser:createUser·p0.90    sample          3.990           ms/op
Client.createUser:createUser·p0.95    sample          4.358           ms/op
Client.createUser:createUser·p0.99    sample          7.728           ms/op
Client.createUser:createUser·p0.999   sample         10.322           ms/op
Client.createUser:createUser·p0.9999  sample         10.600           ms/op
Client.createUser:createUser·p1.00    sample         10.600           ms/op
Client.existUser                      sample  16089   1.991 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.637           ms/op
Client.existUser:existUser·p0.50      sample          1.903           ms/op
Client.existUser:existUser·p0.90      sample          2.462           ms/op
Client.existUser:existUser·p0.95      sample          2.683           ms/op
Client.existUser:existUser·p0.99      sample          4.358           ms/op
Client.existUser:existUser·p0.999     sample         14.778           ms/op
Client.existUser:existUser·p0.9999    sample         14.998           ms/op
Client.existUser:existUser·p1.00      sample         15.008           ms/op
Client.getUser                        sample  10869   2.943 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.524           ms/op
Client.getUser:getUser·p0.50          sample          2.920           ms/op
Client.getUser:getUser·p0.90          sample          3.559           ms/op
Client.getUser:getUser·p0.95          sample          3.971           ms/op
Client.getUser:getUser·p0.99          sample          4.653           ms/op
Client.getUser:getUser·p0.999         sample          6.948           ms/op
Client.getUser:getUser·p0.9999        sample          8.941           ms/op
Client.getUser:getUser·p1.00          sample          8.946           ms/op
Client.listUser                       sample   3791   8.401 ± 0.152   ms/op
Client.listUser:listUser·p0.00        sample          1.720           ms/op
Client.listUser:listUser·p0.50        sample          7.856           ms/op
Client.listUser:listUser·p0.90        sample         11.436           ms/op
Client.listUser:listUser·p0.95        sample         13.156           ms/op
Client.listUser:listUser·p0.99        sample         20.160           ms/op
Client.listUser:listUser·p0.999       sample         28.994           ms/op
Client.listUser:listUser·p0.9999      sample         31.097           ms/op
Client.listUser:listUser·p1.00        sample         31.097           ms/op
