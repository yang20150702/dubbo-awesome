# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 5.461 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.461 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.551 ops/ms
Iteration   1: 11.972 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.972 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ops/ms
Iteration   1: 7.727 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.727 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.198 ops/ms
Iteration   1: 3.490 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.490 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.020 ±(99.9%) 0.096 ms/op
Iteration   1: 3.141 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.141 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ±(99.9%) 0.041 ms/op
Iteration   1: 1.898 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.898 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.081 ms/op
Iteration   1: 3.501 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.501 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.311 ±(99.9%) 0.260 ms/op
Iteration   1: 9.827 ±(99.9%) 0.119 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.988 ±(99.9%) 0.121 ms/op
Iteration   1: 3.493 ±(99.9%) 0.169 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.617 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  90.440 ms/op
                 createUser·p0.9999: 96.600 ms/op
                 createUser·p1.00:   96.600 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9166
  mean =      3.493 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 9019 
    [ 10.000,  20.000) = 106 
    [ 20.000,  30.000) = 6 
    [ 30.000,  40.000) = 3 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 5 
    [ 70.000,  80.000) = 8 
    [ 80.000,  90.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.617 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     90.440 ms/op
     p(99.9900) =     96.600 ms/op
     p(99.9990) =     96.600 ms/op
     p(99.9999) =     96.600 ms/op
    p(100.0000) =     96.600 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ±(99.9%) 0.071 ms/op
Iteration   1: 2.023 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.421 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.917 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   4.984 ms/op
                 existUser·p0.999:  15.450 ms/op
                 existUser·p0.9999: 16.479 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15958
  mean =      2.023 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 513 
    [ 1.250,  2.500) = 12814 
    [ 2.500,  3.750) = 2300 
    [ 3.750,  5.000) = 178 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.917 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.984 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     16.479 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.265 ±(99.9%) 0.095 ms/op
Iteration   1: 3.359 ±(99.9%) 0.160 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   4.015 ms/op
                 getUser·p0.95:   4.650 ms/op
                 getUser·p0.99:   9.074 ms/op
                 getUser·p0.999:  89.618 ms/op
                 getUser·p0.9999: 99.746 ms/op
                 getUser·p1.00:   99.746 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9506
  mean =      3.359 ±(99.9%) 0.160 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 9416 
    [ 10.000,  20.000) = 38 
    [ 20.000,  30.000) = 6 
    [ 30.000,  40.000) = 7 
    [ 40.000,  50.000) = 4 
    [ 50.000,  60.000) = 6 
    [ 60.000,  70.000) = 8 
    [ 70.000,  80.000) = 7 
    [ 80.000,  90.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.015 ms/op
     p(95.0000) =      4.650 ms/op
     p(99.0000) =      9.074 ms/op
     p(99.9000) =     89.618 ms/op
     p(99.9900) =     99.746 ms/op
     p(99.9990) =     99.746 ms/op
     p(99.9999) =     99.746 ms/op
    p(100.0000) =     99.746 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.686 ±(99.9%) 0.366 ms/op
Iteration   1: 7.823 ±(99.9%) 0.150 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   7.307 ms/op
                 listUser·p0.90:   10.306 ms/op
                 listUser·p0.95:   11.829 ms/op
                 listUser·p0.99:   17.410 ms/op
                 listUser·p0.999:  34.020 ms/op
                 listUser·p0.9999: 37.421 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4077
  mean =      7.823 ±(99.9%) 0.150 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 201 
    [ 5.000,  7.500) = 2027 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      7.307 ms/op
     p(90.0000) =     10.306 ms/op
     p(95.0000) =     11.829 ms/op
     p(99.0000) =     17.410 ms/op
     p(99.9000) =     34.020 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.461          ops/ms
Client.existUser                       thrpt         11.972          ops/ms
Client.getUser                         thrpt          7.727          ops/ms
Client.listUser                        thrpt          3.490          ops/ms
Client.createUser                       avgt          3.141           ms/op
Client.existUser                        avgt          1.898           ms/op
Client.getUser                          avgt          3.501           ms/op
Client.listUser                         avgt          9.827           ms/op
Client.createUser                     sample   9166   3.493 ± 0.169   ms/op
Client.createUser:createUser·p0.00    sample          1.294           ms/op
Client.createUser:createUser·p0.50    sample          3.006           ms/op
Client.createUser:createUser·p0.90    sample          3.850           ms/op
Client.createUser:createUser·p0.95    sample          4.617           ms/op
Client.createUser:createUser·p0.99    sample         10.568           ms/op
Client.createUser:createUser·p0.999   sample         90.440           ms/op
Client.createUser:createUser·p0.9999  sample         96.600           ms/op
Client.createUser:createUser·p1.00    sample         96.600           ms/op
Client.existUser                      sample  15958   2.023 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.421           ms/op
Client.existUser:existUser·p0.50      sample          1.778           ms/op
Client.existUser:existUser·p0.90      sample          2.917           ms/op
Client.existUser:existUser·p0.95      sample          3.265           ms/op
Client.existUser:existUser·p0.99      sample          4.984           ms/op
Client.existUser:existUser·p0.999     sample         15.450           ms/op
Client.existUser:existUser·p0.9999    sample         16.479           ms/op
Client.existUser:existUser·p1.00      sample         16.548           ms/op
Client.getUser                        sample   9506   3.359 ± 0.160   ms/op
Client.getUser:getUser·p0.00          sample          0.800           ms/op
Client.getUser:getUser·p0.50          sample          2.957           ms/op
Client.getUser:getUser·p0.90          sample          4.015           ms/op
Client.getUser:getUser·p0.95          sample          4.650           ms/op
Client.getUser:getUser·p0.99          sample          9.074           ms/op
Client.getUser:getUser·p0.999         sample         89.618           ms/op
Client.getUser:getUser·p0.9999        sample         99.746           ms/op
Client.getUser:getUser·p1.00          sample         99.746           ms/op
Client.listUser                       sample   4077   7.823 ± 0.150   ms/op
Client.listUser:listUser·p0.00        sample          1.526           ms/op
Client.listUser:listUser·p0.50        sample          7.307           ms/op
Client.listUser:listUser·p0.90        sample         10.306           ms/op
Client.listUser:listUser·p0.95        sample         11.829           ms/op
Client.listUser:listUser·p0.99        sample         17.410           ms/op
Client.listUser:listUser·p0.999       sample         34.020           ms/op
Client.listUser:listUser·p0.9999      sample         37.421           ms/op
Client.listUser:listUser·p1.00        sample         37.421           ms/op
