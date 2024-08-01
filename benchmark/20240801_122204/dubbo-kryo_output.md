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
# Warmup Iteration   1: 1.743 ops/ms
Iteration   1: 6.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.763 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.198 ops/ms
Iteration   1: 13.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.131 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.373 ops/ms
Iteration   1: 12.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.435 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ops/ms
Iteration   1: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.381 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.065 ms/op
Iteration   1: 2.209 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.209 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.065 ms/op
Iteration   1: 2.147 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.147 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.260 ±(99.9%) 0.058 ms/op
Iteration   1: 1.802 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.802 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.889 ±(99.9%) 0.111 ms/op
Iteration   1: 3.925 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.925 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.692 ±(99.9%) 0.096 ms/op
Iteration   1: 1.990 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.369 ms/op
                 createUser·p0.50:   1.825 ms/op
                 createUser·p0.90:   2.249 ms/op
                 createUser·p0.95:   2.494 ms/op
                 createUser·p0.99:   6.310 ms/op
                 createUser·p0.999:  28.557 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16072
  mean =      1.990 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15281 
    [ 2.500,  5.000) = 543 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.369 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      6.310 ms/op
     p(99.9000) =     28.557 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.077 ±(99.9%) 0.077 ms/op
Iteration   1: 1.801 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.348 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.384 ms/op
                 existUser·p0.99:   3.460 ms/op
                 existUser·p0.999:  17.315 ms/op
                 existUser·p0.9999: 18.157 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17765
  mean =      1.801 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 244 
    [ 1.250,  2.500) = 16907 
    [ 2.500,  3.750) = 452 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      3.460 ms/op
     p(99.9000) =     17.315 ms/op
     p(99.9900) =     18.157 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.079 ms/op
Iteration   1: 1.932 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   1.745 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  19.071 ms/op
                 getUser·p0.9999: 19.795 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16521
  mean =      1.932 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 14989 
    [ 2.500,  3.750) = 1194 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     19.795 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.131 ms/op
Iteration   1: 3.132 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  6.817 ms/op
                 listUser·p0.9999: 10.116 ms/op
                 listUser·p1.00:   10.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10201
  mean =      3.132 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 202 
    [ 2.000,  3.000) = 4997 
    [ 3.000,  4.000) = 3731 
    [ 4.000,  5.000) = 1089 
    [ 5.000,  6.000) = 137 
    [ 6.000,  7.000) = 38 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      6.817 ms/op
     p(99.9900) =     10.116 ms/op
     p(99.9990) =     10.125 ms/op
     p(99.9999) =     10.125 ms/op
    p(100.0000) =     10.125 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.763          ops/ms
ClientSimple.existUser                       thrpt         13.131          ops/ms
ClientSimple.getUser                         thrpt         12.435          ops/ms
ClientSimple.listUser                        thrpt          8.381          ops/ms
ClientSimple.createUser                       avgt          2.209           ms/op
ClientSimple.existUser                        avgt          2.147           ms/op
ClientSimple.getUser                          avgt          1.802           ms/op
ClientSimple.listUser                         avgt          3.925           ms/op
ClientSimple.createUser                     sample  16072   1.990 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.369           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.825           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.310           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.557           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.295           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.295           ms/op
ClientSimple.existUser                      sample  17765   1.801 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.348           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.460           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.315           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.157           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.285           ms/op
ClientSimple.getUser                        sample  16521   1.932 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.526           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.745           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.071           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.071           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.795           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.923           ms/op
ClientSimple.listUser                       sample  10201   3.132 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.096           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.986           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.448           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.817           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.116           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.125           ms/op

Benchmark result is saved to 1722514666778.json
