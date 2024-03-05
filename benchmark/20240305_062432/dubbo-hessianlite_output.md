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
# Warmup Iteration   1: 2.486 ops/ms
Iteration   1: 6.223 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.223 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.974 ops/ms
Iteration   1: 14.601 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.601 ops/ms


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
# Warmup Iteration   1: 4.734 ops/ms
Iteration   1: 10.027 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.027 ops/ms


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
# Warmup Iteration   1: 2.179 ops/ms
Iteration   1: 3.588 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.588 ops/ms


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
# Warmup Iteration   1: 6.722 ±(99.9%) 0.086 ms/op
Iteration   1: 3.265 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.265 ms/op


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
# Warmup Iteration   1: 2.993 ±(99.9%) 0.031 ms/op
Iteration   1: 1.811 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.811 ms/op


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.055 ms/op
Iteration   1: 3.146 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.146 ms/op


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
# Warmup Iteration   1: 14.114 ±(99.9%) 0.294 ms/op
Iteration   1: 9.513 ±(99.9%) 0.106 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.513 ms/op


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
# Warmup Iteration   1: 4.888 ±(99.9%) 0.101 ms/op
Iteration   1: 3.093 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   8.571 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 21.366 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10341
  mean =      3.093 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2273 
    [ 2.500,  5.000) = 7811 
    [ 5.000,  7.500) = 136 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      8.571 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     21.366 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.085 ms/op
Iteration   1: 1.856 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.226 ms/op
                 existUser·p0.9999: 7.408 ms/op
                 existUser·p1.00:   7.414 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17320
  mean =      1.856 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 26 
    [1.000, 1.500) = 726 
    [1.500, 2.000) = 13099 
    [2.000, 2.500) = 2854 
    [2.500, 3.000) = 351 
    [3.000, 3.500) = 100 
    [3.500, 4.000) = 29 
    [4.000, 4.500) = 54 
    [4.500, 5.000) = 43 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      5.226 ms/op
     p(99.9900) =      7.408 ms/op
     p(99.9990) =      7.414 ms/op
     p(99.9999) =      7.414 ms/op
    p(100.0000) =      7.414 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.090 ms/op
Iteration   1: 3.305 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  6.130 ms/op
                 getUser·p0.9999: 8.487 ms/op
                 getUser·p1.00:   8.487 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9678
  mean =      3.305 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 106 
    [2.000, 2.500) = 624 
    [2.500, 3.000) = 2194 
    [3.000, 3.500) = 3435 
    [3.500, 4.000) = 2200 
    [4.000, 4.500) = 813 
    [4.500, 5.000) = 175 
    [5.000, 5.500) = 43 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 22 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =      6.130 ms/op
     p(99.9900) =      8.487 ms/op
     p(99.9990) =      8.487 ms/op
     p(99.9999) =      8.487 ms/op
    p(100.0000) =      8.487 ms/op


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
# Warmup Iteration   1: 12.350 ±(99.9%) 0.403 ms/op
Iteration   1: 8.048 ±(99.9%) 0.096 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   7.758 ms/op
                 listUser·p0.90:   10.412 ms/op
                 listUser·p0.95:   11.452 ms/op
                 listUser·p0.99:   13.810 ms/op
                 listUser·p0.999:  18.497 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3954
  mean =      8.048 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 74 
    [ 5.000,  7.500) = 1589 
    [ 7.500, 10.000) = 1769 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.882 ms/op
     p(50.0000) =      7.758 ms/op
     p(90.0000) =     10.412 ms/op
     p(95.0000) =     11.452 ms/op
     p(99.0000) =     13.810 ms/op
     p(99.9000) =     18.497 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.223          ops/ms
Client.existUser                       thrpt         14.601          ops/ms
Client.getUser                         thrpt         10.027          ops/ms
Client.listUser                        thrpt          3.588          ops/ms
Client.createUser                       avgt          3.265           ms/op
Client.existUser                        avgt          1.811           ms/op
Client.getUser                          avgt          3.146           ms/op
Client.listUser                         avgt          9.513           ms/op
Client.createUser                     sample  10341   3.093 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.133           ms/op
Client.createUser:createUser·p0.50    sample          2.810           ms/op
Client.createUser:createUser·p0.90    sample          4.137           ms/op
Client.createUser:createUser·p0.95    sample          4.489           ms/op
Client.createUser:createUser·p0.99    sample          8.571           ms/op
Client.createUser:createUser·p0.999   sample         17.629           ms/op
Client.createUser:createUser·p0.9999  sample         21.366           ms/op
Client.createUser:createUser·p1.00    sample         21.496           ms/op
Client.existUser                      sample  17320   1.856 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.560           ms/op
Client.existUser:existUser·p0.50      sample          1.778           ms/op
Client.existUser:existUser·p0.90      sample          2.208           ms/op
Client.existUser:existUser·p0.95      sample          2.367           ms/op
Client.existUser:existUser·p0.99      sample          3.453           ms/op
Client.existUser:existUser·p0.999     sample          5.226           ms/op
Client.existUser:existUser·p0.9999    sample          7.408           ms/op
Client.existUser:existUser·p1.00      sample          7.414           ms/op
Client.getUser                        sample   9678   3.305 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.231           ms/op
Client.getUser:getUser·p0.50          sample          3.285           ms/op
Client.getUser:getUser·p0.90          sample          4.039           ms/op
Client.getUser:getUser·p0.95          sample          4.276           ms/op
Client.getUser:getUser·p0.99          sample          5.038           ms/op
Client.getUser:getUser·p0.999         sample          6.130           ms/op
Client.getUser:getUser·p0.9999        sample          8.487           ms/op
Client.getUser:getUser·p1.00          sample          8.487           ms/op
Client.listUser                       sample   3954   8.048 ± 0.096   ms/op
Client.listUser:listUser·p0.00        sample          1.882           ms/op
Client.listUser:listUser·p0.50        sample          7.758           ms/op
Client.listUser:listUser·p0.90        sample         10.412           ms/op
Client.listUser:listUser·p0.95        sample         11.452           ms/op
Client.listUser:listUser·p0.99        sample         13.810           ms/op
Client.listUser:listUser·p0.999       sample         18.497           ms/op
Client.listUser:listUser·p0.9999      sample         20.283           ms/op
Client.listUser:listUser·p1.00        sample         20.283           ms/op
